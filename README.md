<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>TechFuture Summit</title>
  
  <style>
.container-centralizado {
  max-width: 800px;
  margin: 0 auto;
}

body{
    background-image: url('https://c4.wallpaperflare.com/wallpaper/219/288/895/space-spiral-swirl-swirls-wallpaper-preview.jpg');
 color: #000000;

}

 body{
     font-family: 'Franklin Gothic Medium', 'Arial Narrow';
      background-color: #f2f2f2;
    margin: 30px;
    }

header{
    background-color: #2b0053;
 color: white;
  padding: 40px;
      text-align: center;
    }

section{
     background-color: white;
  padding: 20px;
 margin-top: 20px;
    border-radius: 5px;
    }

 h2 {
 color: #4c2c50;
    }

 form label{
     margin-top: 10px;
    }

 form input[type="text"],
 form input[type="email"] {
   width: 100%;
 padding: 8px;
  margin-top: 5px;
      box-sizing: border-box;
    }
button{
      margin-top: 15px;
 padding: 10px 20px;
     background-color: #c300ff;
     color: white;
   border: none;
  cursor: pointer;
    }
 button:hover{
  background-color: #4e14bb;
    }
    h1{
        color:#ffffff;
    }
    .img{
        width: 150px; 
height: 200px; 
 border-radius: 50%; 
 object-fit: cover;
}
.img2{
       width: 150px; 
height: 200px; 
border-radius: 50%; 
  object-fit: cover;
}
.img3{
width: 150px; 
height: 200px; 
border-radius: 50%; 
  object-fit: cover;
}
.img4{
width: 150px; 
height: 200px; 
border-radius: 50%; 
  object-fit: cover;
}

.borda{
            display: inline-block; 
            padding: 5px; 
            border: 2px solid rgb(255, 0, 85); 
        }
.borda2{
            display: inline-block; 
            padding: 10px; 
            border: 8px solidrgb(0, 0, 0); 
        }

  </style>
</head>
<body>
<div class="container-centralizado">  
  <header>
<h1 style="font-size: 50px;">TechFuture Summit</h1>
  </header>

  <section>
 <h2>Sobre o Evento</h2>
    <p><strong>Data:</strong> 4 de setembro de 2025</p>
<p><strong>Local:</strong> Cidade da Música, Salvador-BA</p>
    <p style="color: #4c2c50; font-size: 20px;">A TechConnect ferece uma experiência incrível de uma discussão com desenvolvedores e designers profissionais sobre as novas tendências do mercado tecnológico!</p>
  </section>

  <section>
    <h2>Inscrição</h2>
    <form>
<label for="nome">Nome completo:</label>
<input type="text" id="nome" name="nome" required >

    <label for="email" >E-mail:</label>
 <input type="email" id="email" name="email" required >

 <p>Tipo de ingresso:</p>
<label><input type="radio" name="ingresso" value="Presencial" required>Presencial</label>
 <label><input type="radio" name="ingresso" value="Online" required>Online</label>

 <label> <input type="checkbox" required> Aceito os termos e condições
  </label><br>

<button type="submit">Enviar</button> 
 </form>
  </section>
  
  <section>
    <p style="font-size:25px; color:#4f2c50">Palestrantes</p>
 <img src="https://img.freepik.com/fotos-gratis/mulher-asiatica-satisfeita-com-um-sorriso-largo-penteado-curto-vestido-casualmente-senta-se-a-mesa-do-cafe-gosta-do-tempo-de-lazer-linda-mulher-japonesa-descansando-sozinha-em-restaurante_273609-2712.jpg" class="img" alt="foto de uma mulher asiatica" width="300px">       <img src="https://img.freepik.com/fotos-gratis/mulher-de-vista-superior-com-penteado-afro_23-2150677192.jpg?semt=ais_hybrid&w=740" class="img2" alt="foto de uma mulher sorridente" width="300px">    <img src="https://i.pinimg.com/474x/8f/c4/dd/8fc4dda1b87338d69a9a763ab4c11c10.jpg" class="img3" alt="foto de uma mulher sorridente" width="300px"> <img src="https://www.shutterstock.com/image-photo/young-african-businessman-smiling-while-600nw-1751747738.jpg" class="img4" alt="foto de um homem sorridente" width="300px">
 <p style="color: #99018c;"><span class="borda">Saori Hoshimoto </p>  
 <h5>Desenvolvedora apaixonada por tendências no mundo dos computadores. </h5>
  <p style="color: #99018c;"></ptyle><span class="borda">Helena Souza Matos </p>
 <h5>Designer analista de projetos da Google.</h5>
    <p style="color: #99018c;"></ptyle><span class="borda">Maria Isabel Freire </p>
 <h5>Estudante de Ciências da Computação.</h5>
 <p style="color: #99018c;"></ptyle><span class="borda">Caio Samuel Costa </p>
 <h5>Desenvolvedor Back-end.</h5>

</section>
</div>
</body>
</html>
