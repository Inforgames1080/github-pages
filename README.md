<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Curso de Programação</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            background-color: #f4f4f9;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 2rem 0;
            text-align: center;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <!-- Badge de HTML5 -->
  <img alt="html5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">

  <!-- Badge de JavaScript -->
  <img alt="js" src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E">

  <!-- Badge de Python -->
  <img alt="python" src="https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white">

  <!-- Badge de CSS -->
  <img alt="CSS" src="https://img.shields.io/badge/CSS-239120?style=for-the-badge&logo=css3&logoColor=white">

  <!-- Badge de Bootstrap -->
  <img alt="Bootstrap" src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white">

  <!-- Badge de Django -->
  <img alt="Django" src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white">


        <h1>Bem-vindo ao Curso de Programação</h1>
        <p>Aprenda as habilidades necessárias para criar websites, aplicativos e muito mais!</p>
    </header>

    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Curso de Programação</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link active" href="#sobre">Sobre</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#modulos">Módulos</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contato">Contato</a>
                        <li class="nav-item">
                        <a class="nav-link" href="#contato">Dicas de livros</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Main Content -->
    <main class="container my-4">
        <section id="sobre" class="mb-4">
            <h2>Sobre o Curso</h2>
            <p>Este curso é projetado para iniciantes e desenvolvedores que desejam aprimorar suas habilidades. Comece do básico e avance para tópicos mais avançados, como JavaScript, Python e desenvolvimento de aplicativos.</p>
        </section>

        <section id="modulos" class="mb-4">
            <h2>Módulos do Curso</h2>
            <ul class="list-group">
                <li class="list-group-item">Introdução à Programação</li>
                <li class="list-group-item">HTML e CSS Básico</li>
                <li class="list-group-item">JavaScript para Iniciantes</li>
                <li class="list-group-item">Python e Desenvolvimento Backend</li>
                <li class="list-group-item">Python do básico ao avançado <a href="file:///home/anderson/%C3%81rea%20de%20trabalho/projeto%20site%20django/Explica%C3%A7%C3%A3o%20passo%20a%20passo.html">aqui</a> </li>
                <li class="list-group-item">Projetos Práticos</li>

            </ul>
        </section>

        <section id="contato">
            <h2>Contato</h2>
            <p>Se tiver dúvidas, entre em contato conosco pelo e-mail <a href="mailto:curso@programacao.com">curso@programacao.com</a>.</p>
            <button id="botao-contato" class="btn btn-primary">Clique para saber mais</button>
        </section>
    </main>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Curso de Programação. Todos os direitos reservados.</p>
    </footer>

    <!-- Bootstrap JS and Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
    <!-- Custom JavaScript -->
    <script>
        document.getElementById("botao-contato").addEventListener("click", function() {
            alert("Obrigado por entrar em c
<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# GitHub Pages

_Create a site or blog from your GitHub repositories with GitHub Pages._

</header>

<!--
  <<< Author notes: Course start >>>
  Include start button, a note about Actions minutes,
  and tell the learner why they should take the course.
-->

## Welcome

With GitHub Pages, you can host project blogs, documentation, resumes, portfolios, or any other static content you'd like. Your GitHub repository can easily become its own website. In this course, we'll show you how to set up your own site or blog using GitHub Pages.

- **Who is this for**: Beginners, students, project maintainers, small businesses.
- **What you'll learn**: How to build a GitHub Pages site.
- **What you'll build**: We'll build a simple GitHub Pages site with a blog. We'll use [Jekyll](https://jekyllrb.com), a static site generator.
- **Prerequisites**: If you need to learn about branches, commits, and pull requests, take [Introduction to GitHub](https://github.com/skills/introduction-to-github) first.
- **How long**: This course takes less than one hour to complete.

In this course, you will:

1. Enable GitHub Pages
2. Configure your site
3. Customize your home page
4. Create a blog post
5. Merge your pull request

### How to start this course

<!-- For start course, run in JavaScript:
'https://github.com/new?' + new URLSearchParams({
  template_owner: 'skills',
  template_name: 'github-pages',
  owner: '@me',
  name: 'skills-github-pages',
  description: 'My clone repository',
  visibility: 'public',
}).toString()
-->

[![start-course](https://user-images.githubusercontent.com/1221423/235727646-4a590299-ffe5-480d-8cd5-8194ea184546.svg)](https://github.com/new?template_owner=skills&template_name=github-pages&owner=%40me&name=skills-github-pages&description=My+clone+repository&visibility=public)

1. Right-click **Start course** and open the link in a new tab.
2. In the new tab, most of the prompts will automatically fill in for you.
   - For owner, choose your personal account or an organization to host the repository.
   - We recommend creating a public repository, as private repositories will [use Actions minutes](https://docs.github.com/en/billing/managing-billing-for-github-actions/about-billing-for-github-actions).
   - Scroll down and click the **Create repository** button at the bottom of the form.
3. After your new repository is created, wait about 20 seconds, then refresh the page. Follow the step-by-step instructions in the new repository's README.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/github-pages) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
