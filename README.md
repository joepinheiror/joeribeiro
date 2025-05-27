<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Currículo - Joelyse Pinheiro Ribeiro</title>
  <link rel="stylesheet" href="csscurriculo.css" />
</head>
<body>
  
  <div class="container">
   <header class="cabecalho">
  <div class="imagem-container">
    <img src="\Users\ADM\Downloads\WhatsApp Image 2025-05-27 at 13.06.05.jpeg" class="foto-perfil" alt="Foto de perfil">
  </div>
  <div class="texto-header">
    <h1>Joelyse Pinheiro Ribeiro</h1>
    <p>Técnica em Informática | Futura Engenheira de Software</p>
    <p>Email: joelyse.ribeiro@gmail.com </p>
    <p>Telefone: (85) 98956-2636</p>
    <p>Visite meu <a href="https://www.linkedin.com/in/joelyse-pinheiro-531515338/" target="_blank">LinkedIn</a>.</p>
</header>


    <section>
      <b><h2>Resumo Profissional</h2></b>
      <p>Iniciei minha trajetória profissional aos 16 anos como estagiária na Digital College Brasil, onde atuo até o momento. 
     Desde então, venho desenvolvendo habilidades interpessoais e organizacionais que me permitem atuar de forma colaborativa e também com autonomia em diferentes tipos de demandas. 
     Tenho facilidade em me adaptar a novos desafios, sou proativa e mantenho uma postura comprometida com a qualidade e eficiência no ambiente de trabalho.
      Mesmo em períodos com menor volume de tarefas, estou sempre em busca de contribuir ativamente com a equipe, demonstrando iniciativa e interesse em aprender continuamente.</p>
    </section>

    <section>
      <h2>Experiência Profissional</h2>
      <div class="item">
        <h3>Digital College – Estagiária</h3>
        <span>Agosto 2024 - Dezembro 2024 </span> 
      </div>
      <div class="item">
        <h3>Digital College – Estagiária</h3>
        <span>Março 2025 - Atual</span>
      </div>
    </section>

    <section>
      <h2>Educação</h2>
      <div class="item">
        <h3>EEEP Comendador Miguel Gurgel – Informática</h3>
        <span>Conclusão: 2024</span>
      </div>
      <div class="item">
        <h3>EEEP Comendador Miguel Gurgel – Techinical English and Digital Literacy </h3>
        <span>Conclusão: Setembro de 2024</span>
      </div>
      <div class="item">
        <h3> Huawei Talents Online – Tecnologia 5G</h3>
        <span>Conclusão: 2024</span>
      </div>
      <div class="item">
        <h3> Curso Google – Google UX/UI Design </h3>
        <span>Conclusão: 2024</span>
      </div>
    </section>

    <section>
      <h2>Habilidades (Softskills e HardSkills)</h2>
      <ul class="skills">
        <li>Comunicação</li>
        <li>Trabalho em equipe</li>
        <li>Criatividade</li>
        <li>Organização</li>
        <li>Liderança</li>
        <li>HTML e CSS </li>
        <li>PHP</li>
        <li>Canva Pro </li>
        <li>Photoshop</li> 
        <li>Premiere Pro</li>
        <li>Proatividade</li>
        <li>Proatividade</li>
      </ul>
    </section>
  </div>
</body>
</html>

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: sans-serif;
  background-color: #f7f7f7;
  color: #333;
  line-height: 1.6;
  padding: 20px;
}

.container {
  max-width: 800px;
  background: #fff;
  margin: auto;
  padding: 40px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  border-radius: 10px;
}
.cabecalho {
  position: relative;
  padding-top: 20px;
}

.imagem-container {
  position: absolute;
  top: 42px;
  right: 0;
  width: 130px;
  height: 130px;
  border-radius: 50%;
  overflow: hidden;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

header {
  text-align: left;
  margin-bottom: 30px;
}

.header-container{
display: flex;
  align-items: center;
  gap: 20px;
}

.foto-perfil {
  width: 100%;
  height: 100%;
  object-fit: cover;
  object-position: center 28%;
  display: block;
}
.texto-header {
  padding-right: 150px; /* espaço pra imagem não sobrepor o texto */
}

header h1 {
  font-size: 2.5rem;
  color: #2c3e50;
}

header p {
  color: #696d6d;
  margin: 3px 3px;
}

h2 {
  color: #175177;
  margin-bottom: 10px;
  border-bottom: 2px solid #8981ff;
  padding-bottom: 0px;
}

.item {
  margin-bottom: 20px;
}

.item h3 {
  font-size: 1.1rem;
  color: #34495e;
}

.item span {
  font-size: 0.9rem;
  color: #999;
}

.skills {
  list-style: none;
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}

.skills li {
  background-color: #3498db;
  color: white;
  padding: 8px 12px;
  border-radius: 20px;
  font-size: 0.9rem;
}


