# Magic-Eightball
Magic Eight Ball project from CodeCademy to test adding HTML and CSS to the existing Java

<script> 
  //Greeting
let userName = 'Tracy';

if (userName = 'Tracy') {
console.log(`Hello ${userName}!`); 
}
else {
  console.log(`Hello!`);
}

//User Question
let userQuestion = 'Will I win the lottery?';

let randomNumber = Math.floor(Math.random()*8);

let eightBall = '';

switch(randomNumber) {
  case 0: 
    eightBall = 'It is certain';
  		break;
  case 1: 
    eightBall = 'It is decidedly so';
  		break;
  case 2: 
    eightBall = 'Repy hazy try again';
  		break;
   case 3: 
    eightBall = 'Cannot predict now';
  		break;
   case 4: 
    eightBall = 'Dont count on it';
  		break;
   case 5: 
    eightBall = 'My source says no';
  		break;
   case 6: 
    eightBall = 'Outlook not so good';
  		break;
   case 7: 
    eightBall = 'Signs point to yes';
  		break;

                 }

    console.log(`The user asked: ${userQuestion} `);
    console.log(`The eight ball answered: ${eightBall}`);
</script>
