# HannasSTILGUIDEN<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta name="viewport" content="width=device-width">
    <link href="https://fonts.googleapis.com/css?family=Quicksand:300,400" rel="stylesheet">
    <link rel="stylesheet" href="./styles.css" type="text/css">
    <meta charset="utf-8">
    <title>Stilhjälp</title>
  </head>
  <body>
    <div class="content">
    <div class="introduction">
      <div class="Rubrik1">
        <h1>HANNAs STILGUIDEN </h1>
      </div>
      <div class="Rubrik2">
        <h1> VILL DU VETA MER OM DINA MÖBLERS HISTORIA?</h1>
      </div>
      <p>Vi lever i en tid där <strong>slit-och-släng-samhället</strong> dominerar. Där befolkningen hellre köper <strong>billigt skräp, som går sönder fort</strong>
        för att ha råd att <br>
        följa tidens snabba trendväxlingar. Före att investera i mer kostasamma kvalitetsmöbler som har kapaciteten att hålla i hundratals år.
        I en tid <br>
        där Sverige är i framkant att värna om miljön, så är detta väldigt motsägelsefullt. Jag hoppas med denna sida kunna vecka intresset<br>
        för äldre möbler! Genom att ge möbler en historia så ger jag dom även ett liv och därmed ett större värde. Steg 1 är att ta reda på vad JUST DU <br>
         har för möbel. Efter detta test så kommer du få veta mer om den tid som din möbel "föddes" under. Du får även veta om klassiska <br>
         materialval och smarta konstruktioner som också är en stark grund till varför äldre möbler generellt beyder BÄTTRE Möbler</p>

         <div class="InspirationsBilder">
           <img src="https://cdn3.cdnme.se/4155438/6-3/img_6217_-_copy_53457e529606ee2e2096a751.jpg" alt="MiljöTänk" height="130px"/>
           <img src="https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/piles-of-wood-royalty-free-image-106548715-1531507536.jpg?crop=1.00xw:0.756xh;0,0&resize=4098:*" alt="StarkKonstruktion" height="130px"/>
           <img src="http://www.educe.se/educe/think/vasa/images/Vasaeye.gif" alt="GustafVasa" height="130px"/>
           <img src="http://www.mobelkonservering.se/uploads/3/1/9/4/31946749/9681059_orig.jpg" alt="HannaLundin" height="130px"/>
         </div>
         <p> Sidan är skapad av:<a href="http://mobelkonservering.se">Hannas Möbekonservering</a></p>
  </div>

<div class="FirstQuestions">
<h3>Vi börjar med några första frågor för att rensa ur bland stilarna!</h3>
  <div class="Questions">
    <ul>
      <li>Har stolen textilier?</li>
      <li>Har stolen rotting?</li>
      <li>Har stolen sjögräs?</li>
      <li>Har stolen pappersfiber?</li>
      <li>Tror du det finns inslag av plast?</li>
    </ul>
  </div>
</div>
</div>
</body>
</html>

body{
  width: 100%;
  background-color: #EAE2D6;
}

.content{
  margin-left: 100px;
  margin-right: 100px;
}

.introduction{
  background-color: #C9D1C8;
  margin-top: 20px;
  padding-top: 30px;
  padding-bottom: 20px;
  text-align: center;
}

.InspirationsBilder{
  display: flex;
  flex-direction: row;
  justify-content: center;
}

.FirstQuestions{
  padding-top: 10px;
  background-color: #34675C;
  margin-top: 20px;
  padding-bottom: 20px;
  padding-left: 50px;
  padding-right: 50px;
  font-family: 'Quicksand', sans-serif;
  text-align: left;
}

.Rubrik1{
  font-family: 'Quicksand', sans-serif;
  color: #34675C;
  font-size: 41px;
  margin-bottom: 0px;
}

.Rubrik2{
  font-family: 'Quicksand', sans-serif;
  color: #34675C;
  font-size: 17px;
  margin-top: 0px;
  margin-bottom: 50px;
}

h1{ margin: 0px;
}

/* unvisited link */
a:link {
    color: #324851;
}

/* visited link */
a:visited {
    color: #34675C;
}

/* mouse over link */
a:hover {
    color: #34675C;
}

/* selected link */
a:active {
    color: #86AC41;
}

/* For mobile */
@media (max-width: 600px) {

  .Rubrik1{
    font-family: 'Quicksand', sans-serif;
    color: #34675C;
    font-size: 30px;
    margin-bottom: 0px;
  }

  .Rubrik2{
    font-family: 'Quicksand', sans-serif;
    color: #34675C;
    font-size: 7px;
    margin-top: 0px;
    margin-bottom: 50px;
  }
  .InspirationsBilder{
    display: flex;
    flex-direction: column;
    justify-content:space-between;
}
