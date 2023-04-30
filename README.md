<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Petsumer</title> 
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: white;
      display:flex;
      width: 204.4vh;
      height: 315vh;
    }

    img {
      margin-left: 30vh;
      margin-top: 1vh;
    }

 .div{
  margin-top: 10vh;
  margin-left: 0vh;
  width: 205.4vh;
  height: 8vh;
  background: linear-gradient(to left, #6699ff 0%, #ff0066 100%);
  border-radius: 0vh;
  position: absolute;
 }

.input-box {
  padding-top: 4vh;
  position: absolute;
  margin-top: 0.5vh;
  margin-left: 72vh;
  height: 3vh;
  width: 60vh;
  background: rgb(193, 220, 233);
  border-radius: 8px;
  box-shadow: 0 5px 10px rgba(49, 45, 45, 0.1);
}
.input-box i,
.input-box .button {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
}

.input-box input {
  height: 100%;
  width: 65%;
  outline: none;
  font-size: 18px;
  font-weight: 400;
  padding-left: 10px; 
  background-color: transparent;
  position: absolute;
  top: 2px;
  border: none;
}
.input-box .button {
  right: 8px;
  font-size: 14px;
  font-weight: 400;
  color: rgb(255, 255, 255);
  border: none;
  padding: 12px 30px;
  border-radius: 10px;
  background: linear-gradient(to left, #6699ff 0%, #ff0066 100%);
  cursor: pointer;
}
.input-box .button:active {
  transform: translateY(-50%) scale(0.98);
}

.category{
  position: absolute;
  width: 160vh;
  height: 18vh;
  background-color: white;
  border-width: 1px;
  border-style: solid; 
  border-radius: 2vh;
  border-color: rgb(223, 63, 90);
  margin-top: 28vh;
  margin-left: 22vh;
}

.category img {
  width: 128px;
  height: 90px;
  margin-left: 37px;
  cursor: pointer;
  width: 130px;
  height:85px;
  border-width: 1px;
  border-style: solid; 
  border-radius: 2vh;
  border-color: rgb(223, 63, 90);
  margin-top: 2.5vh;
}
/*adidebs fotos mausis mitanisas*/
.category img:hover {
  transform: scale(1.2);
}
.pirveli{
  position: absolute;
  width: 100vh;
  height:36vh;
  background-color: white;
  border-width: 1px;
  border-style: solid; 
  border-radius: 2vh;
  border-color:  red;
  margin-top: 50vh;
  margin-left: 22vh;
}

.pirveli img{
  width: 40vh;
  height: 32vh;
  border-radius: 2vh;
  margin-left: 3vh;
  margin-top: 2vh;
}

.meore{
  position: absolute;
  width: 56vh;
  height:36vh;
  background-color: white;
  border-width: 1px;
  border-style: solid; 
  border-radius: 2vh;
  border-color:  red;
  margin-top: 50vh;
  margin-left: 126vh;
}

.meore img:first-child{
  width: 15vh;
  height: 10vh;
  margin-left: 4vh;
  margin-top: 2vh;
}

.meore img{
  width: 4vh;
  height: 3vh;
  margin-left: 4vh;
  margin-top: 1.3vh;
  display: flex;
  flex-direction: column-reverse; /* ganalagebs horizontalurad */
}

.meore img:last-child{
  width: 18vh;
  height: 15vh;
  margin-left: 37vh;
  margin-top: -14vh;
}

.blah{
  position: absolute;
  width: 50vh;
  height: 47vh;
  background-color: white;
  border-width: 1px;
  border-style: solid; 
  border-radius: 2vh;
  border-color:  red;
  margin-top: 98vh;
  margin-left: 22vh;
}

.blah img{
  margin-top: 2vh;
  margin-left: 2vh;
  width: 46vh;
  border-radius: 2vh;
}

.blah2{
  position: absolute;
  width: 50vh;
  height: 47vh;
  background-color: white;
  border-width: 1px;
  border-style: solid; 
  border-radius: 2vh;
  border-color:  red;
  margin-top: 98vh;
  margin-left: 76.8vh;
}

.blah2 img{
  margin-top: 2vh;
  margin-left: 2vh;
  width: 46vh;
  border-radius: 2vh;
}

.blah3{
  position: absolute;
  width: 50vh;
  height: 47vh;
  background-color: white;
  border-width: 1px;
  border-style: solid; 
  border-radius: 2vh;
  border-color: red;
  margin-top: 98vh;
  margin-left: 132vh;
}

.blah3 img{
  margin-top: 2vh;
  margin-left: 2vh;
  width: 46vh;
  border-radius: 2vh;
}

.cats{
  position: absolute;
  width: 50vh;
  height: 47vh;
  background-color: white;
  border-width: 1px;
  border-style: solid; 
  border-radius: 2vh;
  border-color:  red;
  margin-top: 158vh;
  margin-left: 22vh;
}

.cats img{
  margin-top: 2vh;
  margin-left: 2vh;
  width: 46vh;
  border-radius: 2vh;
}

.cats2{
  position: absolute;
  width: 50vh;
  height: 47vh;
  background-color: white;
  border-width: 1px;
  border-style: solid; 
  border-radius: 2vh;
  border-color:  red;
  margin-top: 158vh;
  margin-left: 76.8vh;
}

.cats2 img{
  margin-top: 2vh;
  margin-left: 2vh;
  width: 46vh;
  border-radius: 2vh;
}

.cats3{
  position: absolute;
  width: 50vh;
  height: 47vh;
  background-color: white;
  border-width: 1px;
  border-style: solid; 
  border-radius: 2vh;
  border-color:  red;
  margin-top: 158vh;
  margin-left: 132vh;
}

.cats3 img{
  margin-top: 2vh;
  margin-left: 2vh;
  width: 46vh;
  border-radius: 2vh;
}

.lastrow{
  position: absolute;
  width: 50vh;
  height: 47vh;
  background-color: white;
  border-width: 1px;
  border-style: solid; 
  border-radius: 2vh;
  border-color:  red;
  margin-top: 218vh;
  margin-left: 22vh;
}

.lastrow img{
  margin-top: 2vh;
  margin-left: 2vh;
  width: 46vh;
  border-radius: 2vh;
}

.lastrow2{
  position: absolute;
  width: 50vh;
  height: 47vh;
  background-color: white;
  border-width: 1px;
  border-style: solid; 
  border-radius: 2vh;
  border-color:  red;
  margin-top: 218vh;
  margin-left: 76.8vh;
}

.lastrow2 img{
  margin-top: 2vh;
  margin-left: 2vh;
  width: 46vh;
  border-radius: 2vh;
}

.lastrow3{
  position: absolute;
  width: 50vh;
  height: 47vh;
  background-color: white;
  border-width: 1px;
  border-style: solid; 
  border-radius: 2vh;
  border-color: red;
  margin-top: 218vh;
  margin-left: 132vh;
}

.lastrow3 img{
  margin-top: 2vh;
  margin-left: 2vh;
  width: 46vh;
  border-radius: 2vh;
}

.lastcontainer{
  background-color: #bdb7bd;
  width: 205.4vh;
  height: 34vh;
  margin-top: 274vh;
  margin-right: 20vh;
  border-radius: 0vh;
  position: absolute;
}

.lastcontainer img{
      margin-left: 30vh;
      margin-top: -3vh;
}

  </style>
</head>
<body>
  <img src="https://i.ibb.co/3Nm7Pbw/Screenshot-72.png" width="30vh" height="30vh"/>
  <p style="margin-top: 1vh; font-size:30px; color:#bdb7bd">PETSUMER</p><br><br><br><br>
<div class="div">
   <div class="input-box">
    <i class="uil uil-search"></i>
    <input type="text" placeholder="" />
    <button class="button">Search</button>
   </div>
</div>
<p style="position:absolute; margin-top: 22vh; font-size: 3vh; margin-left: 42%; color: coral;
text-shadow: -1px 0 black, 0 1px black, 1px 0 black, 0 -1px black">CHOOSE A CATEGORY</p>
<div class="category">
  <a href="" target="_blank">
    <img src="https://i.ibb.co/JKmj6PL/Screenshot-59.png" alt="Your Image" />
  </a>
  <a href="" target="_blank">
    <img src="https://i.ibb.co/d20wtWD/Screenshot-64.png" alt="Your Image" />
  </a>
  <a href="" target="_blank">
    <img src="https://i.ibb.co/kXpHpTJ/Screenshot-65.png" alt="Your Image" />
  </a>
  <a href="" target="_blank">
    <img src="https://i.ibb.co/JRXfMX3/Screenshot-66.png"  alt="Your Image" />
  </a>
  <a href="" target="_blank">
    <img src="https://i.ibb.co/LkVKNSF/Screenshot-67.png"alt="Your Image" />
  </a>
  <a href="" target="_blank">
    <img src="https://i.ibb.co/KwznRmn/Screenshot-68.png" alt="Your Image" />
  </a>
  </div>

  <div class="pirveli">
    <img src="https://i.ibb.co/KmK9Vzg/Screenshot-70.png" alt="Your Image" />  
    <p style="position: absolute; font-size: 3vh; margin-top: -33vh; margin-left: 45vh;"><b>11 Best Dog Harnesses of 2023, <br> According to Experts and Pet Parents</p></b>
    <p style="position: absolute; margin-left: 45vh; margin-top: -24vh">When it's time to take your beloved pooch on a W-A-L-K, having the right gear will make all the difference. Whether you've got a dog that can't help but pull you all the way around the block, or a new pup that hasn't seemed to master their training just yet, the right dog harness can help make your trips outside fun for everyone involved.</p>
    <a href="https://www.goodhousekeeping.com/life/pets/g28198571/best-dog-harnesses/" target="_blank" style="position: absolute; margin-left: 2vh; margin-top: 31vh; color:rgb(223, 63, 90); ;">Read More</a>
  </div>   
   
  <div class="meore">
    <img src="https://i.ibb.co/QkLJZcR/Screenshot-71.png" alt="Your Image" />  
    <p style="position: absolute; margin-top: -8vh; margin-left: 21vh; font-size: 4vh; color:rgb(223, 63, 90);"><b>Why Trust Us?</b></p>
    <p style="font-size: 2.4vh; margin-left: 5vh; margin-top: 0vh;">Your pet is your world and you need pet advice you can trust. Here at Petsumer we care about pets just as much as you do an it is our goal to help you become the best pet parent you can be</p>
    <img src="https://i.ibb.co/MfPPKTG/sun.png" alt="Your Image" width="40vh"/> 
    <img src="https://i.ibb.co/MfPPKTG/sun.png" alt="Your Image" width="40vh"/> 
    <img src="https://i.ibb.co/MfPPKTG/sun.png" alt="Your Image" width="40vh"/> 
    <p style="position: absolute; margin-left: 11vh; font-size: 2.6vh;  margin-top: -11.3vh; font-family:Georgia, 'Times New Roman', Times, serif">EXPERTICE</p>
    <p style="position: absolute; margin-left: 11vh; font-size: 2.6vh;  margin-top: -7.3vh; font-family:Georgia, 'Times New Roman', Times, serif">EXPERTICE</p>
    <p style="position: absolute; margin-left: 11vh; font-size: 2.6vh;  margin-top: -3.5vh; font-family:Georgia, 'Times New Roman', Times, serif">TRUSTWORTHINESS</p>
    <img src="https://i.ibb.co/3Nm7Pbw/Screenshot-72.png" alt="Your Image" />  
  </div> 

  <p style="position: absolute; margin: 50vh; margin-left: 23vh; margin-top: 90vh; font-size: 4vh;color: #5a585a;">Dog Harness</p>
  <a href="..." target="_blank" style="color:rgb(223, 63, 90); margin-top: 91vh; font-size: 3vh; margin-left: 112vh;" >View All</a>

  <div class="blah">
    <img src="https://i.ibb.co/809nP4F/Screenshot-80.png" alt="Your Image" />
    <p style="font-size: 3.5vh; margin-left: 2vh; margin-top: 1vh; font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;"><b>Harnesses For Boxers</b> </p>
    <p style="font-size: 2.2vh; margin-left: 2vh; margin-top: -2vh;">So you’ve decided it’s time to transition your Boxer dog to a harness? Here we take the guesswork out of it for you as we review the best harnesses for your boxer dog. Boxer dogs have a unique body shape. </p>
    <a href="https://www.loveyourdog.com/best-boxer-harness/" target="_blank" style="position: absolute; margin-left: 2vh; margin-top: -0.5vh; color:rgb(223, 63, 90); ;">Read More</a>
  </div>

  <div class="blah2">
    <img src="https://i.ibb.co/LS3XHXM/Screenshot-78.png" alt="Your Image" />
    <p style="font-size: 3.5vh; margin-left: 2vh; margin-top: 1vh; font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;"><b> Best Harnesses for Golden Retrievers</b></p>
    <p style="font-size: 2.2vh; margin-left: 2vh; margin-top: -2vh;">Golden Retrievers are big dogs with a gentle temperament. If you are looking for the ultimate house pet, it is hard to go wrong with a Golden.</p>
    <a href="https://www.hepper.com/best-harness-for-golden-retrievers/" target="_blank" style="position: absolute; margin-left: 2vh; margin-top: -1vh; color:rgb(223, 63, 90); ;">Read More</a>
  </div>

  <div class="blah3">
    <img src="https://i.ibb.co/55HBYjG/Screenshot-79.png" alt="Your Image" />
    <p style="font-size: 3.5vh; margin-left: 2vh; margin-top: 1vh; font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;"><b> Best Harnesses For Pitbuls</b></p>
    <p style="font-size: 2.2vh; margin-left: 2vh; margin-top: -2vh;">While Pit Bulls can make excellent pets in the right home, they are powerful dogs that may require a little extra support on a leash due to their strength.</p>
    <a href="https://petkeen.com/best-harnesses-for-pit-bulls/" target="_blank" style="position: absolute; margin-left: 2vh; margin-top: -0.5vh; color:rgb(223, 63, 90); ;">Read More</a>
 </div>

 <p style="position: absolute; margin: 50vh; margin-left: 23vh; margin-top: 150vh; font-size: 4vh;color: #5a585a;">Cat Brushes</p>
 <a href="..." target="_blank" style="color:rgb(223, 63, 90); margin-top: 151vh; font-size: 3vh; margin-left: -10vh;" >View All</a> 

 <div class="cats">
  <img src="https://i.ibb.co/Dt60RyL/Screenshot-81.png" alt="Your Image" />
  <p style="font-size: 3.5vh; margin-left: 2vh; margin-top: 1vh; font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;"><b>7 Best Cat Brushes of 2023</b> </p>
  <p style="font-size: 2.2vh; margin-left: 2vh; margin-top: -2vh;">Brushing a cat removes dirt, skin flakes, and hair that has already been shed. It also stimulates blood circulation which improves the condition of their skin, keeping their coat healthy.</p>
  <a href="https://www.thesprucepets.com/best-cat-brushes-4590060" target="_blank" style="position: absolute; margin-left: 2vh; margin-top: -0.5vh; color:rgb(223, 63, 90); ;">Read More</a>
</div>

<div class="cats2">
  <img src="https://i.ibb.co/ZYF0sX7/Screenshot-82.png" alt="Your Image" />
  <p style="font-size: 3.5vh; margin-left: 2vh; margin-top: 1vh; font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;"><b> Brushes for Persian Cats</b></p>
  <p style="font-size: 2.2vh; margin-left: 2vh; margin-top: -2vh;">Persian cats require quite a bit of grooming to look their best. Otherwise, their coat can easily become matted and dirty. Brushing not only removes loose hair and keeps their fur tangle-free</p>
  <a href="https://petkeen.com/best-brushes-for-persian-cats/" target="_blank" style="position: absolute; margin-left: 2vh; margin-top: -1vh; color:rgb(223, 63, 90); ;">Read More</a>
</div>

<div class="cats3">
  <img src="https://i.ibb.co/NWs1tYK/Screenshot-83.png" alt="Your Image" />
  <p style="font-size: 3.5vh; margin-left: 2vh; margin-top: 1vh; font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;"><b>Best Cat Brush Glove:</b> </p>
  <p style="font-size: 2.2vh; margin-left: 2vh; margin-top: -2vh;">Best Overall Cat Brush Glove: Delomo Pet Grooming Glove Gentle Deshedding Brush Glove.This is our top pick when it comes to the best Cat Brush Glove, thanks to its special design and high rankings on platforms such as Amazon and Chewy.</p>
  <a href="https://www.loveyourdog.com/best-boxer-harness/" target="_blank" style="position: absolute; margin-left: 2vh; margin-top: -0.5vh; color:rgb(223, 63, 90); ;">Read More</a>
</div>

<p style="position: absolute; margin: 50vh; margin-left: 23vh; margin-top: 210vh; font-size: 4vh;color: #5a585a;">Recent Posts</p>
<a href="..." target="_blank" style="color:rgb(223, 63, 90); margin-top: 211vh; font-size: 3vh; margin-left: -10vh;" >View All</a> 

<div class="lastrow">
  <img src="https://i.ibb.co/kSf9dZC/1234-3.png"/></a>
  <p style="font-size: 3.5vh; margin-left: 2vh; margin-top: 1vh; font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;"><b> harnesses for doodles</b></p>
  <p style="font-size: 2.2vh; margin-left: 2vh; margin-top: -2vh;">The short chase usually ends with her jerking her neck when she reaches the end of the leash. So in order for her not to hurt herself, we decided to switch to a harness while working on leash training.</p>
  <a href="https://happyoodles.com/2020/01/the-best-dog-harness-for-doodles/" target="_blank" style="position: absolute; margin-left: 2vh; margin-top: -0.5vh; color:rgb(223, 63, 90); ;">Read More</a>
</div>

<div class="lastrow2">
  <img src="https://i.ibb.co/TcGJSGs/1234-1.png" alt="Your Image" />
  <p style="font-size: 3.5vh; margin-left: 2vh; margin-top: 1vh; font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;"><b>Harnesses for French Bulldogs</b> </p>
  <p style="font-size: 2.2vh; margin-left: 2vh; margin-top: -2vh;">What’s not to love about the French Bulldog? They’ve consistently topped the list as one of the most popular breeds in the United States for the last five years</p>
  <a href="https://petkeen.com/best-harnesses-for-french-bulldogs/" target="_blank" style="position: absolute; margin-left: 2vh; margin-top: -1vh; color:rgb(223, 63, 90); ;">Read More</a>
</div>

<div class="lastrow3">
  <img src="https://i.ibb.co/Zg0nR5t/1234-2.png" alt="Your Image" />
  <p style="font-size: 3.5vh; margin-left: 2vh; margin-top: 1vh; font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;"><b>Cute Names to Give Your Cat</b></p>
  <p style="font-size: 2.2vh; margin-left: 2vh; margin-top: -2vh;">So you've just brought home a new cat or kitten. After shopping for all the essentials like toys, litter, a collar, and food and getting your furry friend all settled into their new home</p>
  <a href="https://www.countryliving.com/life/a40799263/best-cute-cat-names/" target="_blank" style="position: absolute; margin-left: 2vh; margin-top: -0.5vh; color:rgb(223, 63, 90); ;">Read More</a>
</div>

<div class="lastcontainer">
  <br><br><br><br><img src="https://i.ibb.co/Z2968WT/Screenshot-88.png" width="38vh" height="33vh"/>
  <p style="font-size:6.3vh; color:#5a585a; margin-top: -6.2vh; margin-left: 36vh;">PETSUMER</p>
  <p style="font-size:2.7vh; color:#5a585a; margin-top: -4vh; margin-left: 30vh;">some text here. some text here. some text here. some text here.<br>  some text here. some text here. some text here. some text here.<br>  some text here. some text here. some text here. some text here.<br>  some text here. some text here. some text here. some text here.</p>
  <p style="font-size:2.7vh; color:#5a585a; margin-top: -15.6vh; margin-left: 110vh;"> some text here. some text here. some text here.<br>  some text here. some text here. some text here. <br>  some text here. some text here. some text here.<br>  some text here. some text here. some text here.</p>
  <p style="font-size:2.7vh; color:#000000; margin-top: -15vh; margin-left: 175vh;">Disclaimer<br>Our team<br>Privacy</p> 
</div> 

<p style="margin-top: 310vh; margin-left: -93vh;text-shadow: 0 0 3px #FF0000, 0 0 5px #0000FF;"><b>Copyright c 2023 Petsumer</b></p>
</body>
</html>
