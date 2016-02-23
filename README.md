# Lan-Hong-House
Chinese Restauarant
<!DOCTYPE html>

<head>

<script src="/assets/jquery.js"></script>

<link href='https://fonts.googleapis.com/css?family=Raleway:400,200' rel='stylesheet' type='text/css'>

<style>
h1 {
  font-family: 'Raleway', sans-serif;
  font-size: 75px;
  text-align: center;
  margin: 60px 0 0 0;
  color: #ff4d4d;
}

h2 {
  text-align: center;
  font-size: 25px;
  margin: 0px 0 40px 0;
  color: #ffff99;
}

h3 {
  text-align: center;
  font-size: 15px;
  margin: 0px 0 10px 0;
  color: #bbbbbb  
}

body {
  font-family: helvetica, sans-serif;
  margin: 0 auto;
  max-width: 600px;
  background: #001a33;
}
div {
  height: 200px;
  background-size: cover;
  position: relative;
  margin: 40px 0 0 0;
  border-radius: 12px;
}

p {
  color: rgba(255,255,255,1);
  background-color: rgba(0,0,0,1);
  background: -webkit-linear-gradient(bottom, rgba(0,0,0,1), rgba(0,0,0,.4));
  background: -moz-linear-gradient(bottom, rgba(0,0,0,1), rgba(0,0,0,.4));
  padding: 10px;
  line-height: 28px;
  text-align: center;
  border-radius: 150px;
  width: 150px;
  position: absolute;
  height: 30px;
}

.show-description p{
  height: 150px;
}

.show-description small{
  opacity:1;
}


.first{
  width: 300px;
  height: 300px;
  border-radius: 150px;
  -webkit-border-radius: 150px;
  -moz-border-radius: 150px;
  background-image: url("http://img15.deviantart.net/0400/i/2010/088/a/e/spring_rolls_by_splgum.jpg");
  box-shadow: 0 0 8px rgba(0, 0, 0, .4);
  -webkit-box-shadow: 0 0 8px rgba(0, 0, 0, .8);
  -moz-box-shadow: 0 0 8px rgba(0, 0, 0, .8);
  position: relative;
  top: 20px;
  left: 130px;
}

.chicken{
  width: 300px;
  height: 300px;
  border-radius: 150px;
  -webkit-border-radius: 150px;
  -moz-border-radius: 150px;
  background-image: url("http://farm5.static.flickr.com/4086/4983077603_eb6bc34be6.jpg");
  box-shadow: 0 0 8px rgba(0, 0, 0, .4);
  -webkit-box-shadow: 0 0 8px rgba(0, 0, 0, .4);
  -moz-box-shadow: 0 0 8px rgba(0, 0, 0, .4);
  position: relative;
  top: -130px;
  left: -140px;
}
  
.duck{
  width: 300px;
  height: 300px;
  border-radius: 150px;
  -webkit-border-radius: 150px;
  -moz-border-radius: 150px;
  background-image: url("http://sevenstarschinese.co.uk/wp-content/uploads/2012/08/Roast-Duck-on-Rice.jpg");
  background-position: center;
  box-shadow: 0 0 8px rgba(0, 0, 0, .4);
  -webkit-box-shadow: 0 0 8px rgba(0, 0, 0, .4);
  -moz-box-shadow: 0 0 8px rgba(0, 0, 0, .4);
  position: relative;
  top: -470px;
  left: 400px;
}

.veg{
  width: 300px;
  height: 300px;
  border-radius: 150px;
  -webkit-border-radius: 150px;
  -moz-border-radius: 150px;
  background-image: url("http://cookdiary.net/wp-content/uploads/images/Ma-Po-Tofu_14552.jpg");
  box-shadow: 0 0 8px rgba(0, 0, 0, .4);
  -webkit-box-shadow: 0 0 8px rgba(0, 0, 0, .8);
  -moz-box-shadow: 0 0 8px rgba(0, 0, 0, .8);
  position: relative;
  top: -630px;
  left: 130px;
}

.beef{
  width: 300px;
  height: 300px;
  border-radius: 150px;
  -webkit-border-radius: 150px;
  -moz-border-radius: 150px;
  background-image: url("https://s3.amazonaws.com/trycaviar.com/offers/381/16873.jpg");
  box-shadow: 0 0 8px rgba(0, 0, 0, .4);
  -webkit-box-shadow: 0 0 8px rgba(0, 0, 0, .4);
  -moz-box-shadow: 0 0 8px rgba(0, 0, 0, .4);
  position: relative;
  top: -750px;
  left: -140px;
}

.pork{
   width: 300px;
  height: 300px;
  border-radius: 150px;
  -webkit-border-radius: 150px;
  -moz-border-radius: 150px;
  background-image: url("https://seansadventuresinflavortown.files.wordpress.com/2015/08/img_9744.jpg");box-shadow: 0 0 8px rgba(0, 0, 0, .4);
  -webkit-box-shadow: 0 0 8px rgba(0, 0, 0, .4);
  -moz-box-shadow: 0 0 8px rgba(0, 0, 0, .4);
  position: relative;
  top: -1100px;
  left: 400px;
}

.dessert {
   width: 300px;
  height: 300px;
  border-radius: 150px;
  -webkit-border-radius: 150px;
  -moz-border-radius: 150px;
  background-image: url("http://food-blogger.com/wp-content/uploads/2014/03/Banana-Fritters.jpg");box-shadow: 0 0 8px rgba(0, 0, 0, .4);
  -webkit-box-shadow: 0 0 8px rgba(0, 0, 0, .4);
  -moz-box-shadow: 0 0 8px rgba(0, 0, 0, .4);
  position: relative;
  top: -1210px;
  left: 130px;
}

h4 {
  text-align: center;
  font-size: 15px;
  margin: 0px 0 10px 0;
  color: #bbbbbb 
}

</style>


<body>

<h1>lan hong house</h1>

<h2>chinese restaurant & take-away</h2>

<h3>&bull; tues-sun 11:30am-11:00pm &bull; 12 norfolk st. cambridge &bull; delivery &#163;1.5 &bull;
</h3>
  

<div class="first show-description">
<p>appetizers & soups <br />
<small>starting at &#163;2.5</small></p>
</div>

<div class="chicken show-description">
<p>chicken dishes<br />
<small>starting at &#163;4.5</small></p>
</div>

<div class="duck show-description">
<p>duck dishes<br />
<small>&#163;5</small></p>
</div>

<div class="veg show-description">
<p>veg dishes<br />
<small>starting at &#163;3</small></p>
</div>

<div class="beef show-description">
<p>beef dishes<br />
<small>&#163;4.5</small></p>
</div>

<div class="pork show-description">
<p>pork dishes<br />
<small>&#163;4.5</small></p>
</div>

<div class="dessert show-description">
<p>desserts <br /> <span class="price">&#163;3.5<br /></p>
<small>dessert 1 <br /> dessert 2 </small>
</div>

<script>
  $('div').on('click', function() {
    $(this).toggleClass('show-description');
  });
</script>

</body>
