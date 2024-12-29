## Create a counter in JavaScript


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>Counter</h1>
    <p id="counter">0</p>
</body>
<script>
    let count=0;
    let counter=document.getElementById('counter');
    setInterval(()=>{
        cout++;
        counter.innerText=count;
    },1000
    )
</script>
</html>
