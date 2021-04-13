
<html>html sucks
<title>College List</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<body>
  
  
  
<div class="w3-sidebar w3-bar-block w3-collapse w3-card" style="width:200px;" id="mySidebar">
  <button class="w3-bar-item w3-button w3-hide-large"
  onclick="w3_close()">Close &times;</button>
  <a href="#" class="w3-bar-item w3-button">Link 1</a>
  <a href="#" class="w3-bar-item w3-button">Link 2</a>
  <a href="#" class="w3-bar-item w3-button">Link 3</a>
</div>

<div class="w3-main" style="margin-left:200px">

<div class="w3-teal">
  <button class="w3-button w3-teal w3-xlarge" onclick="w3_open()">&#9776;</button>
  <div class="w3-container">
    <h1>My Page</h1>
  </div>
  </div>
</div>

<script>
function w3_open() {
  document.getElementById("mySidebar").style.display = "block";
}

function w3_close() {
  document.getElementById("mySidebar").style.display = "none";
}
</script>



<!-- Header -->
<header class="w3-display-container w3-content w3-wide" style="max-width:1500px;" id="home">
  <img class="w3-image" src="https://miro.medium.com/max/2048/1*zw-CgiuY2Q_cOt0uNG3f0w.jpeg" alt="Mainimg" width="1500" height="800">
  <div class="w3-display-middle w3-margin-top w3-center">
    <h1 class="w3-xxlarge w3-text-white"><span class="w3-padding w3-black w3-opacity-min"><b>College</b></span> <span class="w3-hide-small w3-text-light-grey">List</span></h1>
  </div>
</header>

<!-- Page content -->
<div class="w3-content w3-padding" style="max-width:1564px">

  <!-- Project Section -->
  <div class="w3-container w3-padding-32" id="Universities">
    <h3 class="w3-border-bottom w3-border-light-grey w3-padding-16">Universities</h3>
  </div>

  <div class="w3-row-padding">
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-display-container">
        <div class="w3-display-topleft w3-black w3-padding">United States</div>
        <img src="https://d2cbg94ubxgsnp.cloudfront.net/Pictures/480x270//5/4/7/143547_SQBRC_Exterior_PM_June-2019.jpg" alt="pic" style="width:100%">
        <p><button class="w3-button w3-light-grey w3-block">Go to</button></p>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-display-container">
        <div class="w3-display-topleft w3-black w3-padding">Canada</div>
        <img src="https://news.ubc.ca/wp-content/uploads/2019/04/UBC.jpg" alt="pic" style="width:100%">
        <p><button class="w3-button w3-light-grey w3-block">Go to</button></p>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-display-container">
        <div class="w3-display-topleft w3-black w3-padding">Oceania</div>
        <img src="https://teanabroad.org/wp-content/uploads/2015/12/U-Melbourne-Media-1-1.jpg" alt="pic" style="width:100%">
        <p><button class="w3-button w3-light-grey w3-block">Go to</button></p>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-display-container">
        <div class="w3-display-topleft w3-black w3-padding">Asia</div>
        <img src="https://www.channelnewsasia.com/image/11194802/16x9/991/557/678581a6d9326f7aadc6c95ca72a1b7c/kG/file-photo--utown--nus.jpg" alt="pic" style="width:100%">
        <p><button class="w3-button w3-light-grey w3-block">Go to</button></p>
      </div>
    </div>
  </div>

 

  <!-- About Section -->
  <div class="w3-container w3-padding-32" id="Colleges">
    <h3 class="w3-border-bottom w3-border-light-grey w3-padding-16">Modules</h3>
    <p> Colleges List
    </p>
  </div>


 <div class="w3-row-padding w3-grayscale">
    <div class="w3-col l3 m6 w3-margin-bottom">
      <img src="https://i.ytimg.com/vi/l0PT01Wqe1Y/maxresdefault.jpg" alt="pic" style="width:100%">
      <h3>University Websites</h3>
      <p class="w3-opacity"></p>
      <p>Official University websites</p>
      <button onclick='window.open("UniWebsites.html")'>
  Go to
</button>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <img src="https://mma.prnewswire.com/media/595586/CollegeVine_Green__1_Logo.jpg?p=facebook" alt="pic" style="width:100%">
      <h3>Collegevine Website</h3>
      <p class="w3-opacity"></p>
      <p>Goes to collegevine website  </p>
       <button onclick='window.location.assign("https://www.collegevine.com/")'>
  Go to
</button>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <img src="https://www.topschoolsintheusa.com/wp-content/uploads/2018/04/Best-Engineering-Schools-in-California.png" alt="pic" style="width:100%">
      <h3>Accepted List</h3>
      <p class="w3-opacity"></p>
      <p>List of Acceptances</p>
      <button onclick='window.location.assign("acceptedList.html")'>
  Go to
</button>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <img src="https://www.socialbakers.com/website/storage/2020/06/Content-Calendar.jpg" alt="pic" style="width:100%">
      <h3>Important dates</h3>
      <p class="w3-opacity"></p>
      <p>Application and decision dates   </p>
      <button onclick='window.location.assign("temporary.html")'>
  Go too
</button>
    </div>
  </div>
  
<!-- Image of location/map -->
<div class="w3-container">
  <img src="/w3images/map.jpg" class="w3-image" style="width:100%">
</div>

<!-- End page content -->
</div>


<!-- Footer -->
<footer class="w3-center w3-black w3-padding-16">
  <p>Powered by my pp<a href="https://www.w3schools.com/w3css/default.asp" title="W3.CSS" target="_blank" class="w3-hover-text-green"></a></p>
</footer>

</body>
</html>
