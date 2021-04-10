# jQuery-insert-text--after-image
jQuery codding insert text after image
<script>
		function afterText(){
			var txt1 = "<b>I</b>";
			var txt2 = $("<li></li>").text("love");
			var txt3 = document.createElement("b");
			txt3.innerHTML= "jQuery";
			$("img").after(txt1,txt2,txt3);
		}
	</script>
    </head>)
     <body>
      <img src= "C:\Users\hp\Desktop\w3jquery.gif" alt="jQuery" width="100px" height="100px">
      <p>Click the button insert text after the image</p>
      <button onclick="afterText()">Insert After</button>
