<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mon premier site</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>Bienvenue sur mon premier site</h1>
        <p class="msg">
           Bonjour ! 👋<br>
            Je suis encore débutant en programmation et développement web, 
            et ceci est ma première page que je crée.   
            J’espère que ça vous plaira 😄
        </p>
        <p class="small">— Je commence de zéro et je veux apprendre pas à pas —</p>
    </div>
</body>
</html>
body{
    background-color:#f19ce3 ;
    font-family: Arial, sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
}
.container {
    background: rgb(171, 138, 206);
    width: 308px;
    padding: 25px;
    text-align:center;
    border-radius: 12px;
    box-shadow: 0 4px rgba(28, 28, 16, 0.1);
}
h1 {
    color: #eee9e9;
    margin-bottom: 15px;
}
.msg {
    color: #444;
    line-height: 1.8;
    margin-bottom: 15px;
    font-size: 17px;    
}
.small {
    color: #eadfdf;
    font-size: 14px;
}

    font-size: 14px;

