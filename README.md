<html>
<head>
   <title>JavaScript - Center Text</title>
</head>
   <body>
      <script> 
         const centerText = () => {    
            var centerText = document.createElement('p');
            centerText.innerText = 'A github website';
            centerText.style.color = 'black';
            centerText.style.textAlign = 'center';
            document.body.appendChild(centerText);
         } 	 
         centerText();
      </script>
   </body>
</html>
