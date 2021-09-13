var y;
m=0; //margin
function start()
{
     y= setInterval(run,100);

     function run(){
       if(m==1200)  //width almost the car can go
       {
         clearInterval(y); 
       }
       else  //Run a car
       {
          m+=5;
      var x=document.getElementById("img");
      x.style.marginLeft=m+'px';
       }
    }

}
function stop() //stop btton
{
  clearInterval(y);
}
