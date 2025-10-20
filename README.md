# relatorio-de-trabalho-usando-HTML-5
Descrição detalhada da primeira experiência programando com a HTML

Nesse terceiro módulo de desenvolvimento de sistemas, estarei codificando em linguagem HTML, Com as seguintes orientações:

"Desenvolver uma plataforma web completa e profissional que permita a ONGs gerenciar suas atividades, divulgar projetos, captar recursos e engajar voluntários, aplicando, de forma integrada, todos os conceitos estudados nas quatro unidades da disciplina."

DE ínicio tive que rever várias vezes o conteúdo até conseguir entender, e obtive sucesso.
Criei então o código

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HELP ONGs</title>
    <meta name="description" content="está precisando de organizAção? Achou o lugar certo?">
    <link rel="stylesheet" href="assets/css/style.css">
</head>
<body>

    <header class="site-header">
        <nav class="site-nav" aria-label="Página principal">
            <a href="/" class="logo">ONGs</a>
            <button class="nav-toggle" aria-expanded="false" aria-controls="main-menu">Menu</button>
            <ul class="nav-menu" id="main-menu">
                <li><a href="#projetos">Divulgue seu projeto</a></li>
                <li><a href="#voluntarios">Voluntários</a></li>
                <li><a href="#doacoes">Doações</a></li>
                <li><a href="#contato">Entre em contato</a></li>
            </ul>
        </nav>
    </header>

    <main id="main-content">
        <section class="hero-section" aria-label="Seção de destaque">
            <div class="hero-content">
                <p>Gerencie, divulgue e transforme o mundo com a sua ONG.</p>
                <a href="#" class="cta-button">Conheça nossos projetos</a>
            </div>
        </section>

        <section id="projetos" class="projects-section" aria-labelledby="projects-heading">
            <h2 id="projects-heading">Nossos projetos</h2>
            <div class="project-list">
                <article class="project-card">
                    <img src="assets/images/projeto-1.jpg" alt="projeto tchau frio!">
                    <h3>Projeto Tchau frio!</h3>
                    <p>Doe roupas de inverno para quem precisa!</p>
                    <a href="#" class="link-details">Ver detalhes</a>
                </article>
                <article class="project-card">
                  
                     </div>
                  
                    <img src="assets/images/projeto-2.jpg" alt="Projeto bucho cheio">
                    <h3>multirão para arrecadar alimentos</h3>
                    <p>doe um quilo de alimento e venha participar das doações.</p>
                    <a href="#" class="link-details">Ver detalhes</a>
                </article>
            </div>
        </section>

        <aside class="donation-form-container" aria-label="Formulário de doação">
            <h3>Faça sua doação</h3>
            <form action="#" method="post" class="donation-form">
                <label for="donation-amount">Valor:</label>
                <input type="number" id="donation-amount" name="donation-amount" placeholder="Ex: 50" required>

                <label for="donation-email">E-mail:</label>
                <input type="email" id="donation-email" name="donation-email" placeholder="seuemail@exemplo.com" required>

                <button type="submit">Doar agora</button>
            </form>
        </aside>
    </main>

    <footer class="site-footer">
        <p>&copy; 2025 HELP ONG. Todos os direitos reservados.</p>
        <p><a href="#">Política de Privacidade</a> | <a href="#">Termos de Uso</a></p>
    </footer>

    <script src="assets/js/main.js"></script>
     </body>
    </html>

Segue as imagens:

<img width="489" height="250" alt="image" src="https://github.com/user-attachments/assets/55893da3-d121-411a-930e-46e8a17886cd" />


esse é o menu principal do site

agora a pagina dos projetos:

<img width="389" height="333" alt="image" src="https://github.com/user-attachments/assets/7070bcc6-0f18-44bd-966b-1f1d87deaa8d" />

agora a página das doaçoes para as ongs:

<img width="581" height="143" alt="image" src="https://github.com/user-attachments/assets/0fe6bd7b-cc82-49a6-a1c9-f0b57dbcf148" />

Esse foi o resultado da primeira parte do site, o HTML.
