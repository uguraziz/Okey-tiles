```html
<!DOCTYPE html>
<body>
    <script>
        console.log(
            new Array(13).fill().reduce((acc, curr, index) => {
                return [
                    ...acc,
                    {
                        number: index + 1,
                        color: 'BLACK'
                    },
                    {
                        number: index + 1,
                        color: 'BLACK'
                    },
                    {
                        number: index + 1,
                        color: 'RED'
                    },
                    {
                        number: index + 1,
                        color: 'RED'
                    },
                    {
                        number: index + 1,
                        color: 'BLUE'
                    },
                    {
                        number: index + 1,
                        color: 'BLUE'
                    },
                    {
                        number: index + 1,
                        color: 'ORANGE'
                    },
                    {
                        number: index + 1,
                        color: 'ORANGE'
                    }
                ]
            }, [
                {
                    number : 'FAKE_1',
                    color: 'FAKE'
                },{
                    number : 'FAKE_2',
                    color: 'FAKE'
                },
            ])
        );
    </script>
</body>
</html>
```
