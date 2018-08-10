# hello-world
我希望对我的分支文档进行修改，内容如下：
this is my world.
<!DOCTYPE html>
<html lang=en>
<head>
    <meta charset='utf-8'>
    <title>document</title>
</head>
<body>
    <script>
        // do{
        //     //从弹框录入数据并打印
        //     var input = prompt('输入数据：');
        //     console.log(input)
        // }while(input != 'exit');
        var year = Number(prompt('year'));
        var month = Number(prompt('month'));
        var days = Number(prompt('days'));
        var totalDays = 0;
        var i = 1;
        while(i<month){
            switch(i){
                case 1:
                case 3:
                case 5:
                case 7:
                case 8:
                case 10:
                    totalDays += 31;
                    break;
                case 4:
                case 6:
                case 9:
                case 11:
                    totalDays += 30;
            }
            i ++
        }
        do{
           totalDays += 30;
        }while(
            switch(month){}
            );
        do{
           totalDays += 31;
        }while();
    </script>
</body>
</html>
