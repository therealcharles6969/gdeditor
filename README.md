<head>
    <title>GDPLAYER</title>

    <link href="styles.css" type="text/css" rel="stylesheet">
    <link rel="icon" href="icon.png">
</head>

<body>
    <div style="position:absolute; bottom: 0%; left: 0%; width: 100%">
		<img class="cornerPiece" src="corner.png" width="7%;">
	</div>
    <div style="position:absolute; bottom: 0%; right: 0%; width: 100%; text-align: right;">
		<img class="cornerPiece" src="corner.png" width="7%;" style="transform: scaleX(-1);  pointer-events: none">
	</div>
    
  <div style="position:absolute; top: 2%; left: 1.5%; width: 10%; height: 25%; pointer-events: none">
		<img class="gdButton yesClick" id="backButton" src="back.png" height="30%" onclick="backButton()" tabindex="1">
	</div>

  <center>
    <div id="textboxBox">
            
      <textarea class="mAdjust logoMode" id="input" placeholder="Level Name"></textarea>
  </div>
</center>
<center>
  <div id="textboxBox">
            
    <textarea class="mAdjust logoMode" id="input" placeholder="Discription (optional)"></textarea>
</div>
</center>

  <center>
    <p><a tabindex="1" href="file:///Users/Charles/Desktop/GDPLayer%20/edit.html"><img class="menubutton menu-saved" src="edit.png" height="150"
      width="150" title="Edit Levels"></a>
      ⠀⠀⠀⠀
      <a tabindex="1" href="file:///Users/Charles/Desktop/GDPLayer%20/Play.html"><img class="menubutton menu-saved" src="play.png" height="150"
        width="150" title="Play Levels"></a>
      ⠀⠀⠀⠀
        <a tabindex="1" href="file:///Users/Charles/Desktop/GDPLayer%20/Play.html"><img class="menubutton menu-saved" src="share.png" height="150"
          width="150" title="Share Levels"></a>

    </p>
  </center>

  <div style="position:absolute; top: 2%; right: 1.5%; width: 10%; text-align: right">
		<img class="gdButton" style="margin-bottom: 12%" src="delete.png" width="60%" onclick="clearFilters()">
		<a href="https://www.robtopgames.com/files/GDEditor.pdf"><img class="gdButton" style="margin-bottom: 12%" id="showFilters" nolist="true" src="xd.gif" width="60%" onclick="$('#filters').show()"></a>
		<img class="gdButton" id="listSearch" style="margin-bottom: 12%" src="copy.png" width="60%">
		<img class="gdButton" src="btn_up.png" width="60%" onclick="$('#customlist').show()">
	</div>

  <script>alert("run");</script>
</body>
