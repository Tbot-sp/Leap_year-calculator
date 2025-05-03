# Leap_year-calculator
## 用来输出2000到3000年之间的闰年呢

// Write code below 💖
let i = 2000;

while (i<3000) {

  if (i%4==0 && i%100!= 0){
    console.log(i)}
  
  else if (i%400 ==0){
    console.log(i)}
  i = i+1
   
}