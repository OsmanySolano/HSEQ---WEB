<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>HSEQ Interactivo</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
<style>
* { box-sizing: border-box; margin: 0; padding: 0; }
body {
font-family: "Roboto", sans-serif;
background: #eef1f5;
color: #333;
}


header {
background: linear-gradient(135deg, #005baa, #003f73);
color: white;
padding: 40px 20px;
text-align: center;
animation: fade 1s ease;
}


header h1 {
font-size: 2.5rem;
letter-spacing: 1px;
}


nav {
display: flex;
justify-content: center;
gap: 20px;
background: white;
padding: 15px;
box-shadow: 0 3px 6px rgba(0,0,0,0.1);
position: sticky;
top: 0;
z-index: 10;
}


nav button {
background: #005baa;
color: white;
border: none;
padding: 12px 20px;
border-radius: 8px;
cursor: pointer;
transition: 0.3s ease;
font-size: 15px;
}


nav button:hover {
background: #0073d1;
transform: translateY(-3px);
}


.section {
display: none;
padding: 40px 20px;
animation: fade 0.5s ease;
max-width: 1100px;
margin: auto;
}


.active {
display: block;
}


@keyframes fade {
from {opacity: 0;} to {opacity: 1;}
}


.grid {
display: grid;
grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
gap: 20px;
</html>
