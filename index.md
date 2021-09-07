<html>
<style>
  body{
    font-family:Arial;
    background: linear-gradient( rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5) ), url('attachments/backdrop.jfif');
    background-repeat: no-repeat;
    background-size:cover;
    background-attachment: fixed;
  }

  .headrow{
    width: min(95vw, 950px);
    margin: auto
  }
  .headrow:after{
    content: "";
    display: table;
    clear: both;
  }
  .headcolumn{
    float: left;
    height: min(5vw, 50px);
    padding: 0;
  }
  .headtext{
    color: white;
    font-size: min(2vw, 20px);
    text-decoration: none;
    padding: 0;
    vertical-align: min(1vw, 10px);
  }
  .headicon{
    height: min(3vw, 30px);
    padding: 0;
  }

  .profile{
    width: min(50vw, 500px);
    margin: min(2vw, 20px) 0vw;
    border-radius: 50%;
    border: 2px solid white;
  }

  .title{
    color: white;
    font-size: min(8vw, 80px);
    font-weight: bold;
    margin: 0;
    padding: 0;
  }
  .subtitle{
    color: LightGray;
    font-size: min(2.8vw, 28px);
    margin: 0vw 0vw min(4vw, 40px) 0vw;
    padding: 0;
  }

  .linkrow{
    width: min(80vw, 800px);
    margin: 0 auto
  }
  .linkrow:after{
    content: "";
    display: table;
    clear: both;
  }
  .linkcolumn{
    float: left;
    width: 30%;
    height: min(8vw, 80px);
    padding: 0;
    background-repeat: no-repeat;
    background-size: auto min(3vw, 30px);
    background-position: center center;
    background-color: rgba(255, 255, 255, 0.5);
    border-radius: 10px;
    border: 2px solid white;
    
  }
  .linkcolumn:hover .linkoverlay{
    opacity: 0.5;
  }
  .linkgap{
    float: left;
    width: calc(5% - 6px);
    height: min(8vw, 80px);
    padding: 0;
  }
  .linkoverlay{
    height: 100%;
    width: 100%;
    background-color: black;
    opacity: 0;
    color: white;
    font-size: 20px;
    margin: auto;
    border-radius: 10px;
  }
  
  .pdf{
    background-color:white;
    width: min(80vw, 800px);
    height: min(103.5vw, 1035px);
    margin: min(8vw, 80px) 0vw;
  }
  
  .galleryrow{
    width: min(80vw, 800px);
    height: min(38vw, 380px);
    margin: 0 auto min(calc(4% - 4px), 36px) auto
  }
  .gallerycolumn{
    float: left;
    width: 47.5%;
    height: min(38vw, 380px);
    padding: 0;
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center center;
    border: 2px solid white;
  }
  .gallerycolumn:hover .galleryoverlay{
    opacity: 1;
  }
  .gallerygap{
    float: left;
    width: calc(5% - 8px);
    height: min(38vw, 380px);
    padding: 0;
  }
  .galleryoverlay{
    height: 100%;
    width: 100%;
    background-color: rgba(0, 0, 0, 0.5);
    opacity: 0;
    margin: 0;
    padding: 0;
    background-position: center center;
  }
  .gallerytext{
    padding: 5%;
    color: white;
    font-size: min(2vw, 20px);
    text-align: left;
  }
  
</style>
  
<body>
  <div class=headrow>
    <div class=headcolumn align="left" style="width:40%">
        <embed src="attachments/phone.jpg" class=headicon> <a href="tel:513-708-1629" class=headtext>(513)708-1629</a>
    </div>
    <div class=headcolumn align="right" style="width:60%">
        <embed src="attachments/email.png" class=headicon> <a href="mailto:lienwhite7@gmail.com" class=headtext>lienwhite7@gmail.com</a>
    </div>
  </div>
 
  <p align="center">
    <embed src="attachments/C891BAEA-CADB-4B12-A95A-69ED839A1A11.jpeg" class=profile>
  </p>

  <p class=title align="center">
    Lien White
  </p>
  <p class=subtitle align="center">
    Robotics Engineering - Electrical Engineering Co-Op
  </p>

  <div class="linkrow">
    <div class="linkcolumn" align="center" style ="background-image: url('attachments/GitHubLogo.png');">
      <a href="https://github.com/Lien-White"><div class=linkoverlay></div></a>
    </div>
    <div class=linkgap></div>
    <div class="linkcolumn" align="center" style ="background-image: url('attachments/LinkedIn_Logo.svg.png');">
      <a href="https://www.linkedin.com/in/lien-white"><div class=linkoverlay></div></a>
    </div>
    <div class=linkgap></div>
    <div class="linkcolumn" align="center" style ="background-image: url('attachments/Luminosity.png');">
      <a href="https://theluminositylab.com/"><div class=linkoverlay></div></a>
    </div>
  </div>

  <p align="center">  
    <a href="attachments/White_Lien_Resume.pdf" download><embed src="attachments/White_Lien_Resume.pdf" class=pdf></a>
  </p>
  
  <div class=galleryrow>
    <div class=gallerycolumn align="center" style="background-image: url('attachments/JOOEE.png');">
      <a href="attachments/JOOEE.png" style="text-decoration: none;">
        <div class=galleryoverlay>
          <div class=gallerytext>
            <b>CAN Sarlacc Adapter:</b>
            <p>Board and Software</p>
          </div>
        </div>
      </a>
    </div>
    <div class=gallerygap></div>
    <div class=gallerycolumn align="center" style="background-image: url('attachments/FIP.png');">
      <a href="attachments/FIP.png" style="text-decoration: none;">
        <div class=galleryoverlay>
          <div class=gallerytext>
            <b>Paragon Space Development:</b>
            <p>MSEPA Chassis</p>
          </div>
        </div>
      </a>
    </div>
  </div>
  
  <div class=galleryrow>
    <div class=gallerycolumn align="center" style="background-image: url('attachments/UAVUGVcouple.jpg');">
      <a href="attachments/UAVUGVcouple.jpg" style="text-decoration: none;">
        <div class=galleryoverlay>
          <div class=gallerytext>
            <b>Mesh Networking:</b>
            <p>NASA Big IDEA CHallenge</p>
          </div>
        </div>
      </a>
    </div>
    <div class=gallerygap></div>
    <div class=gallerycolumn align="center" style="background-image: url('attachments/lift.gif');">
      <a href="attachments/lift.gif" style="text-decoration: none;">
        <div class=galleryoverlay>
          <div class=gallerytext>
            <b>Foldable Wing Robotics</b>
            <p>EGR 555: Foldable Robotics</p>
          </div>
        </div>
      </a>
    </div>
  </div>
  
  <div class=galleryrow>
    <div class=gallerycolumn align="center" style="background-image: url('attachments/2wdFC.jpg');">
      <a href="attachments/2wdFC.jpg" style="text-decoration: none;">
        <div class=galleryoverlay>
          <div class=gallerytext>
            <b>Teaching Assistant:</b>
            <p>EGR 304/314 Embedded Systems</p>
          </div>
        </div>
      </a>
    </div>
    <div class=gallerygap></div>
    <div class=gallerycolumn align="center" style="background-image: url('attachments/2wdRO.jpg');">
      <a href="attachments/2wdRO.jpg" style="text-decoration: none;">
        <div class=galleryoverlay>
          <div class=gallerytext>
            <b>Crane Machine:</b>
            <p>EGR 314: Embedded Sytsems Design II</p>
          </div>
        </div>
      </a>
    </div>
  </div>

  <div class=galleryrow>
    <div class=gallerycolumn align="center" style="background-image: url('attachments/piclip.jpg');">
      <a href="attachments/piclip.jpg" style="text-decoration: none;">
        <div class=galleryoverlay>
          <div class=gallerytext>
            <b>Street Sweeper:</b>
            <p>EGR 304: Embedded Sytsems Design I</p>
          </div>
        </div>
      </a>
    </div>
    <div class=gallerygap></div>
    <div class=gallerycolumn align="center" style="background-image: url('attachments/piclipSW.JPG');">
      <a href="attachments/piclipSW.JPG" style="text-decoration: none;">
        <div class=galleryoverlay>
          <div class=gallerytext>
            <b>PiClip Controller:</b>
            <p>Chassis</p>
          </div>
        </div>
      </a>
    </div>
  </div>
  
  <div class=galleryrow>
    <div class=gallerycolumn align="center" style="background-image: url('attachments/wingproto.gif');">
      <a href="attachments/wingproto.gif" style="text-decoration: none;">
        <div class=galleryoverlay>
          <div class=gallerytext>
            <b>Foldable Robotics:</b>
            <p>Wing Prototype</p>
          </div>
        </div>
      </a>
    </div>
    <div class=gallerygap></div>
    <div class=gallerycolumn align="center" style="background-image: url('attachments/wingsim.gif');">
      <a href="attachments/wingsim.gif" style="text-decoration: none;">
        <div class=galleryoverlay>
          <div class=gallerytext>
            <b>Foldable Robotics:</b>
            <p>Wing Simulation</p>
          </div>
        </div>
      </a>
    </div>
  </div>
  
</body>
</html>
