
<!-- saved from url=(0039)http://karo218.ir/Goldhen702/index.html -->
<html manifest="offlinexmb.manifest"><head><meta http-equiv="Content-Type" content="text/html; charset=windows-1252"><title>Karo Host GoldHEN 7.02 FW</title>
	<style>
        .switch {
		  position: relative;
		  display: inline-block;
		  width: 60px;
		  height: 34px;
		}

		.switch input { 
		  opacity: 0;
		  width: 0;
		  height: 0;
		}

		.slider {
		  position: absolute;
		  cursor: pointer;
		  top: 0;
		  left: 0;
		  right: 0;
		  bottom: 0;
		  background-color: #2196F3;
		  -webkit-transition: .4s;
		  transition: .4s;
		}
		
		.slider.new {
		  position: absolute;
		  cursor: pointer;
		  top: 0;
		  left: 0;
		  right: 0;
		  bottom: 0;
		  background-color: #585858;
		  -webkit-transition: .4s;
		  transition: .4s;
		}

		.slider:before {
		  position: absolute;
		  content: "";
		  height: 26px;
		  width: 26px;
		  left: 4px;
		  bottom: 4px;
		  background-color: white;
		  -webkit-transition: .4s;
		  transition: .4s;
		}

		input:checked + .slider {
		  background-color: #2196F3;
		}

		input:focus + .slider {
		  box-shadow: 0 0 1px #2196F3;
		}

		input:checked + .slider:before {
		  -webkit-transform: translateX(26px);
		  -ms-transform: translateX(26px);
		  transform: translateX(26px);
		}

		/* Rounded sliders */
		.slider.round {
		  border-radius: 34px;
		}

		.slider.round:before {
		  border-radius: 50%;
		}
		.button {
		  background:rgba(0,0,0,0.5);
		  box-shadow: 0 5px 20px 0 white;
		  border: 2px solid black;
		  border-radius: 10px;
		  color: white;
		  text-decoration: none;
		  width: 200px;
          height: 35px;
		  display:inline-table;
		  font-family: system-ui;
		  text-align: center;
		}

		.button:focus,
		.button:hover {
		  color: White;
		  box-shadow: 0 5px 50px 0 white;
		  background-color: #0F0F53;
          border-radius: 10px;
		}

		.modal {
  display: none; /* Hidden by default */
  position: fixed; /* Stay in place */
  z-index: 1; /* Sit on top */
  padding-top: 100px; /* Location of the box */
  left: 0;
  top: 0;
  width: 100%; /* Full width */
  height: 100%; /* Full height */
  overflow: auto; /* Enable scroll if needed */
  background-color: rgb(0,0,0); /* Fallback color */
  background-color: rgba(0,0,0,0.4); /* Black w/ opacity */
}
  .content {
  width:80%;
  margin-left:7.5%;
  background:rgba(0,0,0,0.5);
  color:white;
  margin-top:0%;
  font-size:25px;
  text-align:center;
  border-radius:30px;
  padding:20px;
  line-height:20px;
  position:absolute;bottom:0px;
 }
 .title {
  font-size:40px;
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-weight:bolder;
  margin-bottom:10px;
 }
 .yellow {
  color:yellow;
 }
 .hue {
  color:yellow;
  padding:10px;
  border-radius:10px;
  animation:hue 5s linear infinite;
  -webkit-animation: hue 5s linear infinite;
  box-shadow: 0px 0px 50px yellow;
  color:white;
  background:rgba(255,255,0,0.4);
 }
 .hue:hover{
  color:yellow;
  background:transparent;
 }
 @keyframes hue{
 0%{
 filter:hue-rotate(0deg);
 -webkit-filter:hue-rotate(0deg);
 }
 10%{
 box-shadow: 0px 1px 50px yellow;
 }
 20%{
 box-shadow: 1px 1px 50px yellow;
 }
 30%{
 box-shadow: 1px 0px 50px yellow;
 }
 40%{
  box-shadow: 1px -1px 50px yellow;
 }
 50%{
 box-shadow: 0px -1px 50px yellow;
 }
 60%{
 box-shadow: -1px -1px 50px yellow;
 }
 70%{
 box-shadow: -1px 0px 50px yellow;
 }
 80%{
 box-shadow: -1px 1px 50px yellow;
 }
 90%{
 box-shadow: 0px 1px 50px yellow;
 }
 100%{
 filter:hue-rotate(360deg);
 -webkit-filter:hue-rotate(360deg);
 }
 }
 .text {
  padding-bottom:50px;
 }
  .back {
   font-size:25px;
   margin-top:10px;
   display:block;
   line-height:55px;
   width:20%;
   text-decoration:none;
   height:50px;
   background:white;
   color:black;
   border-radius:15px;
  }
  .back:hover{
   border:2px solid white;
   background:transparent;
   box-sizing:border-box;
   color:white;
  }
/* Modal Content */
.modal-content {
  font-family: BFARNAZ;
  font-size: 18px;
  position: relative;
  background-color: #dddddd;
  margin: auto;
  padding: 0;
  border: 1px solid #888;
  width: 50%;
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2),0 6px 20px 0 rgba(0,0,0,0.19);
  -webkit-animation-name: animatetop;
  -webkit-animation-duration: 0.4s;
  animation-name: animatetop;
  animation-duration: 0.4s
}
.titleheadx {
		  background-color: #1A1920;  
		  border-radius: 5px;
		  color: white;
		  padding: .5em;
		  text-decoration: none;
		  text-align: center;
		  margin-top: 17%;
		  margin-bottom: -10px;
		  font-family: system-ui;
}

.titlehead {
		  background-color: #1A1920;  
		  color: white;
		  padding: .5em;
		  text-align: center;
		  margin-top: 0%;
		  font-family: system-ui;
		  font-size:30px;
		  text-shadow: 4px 4px 4px black;
}

		.bg {
		  /* The image used */
		  background-color:#1A1920;
		  font-family: system-ui;
		  /* Center and scale the image nicely */
		  background-position: center;
		  background-repeat: no-repeat;
		  background-size: cover;
		}

       #Progress {
		  color: white;
		}

       #Progressx {
		  color: white;
		}

.pointer {cursor: pointer;}
	</style>
<script>
  window.applicationCache.ondownloading=function(){document.getElementById("progressx").innerHTML="Caching Started!!"};
  window.applicationCache.onprogress=function(a){document.getElementById("progressx").innerHTML="Caching Status: "+(Math.round(100*(a.loaded/a.total)))+"% Completed"};
  window.applicationCache.oncached=function(){document.getElementById("progressx").innerHTML="Cached Successfully!!";setTimeout(function(){document.getElementById("progressx").innerHTML="Reopen the Page !!"; }, 1500);localStorage.cached702="yes";};
  window.applicationCache.onnoupdate=function(){localStorage.cached702="yes";};
  window.applicationCache.onerror=function(){localStorage.cached702="yes";};
</script>
	</head><body onload="if(localStorage.cached702==&#39;yes&#39;)go();" class="bg">
<script>
function print(){}

var scriptCode = '';

function preloadScripts(lst)
{
    for(var i = 0; i < lst.length; i++)
    {
        var xhr = new XMLHttpRequest();
        xhr.open('GET', lst[i], false);
        xhr.send('');
        scriptCode += xhr.responseText + '\n';
    }
}

function done()
{
    if(main_ret == 0 || main_ret == 179)
    {
        alert("You're all set!");
        read_ptr_at(0);
    }
    else
        alert("Jailbreak failed! Reboot your PS4 and try again.");
}

window.midExploit = function()
{
preloadScripts(['702.js', 'jb.js', 'preloader.js', 'goldhen_2.2.2_702.js', 'loader.js'], go);
}

window.postExploit = function()
{
    setTimeout(function() //update the screen one last time...
    {
        eval.call(window, scriptCode);
        done();
    }, 100);
};
</script>
		<script src="./Karo Host GoldHEN 7.02 FW_files/utils.js.&#1041;&#1077;&#1079; &#1085;&#1072;&#1079;&#1074;&#1072;&#1085;&#1080;&#1103;"></script>
		<script src="./Karo Host GoldHEN 7.02 FW_files/int64.js.&#1041;&#1077;&#1079; &#1085;&#1072;&#1079;&#1074;&#1072;&#1085;&#1080;&#1103;"></script>
		<script src="./Karo Host GoldHEN 7.02 FW_files/ps4.js.&#1041;&#1077;&#1079; &#1085;&#1072;&#1079;&#1074;&#1072;&#1085;&#1080;&#1103;"></script>
        <h1 id="progressx" class="titleheadx">Loading ...</h1><br>
		<button style="opacity:0" id="input1" onfocus="handle2()"></button>
		<button style="opacity:0" id="input2"></button>
		<button style="opacity:0" id="input3" onfocus="handle2()"></button>
		<select style="opacity:0" id="select1">
			<option value="value1">Value1</option>
		</select>

</body></html>
