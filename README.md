# barbearia-2
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <title>Contato - Barbearia Alura</title>

        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <header>
            <div class="caixa">
                <h1><img src="logo.png"></h1>

                <nav>
                    <ul>
                        <li><a href="index.html">Home</a></li>
                        <li><a href="produtos.html">Produtos</a></li>
                        <li><a href="contato.html">Contato</a></li>
                    </ul>
                </nav>
            </div>
        </header>

        <footer>
            <img src="logo-branco.png">
            <p class="copyright">&copy; Copyright Barbearia Alura - 2019</p>
        </footer>
    </body>
</html>
<main>
    <form>
        <label for="nomesobrenome">Nome e sobrenome</label>
        <input type="text" id="nomesobrenome">

        <label for="email">Email</label>
        <input type="text" id="email">

        <label for="telefone">Telefone</label>
        <input type="text" id="telefone">

        <input type="submit" value="Enviar formulário">
    </form>
</main>
main {
    width: 940px;
    margin: 0 auto;
}

form {
    margin: 40px 0;
}

form label {
    display:block;
    font-size: 20px;
    margin: 0 0 10px;
}

form input {
    display: block;
    margin: 0 0 20px;
    padding: 10px 25px;
    width: 50%;
}
<main>
<form>
<label> Grifinória </label>
<input type="radio" value="grifinoria" id="radio-grifinoria">
<label> Sonserina </label>
<input type="radio" value="sonserina" id="radio-sonserina">
<label> Lufa-Lufa </label>
<input type="radio" value="lufa-lufa" id="radio-lufa-lufa">
<label> Corvinal </label>
<input type="radio" value="corvinal" id="radio-corvinal">
<input type="submit" value="Enviar formulário" />
</form>
</main>
<p class="paragrafo">

p {
    color: blue;
}

p.paragrafo {
    color: red;
}

.paragrafo {
    color: purple;
}
<label for="mensagem">Mensagem</label>
<textarea cols="70" rows="10" id="mensagem" class="input-padrao"></textarea>

<div>
    <p>Qual horário prefere ser atendido?</p>
    <select>
        <option>Manhã</option>
        <option>Tarde</option>
        <option>Noite</option>
    </select>
</div>
<label class="checkbox">
    <input type="checkbox">
    Gostaria de receber nossas novidades por email?
</label>
form label {form input {
    display: block;
    margin: 0 0 20px;
    padding: 10px 25px;
    width: 50%;
}
.input-padrao {
    display: block;
    margin: 0 0 20px;
    padding: 10px 25px;
    width: 50%;
}
.checkbox {
    margin: 20px 0;
}

    display:block;
    font-size: 20px;
    margin: 0 0 10px;
}
form label, form p {
    display:block;
    font-size: 20px;
    margin: 0 0 10px;
}
