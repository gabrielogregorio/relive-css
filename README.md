<div align="center">
  <img height="30" alt="css3" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
  <img height="30" alt="html5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
</div>

<h3 align="center">Relieve CSS</h3>
<p align="center">
  Create CRUDS backend without worrying about CSS
  <br>
  <a href="https://gabrielogregorio.com/projetos/relieve/"><strong>See demo »</strong></a>
  <br>
</p>

![GitHub estrelas](https://img.shields.io/github/stars/gabrielogregorio/relieveCSS)
![GitHub last commit](https://img.shields.io/github/last-commit/gabrielogregorio/relieveCSS?style=flat-square)
![GitHub contributors](https://img.shields.io/github/contributors/gabrielogregorio/relieveCSS)
![GitHub language count](https://img.shields.io/github/languages/count/gabrielogregorio/relieveCSS)
![GitHub repo size](https://img.shields.io/github/repo-size/gabrielogregorio/relieveCSS)

### Introduction 
This project is a mini framework that stylizes HTML tags.

The goal is to provide a minimalist layout and as little use of classes as possible in order to facilitate the development of backend CRUDS.

To include the mini framework in your project, you need to include the relieve.css file in your application, using the command below or a javascript import.

```html
<link rel="stylesheet" href="relieve.css">
```

## Summary
- [Summary](#summary)
- [Components](#components)
  - [Navbar](#navbar)
  - [Breadcrumb](#breadcrumb)
  - [titles](#titles)
  - [Erros](#erros)
  - [Formulary](#formulary)
  - [Select and Datalist](#select-and-datalist)
  - [Summary](#summary-1)
  - [Video](#video)
  - [Image](#image)
  - [Links](#links)
  - [Lists](#lists)
  - [Strong and paragraph](#strong-and-paragraph)
  - [Buttons with links](#buttons-with-links)
  - [Simple table](#simple-table)
  - [Large tables](#large-tables)
  - [Footer](#footer)

## Components
### Navbar
![navbar](images/nav.png)
```html
<nav>
  <a href="#"><img src="images/logo.png"></a>
  <a class="active" href="#">Home</a>
  <a href="#">Itens</a>
  <a href="#">Users</a>
</nav>
```

-----------------------------------------------

### Breadcrumb
![breadcrumb](images/bread.png)
```html
<div class="breadcrumb">
  <a href="#">Posts</a>&gt;
  <a href="#">Edit</a>&gt;
  <a class="active" href="#">User</a>
</div>
```

-----------------------------------------------

### titles
![titles](images/title.png)
```html
<section>
  <div class="container">
    <h1>Título do Website</h1>
    <h2>Subtítulo 1</h2>
    <h3>Subtítulo 2</h3>
    <h4>Subtítulo 3</h4>
    <h5>Subtítulo 4</h5>
    <h6>Subtítulo 4</h6>
  </div>
</section>
```

-----------------------------------------------


### Erros
![paragraph error](images/mensagem.png)
```html
  <section>
    <div class="container">
      <p class="red">Erro 1 - Mensagem de erro</p>
      <p class="blue">Erro 1 - Mensagem de erro</p>
      <p class="orange">Erro 1 - Mensagem de erro</p>
      <p class="green">Erro 1 - Mensagem de erro</p>
    </div>
  </section>
  ```
-----------------------------------------------

### Formulary
![formulary](images/form.png)

```html
<section>
  <div class="container">
    <h1>Preencha seus dados</h1>
    <form action="">

      <label for="name">Name: </label>
      <input type="text" name="name" id="name" placeholder="your name">

      <label for="email">E-mail: </label>
      <input type="email" name="email" id="email" placeholder="your email">

      <label for="password">Password: </label>
      <input type="password" name="password" id="password" placeholder="your password">

      <label for="avatar">Choose a profile picture:</label>
      <input type="file" id="avatar" name="avatar" accept="image/png, image/jpeg">
      
      <label for="date">Date: </label>
      <input id="date" lang="por" type="date">

      <textarea name="textarea" id="textarea" cols="30" rows="8"></textarea>

      <button>Cadastrar</button><br>
    </form>
  </div>
</section>
```

-----------------------------------------------
### Select and Datalist
![Select and Datalis](images/select_datalist.png)

```html
  <section>
    <div class="container">
      <h1>Outros itens</h1>
      <form action="">
        <label for="carros">Escolha um carro</label>
        <select id="carros">
          <option value="volvo">Volvo</option>
          <option value="saab">Saab</option>
          <option value="opel">Opel</option>
          <option value="audi">Audi</option>
        </select>

        <label for="browser">Escolha um navegador</label>
        <input list="browsers" name="browser" id="browser">
        <datalist id="browsers">
          <option value="Edge">
          <option value="Firefox">
          <option value="Chrome">
          <option value="Opera">
          <option value="Safari">
          <option value="Safari2">
        </datalist>

        <button type="submit" class="blue">Cadastrar</button><br>
      </form>
    </div>
  </section>
```

-----------------------------------------------

### Summary
![Summary](images/summary.png)

```html
  <section>
    <div class="container">
      <h3>Example Summary</h3>

      <details>
        <summary>Lorem ipsum dolor</summary>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempora doloremque amet, saepe tenetur officia beatae neque aut ratione repellat eos id reiciendis blanditiis ut dignissimos tempore debitis temporibus totam hic!</p>
      </details>

      <details>
        <summary>Lorem amet consectetur</summary>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Voluptatum doloribus deserunt quia officiis officia explicabo vel omnis similique! Pariatur aspernatur nobis incidunt architecto amet aut optio dicta vitae ipsam consequuntur?</p>
      </details>

      <details>
        <summary>Lorem ipsum sit</summary>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Architecto nihil eveniet, vel soluta quidem temporibus unde repudiandae doloremque illo corrupti illum corporis quam nobis! Nulla debitis totam recusandae consequatur sunt!</p>
      </details>

    </div>
  </section>

```

-----------------------------------------------

### Video
![Video](images/video.png)

```html
  <section>
    <div class="container">
      <h3>Meu vídeo</h3>
      <video controls>
        <source src="videos/video.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>

      <p>Este vídeo foi baixado no Pixabay, para servir como exemplo para esse demonstrativo. Segue o link <a href="https://pixabay.com/videos/rainy-rain-night-summer-colorful-5278/">https://pixabay.com/videos/rainy-rain-night-summer-colorful-5278/</a></p>
    </div>
  </section>

```
-----------------------------------------------

### Image
![Image](images/imagetag.png)

```html
  <section>
    <div class="container">
      <h3>Uma imagem qualquer</h3>
      <figure>
        <img src="images/image.jpg" alt="Pescador ao lado de torres de transmissão de energia">
        <figcaption>Fig.1 - Pescador, Rio, Estação de energia. </figcaption>
      </figure>  
    </div>
  </section>
```
-----------------------------------------------

### Links
![Links](images/links.png)

```html
  <section>
    <div class="container">
      <a href="#">Link Example</a>
      <a href="#">Link Example</a>
      <a href="#">Link Example</a><br>
    </div>
  </section>
```

-----------------------------------------------

### Lists
![Lists](images/listas.png)
```html
<section>
  <div class="container">
    <h3>Lista de itens</h3>
    <ul>
      <li>Item List example</li>
      <li>Item List example</li>
      <li>Item List example</li>
      <li>Item List example</li>
    </ul><br>
  </div>
</section>
```

-----------------------------------------------

### Strong and paragraph
![Strong and paragraph](images/destaque.png)
```html
<section>
  <div class="container">
    <h3>Respostas</h1>
    <p><strong>Resposta: </strong> Isso é uma resposta qualquer<br></p>
  </div>
</section>
```

-----------------------------------------------

### Buttons with links
![Buttons with links](images/buttons.png)
```html
<section>
  <div class="container">
    <button class="red"><a href="#">Botão red</a></button>
    <button class="green"><a href="#">Botão green</a></button>
    <button class="blue"><a href="#">Botão blue</a></button>
    <button class="orange"><a href="#">Botão orange</a></button>
  </div>
</section>
  ```

-----------------------------------------------

### Simple table
![Simple table](images/table2.png)
```html
<section>
  <div class="container">

    <h1>Painel administrador</h1>
    <table>
      <tr>
        <th>id</th>
        <th>name</th>
        <th>Ações</th>
      </tr>

      <tr>
        <td>2</td>
        <td>lisa@google.com</td>
        <td>
          <button class="blue">View</button>
          <a class="green">View 2</a>
        </td>
      </tr>

    </table>  
  </div>
</section>
```

-----------------------------------------------

### Large tables
![large table](images/table.png)

```html
<section>
  <div class="container-large">

    <h1>Painel administrador</h1>

    <table>
      <tr>
        <th>id</th>
        <th>foto</th>
        <th>name</th>
        <th>email</th>
        <th>Cargo</th>
        <th>Ações</th>
      </tr>

      <tr>
        <td>1</td>
        <td><img src="perfil.webp"></td>
        <td>Amy Winehouse</td>
        <td>amy@winehouse.com</td>
        <td>admin</td>
        <td>
          <button class="blue">View</button>
          <button class="green">View 2</button>
          <a class="orange">Edit</a>
          <a class="red" >Delete</a>
        </td>
      </tr>

      <tr>
        <td>2</td>
        <td><img src="perfil.webp"></td>
        <td>Lisa</td>
        <td>lisa@google.com</td>
        <td>user</td>
        <td>
          <button class="blue">View</button>
          <button class="green">View 2</button>
          <button class="orange">Edit</button>
          <button class="red" >Delete</button>
        </td>
      </tr>
    </table>  
  </div>
</section>
```

-----------------------------------------------

### Footer

![Footer](images/footer.png)

```html
<footer>
<p>Copyright@yourName</p>
</footer>
```
