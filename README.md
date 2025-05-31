<!DOCTYPE html> 
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Ficha de Anamnese - Micropigmentação de Barba</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 20px;
      background: #f4f4f4;
    }
    h1, h2 {
      text-align: center;
    }
    form {
      background: #fff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      max-width: 800px;
      margin: auto;
    }
    label {
      display: block;
      margin-top: 15px;
    }
    input, textarea {
      width: 100%;
      padding: 8px;
      margin-top: 5px;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
    .checkbox-group {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }
    .checkbox-group label {
      width: 48%;
    }
    .submit-btn {
      text-align: center;
      margin-top: 20px;
    }
    button {
      padding: 10px 20px;
      background-color: #0066cc;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background-color: #004999;
    }
  </style>
</head>
<body>

  <h1>Ficha de Anamnese</h1>

  <form action="https://formsubmit.co/barbearianunes132@gmail.com" method="POST">
    <!-- Campos ocultos do FormSubmit -->
    <input type="hidden" name="_next" value="https://barberianunes.github.io/barbearianunes/obrigado.html">
    <input type="hidden" name="_captcha" value="false">

    <label>Nome: <input type="text" name="nome" required></label>
    <label>Data de nascimento: <input type="date" name="data_nascimento"></label>
    <label>RG: <input type="text" name="rg"></label>
    <label>CPF: <input type="text" name="cpf"></label>
    <label>Profissão: <input type="text" name="profissao"></label>
    <label>Endereço: <input type="text" name="endereco"></label>
    <label>Bairro: <input type="text" name="bairro"></label>
    <label>Cidade: <input type="text" name="cidade"></label>
    <label>UF: <input type="text" name="uf"></label>
    <label>Telefone: <input type="tel" name="telefone"></label>

    <h2>Condições de Saúde</h2>
    <div class="checkbox-group">
      <label><input type="checkbox" name="herpes"> Herpes</label>
      <label><input type="checkbox" name="gravidez"> Está grávida</label>
      <label><input type="checkbox" name="amamentando"> Amamentando</label>
      <label><input type="checkbox" name="alergia"> Alergia a cosmético</label>
      <label><input type="checkbox" name="anemia"> Anemia</label>
      <label><input type="checkbox" name="diabetes"> Diabetes</label>
      <label><input type="checkbox" name="hipertensao"> Hipertensão</label>
      <label><input type="checkbox" name="epilepsia"> Epilepsia</label>
      <label><input type="checkbox" name="fumante"> Fumante</label>
      <label><input type="checkbox" name="hepatite"> Hepatite</label>
      <label><input type="checkbox" name="acne"> Acne avançada</label>
      <label><input type="checkbox" name="depressao"> Depressão</label>
    </div>

    <label>Está realizando algum tratamento médico? Quais?<br>
      <textarea name="tratamento_medico" rows="3"></textarea>
    </label>

    <label>Fez procedimentos estéticos recentemente?<br>
      <textarea name="procedimentos" rows="3"></textarea>
    </label>

    <label>Faz uso contínuo de medicamentos? Quais?<br>
      <textarea name="medicamentos" rows="2"></textarea>
    </label>

    <h2>Consentimento</h2>
    <label>
      <input type="checkbox" name="consentimento" required> 
      Declaro que li e concordo com todos os termos de consentimento e estou ciente dos riscos e cuidados do procedimento de micropigmentação.
    </label>

    <label>Assinatura (digite seu nome completo): <input type="text" name="assinatura" required></label>
    <label>Data: <input type="date" name="data_assinatura" required></label>

    <div class="submit-btn">
      <button type="submit">Enviar</button>
    </div>
  </form>

</body>
</html>
