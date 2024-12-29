## Counter without setInterval

Without using setInterval, try to code a counter in Javascript. There is a hint at the bottom of the file if you get stuck.

<body>
  <p id="count">0</p>
</body>
<script>
  let a=0;
  setTimeout(()=>{
     a++;
     const c=document.getElementbyId("count");
     c.innerhtml=a;
    },1000)
</script>






































































(Hint: setTimeout)
