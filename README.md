# Leap_year-calculator
## to output the leap year from 2000 to 3000

// Write code below 💖
let i = 2000;

while (i<3000) {

  if (i%4==0 && i%100!= 0){
    console.log(i)
    }
  
  else if (i%400 ==0){
    console.log(i)
    }
  i = i+1 
   
}