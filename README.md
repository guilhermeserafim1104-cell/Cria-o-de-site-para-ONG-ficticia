# Cria-o-de-site-para-ONG-ficticia
# Nesse projeto estou criando uma pagina web em html para a divulgação de uma ONG imaginária, utilizando formulários e inputs para a ferramenta de cadastro, links para alternar entre as páginas e imagens para melhor imersão visual.

# Començando com a página inicial do nosso site, onde as pessoas poderam se informar a respeito da nossa ONG ficticia

<!--Começando com a estrutura básica em HTML-->
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE-edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SAF</title>
</head>
<body>
    <hearder>
        <h1>Bem-vindo à SAF</h1>
        <button><a href="index.html">Pagina Inicial</a></button>   <button><a href="projetos.html">Projetos</a></button>   <button><a href="cadastro.html">Cadastro</a></button>
        <h2><u>Nosso objetivo</u></h2>
        <hr>
        <p>Em agosto de 2024 foram registradas quase 300.000 famílias em situação de rua, mostrando um crescimento médio de 150% desde 2018, que estimou 116.000 pessoas.</p>
        <p>A<abbr title="Suporte de Apoio as Famílias"> SAF</abbr> é uma ONG dedicada a ajudar famílias que se encontram nessa situação.</p>
        <hr>
        <img src="pexels-pavel-danilyuk-6340686.jpg" width="300">
        
        <h2><u>Nossos contatos</u></h2>
        <address>
            <p>Endereço: Rua 7 de Março, 123-Rio de Janeiro, RJ</p>
            <p>Telefone: (99) 99999-9999</p>
            <p>Email: safcontato@gmail.com</p>
        </address>

    </header>
</body>
</html>


# Agora vamos mostrar a ferramentar de cadastro do nosso site, onde vamos poder ver como se tornar um voluntário e como fazer uma doação.

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SAF-Projetos</title>
</head>
<body>
    <header>
        <h1>Conheça nossos projetos</h1>
        
        <button><a href="index.html">Página inicial</a></button> <button><a href="projetos.html">Projetos</a></button> <button><a href="cadastro.html">Cadastro</a></button>
        
        <p>Nossa missão é prover à essas famílias tudo aquilo elas necessitam e tem direito.</p>
        <p>Ajude-nos a levar esperança a essas famílias, cadastre-se, torne-se um dos nossos voluntários e faça uma doação.</p>
        <p>Com R$1,00, você faz a diferença.</p>
        
        <br><hr>

        <img src="istockphoto-1625310710-612x612.jpg" width="565"> <img src="istockphoto-1479374222-612x612.jpg">

        <br><hr>

        <h2><u>Informações para doação</u></h2>
        <p>Chave pix(tel): (99) 99999-9999</p>
    </header>
</body>
</html>

# E, por fim, vamos criar uma ferramenta de cadastro, onde as pessoas poderão se voluntariar.

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SAF-Cadastro</title>
</head>
<body>
    <main>
        <header>
            <button><a href="index.html">Página inicial</a></button>  <button><a href="projetos.html">Projetos</a></button>  <button><a href="cadastro.html">Cadastro</a></button>
        </header>
            <br><br>
        <section>
            <h2>Formaulário</h2>
            <form>
                <legend> Nome Completo:</legend>
                <label for="nome"></label>
                <input type="text" id="nome" required>

                <br><br>
                
                <legend> CPF</legend>
                <label for="cpf"></label>
                <input type="text" pattern="\d{3}\.\d{3}\.\d{3}\-\d{2}\" maxlength="14" id="cpf" required>
                
                <br><br>
                
                <legend> Telefone:</legend>
                <label for="telefone"></label>
                <input type="tel" id="telefone" required>
                
                <br><br>
                
                <legend> Data de Nascimento:</legend>
                <label for="idade"></label>
                <input type="date" id="idade" required>
                
                <br><br>
                
                <legend> Endereço</legend>
                <label for="endereço"></label>
                <input type="text" id="endereço" required>
                
                <br><br>
                
                <legend> CEP</legend>
                <label for="cep"></label>
                <input type="text" id="cep" required>
                
                <br><br>
                
                <legend> Cidade:</legend>
                <label for="cidade"></label>
                <input type="text" id="cidade" required>
                
                <br><br>
                
                <legend> Endereço:</legend>
                <label for="endereço"></label>
                <input type="text" id="endereço" required>
                
                <br><br>
                
                <legend> Email:</legend>
                <label for="email"></label>
                <input typr="email" id="email" required>
                
                <br><br>
                
                <legend> Senha:</legend>
                <label for="senha"></label>
                <input typr="password" id="senha" required>
                
                <br><br>
                
                <input type="submit" value="Enviar cadastro">
            </form>
        </section>
    </main>
</body>
</html>
