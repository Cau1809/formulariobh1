<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="style.css" rel="stylesheet">
    <title>Formulário</title>
<head>
    
<body>

    <div>
        <h1 id="titulo">FORMULÁRIO<h1>
        <p id="subtitulo"> Complete suas informações</p>
    </div>

    <form>
        <div class="campo">
            <label for="name">Nome Completo</label>
            <input type="text" name="sobrenome" id="sobrenome"> 
        </div>

        <div class="campo">
            <label for="CRP">CRP</label>
            <input type="text" name="CRP" id="CRP">
        </div>

        <div class="campo">
            <label for="CPF">CPF</label>
            <input type="text" name="CPF" id="CPF">
        </div>

        <div class="image-field">
            <input type="checkbox" name="permissao_imagem" value="yes">
            <label> Você autoriza o uso de imagem?</label>
            <input type="file" name="foto" class="input-arquivo">
        </div>
        
          
        <div>
            <input type="checkbox" name="permissao_imagem" value="yes"> 
            <label> Você permite que sua informações sejam publicadas no site?</label>
        <div>
            <input class="botao" type="submit" value="Enviar" required>
          </div>
        </form>

    </body>
</html>
