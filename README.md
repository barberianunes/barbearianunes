<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Ficha de Anamnese - Micropigmentação de Barba</title>
  <style>
    body { font-family: Arial, sans-serif; padding: 20px; background-color: #f7f7f7; }
    form { background: white; padding: 20px; border-radius: 8px; }
    h1 { color: #444; }
    label { display: block; margin-top: 10px; font-weight: bold; }
    input, textarea, select { width: 100%; padding: 8px; margin-top: 5px; }
    .group { margin-top: 20px; }
    .checkbox-group { display: flex; flex-wrap: wrap; gap: 10px; }
    .checkbox-group label { font-weight: normal; }
    button { margin-top: 20px; padding: 10px 20px; background: #333; color: white; border: none; border-radius: 5px; cursor: pointer; }
  </style>
</head>
<body>
  <h1>Ficha Cadastral de Anamnese - Micropigmentação de Barba</h1>
  <form action="https://formsubmit.co/barbearianunes132@gmail.com" method="POST">
    
    <label>Nome:</label>
    <input type="text" name="Nome" required>

    <label>Data de nascimento:</label>
    <input type="date" name="Data de nascimento">

    <label>RG:</label>
    <input type="text" name="RG">

    <label>CPF:</label>
    <input type="text" name="CPF">

    <label>Profissão:</label>
    <input type="text" name="Profissão">

    <label>Endereço:</label>
    <input type="text" name="Endereço">

    <label>Bairro:</label>
    <input type="text" name="Bairro">

    <label>Cidade:</label>
    <input type="text" name="Cidade">

    <label>UF:</label>
    <input type="text" name="UF">

    <label>Telefone:</label>
    <input type="tel" name="Telefone">

    <div class="group">
      <h3>Anamnese</h3>
      <p>Selecione se você tem ou já teve os seguintes:</p>
      <div class="checkbox-group">
        <label><input type="checkbox" name="Herpes"> Herpes</label>
        <label><input type="checkbox" name="Grávida"> Está grávida</label>
        <label><input type="checkbox" name="Amamentando"> Amamentando</label>
        <label><input type="checkbox" name="Alergia"> Alergia esmalte/cosmético</label>
        <label><input type="checkbox" name="Cirurgia oftalmológica"> Cirurgia oftalmológica</label>
        <label><input type="checkbox" name="Glaucoma"> Glaucoma</label>
        <!-- Continue com os demais campos aqui... -->
        <label><input type="checkbox" name="Diabetes"> Diabetes</label>
        <label><input type="checkbox" name="Hipertensão"> Hipertensão</label>
        <label><input type="checkbox" name="Epilepsia"> Epilepsia</label>
        <label><input type="checkbox" name="Doença cardíaca"> Doença cardíaca</label>
        <label><input type="checkbox" name="Hepatite"> Hepatite</label>
        <label><input type="checkbox" name="HIV"> HIV+</label>
        <label><input type="checkbox" name="Depressão"> Depressão</label>
        <!-- Adicione todos os demais conforme seu formulário -->
      </div>
    </div>

    <label>Relato médico ou tratamento atual:</label>
    <textarea name="Relato médico" rows="3"></textarea>

    <label>Usa produto injetável ou tópico na face recentemente?</label>
    <input type="text" name="Produtos injetáveis">

    <label>Cirurgia facial ou geral no último ano?</label>
    <input type="text" name="Cirurgia facial">

    <label>Medicamento contínuo? Informe:</label>
    <input type="text" name="Medicamentos contínuos">

    <label>Exame de ressonância nos próximos dias?</label>
    <input type="text" name="Ressonância">

    <label>Você autoriza o uso de imagem conforme descrito?</label>
    <select name="Autorização de imagem">
      <option value="Sim">Sim</option>
      <option value="Não">Não</option>
    </select>

    <label>Declarações finais e consentimento:</label>
    <textarea name="Consentimento" rows="6">Declaro estar ciente e de acordo com todos os termos apresentados.</textarea>

    <label>Local e Data:</label>
    <input type="text" name="Local e data">

    <label>Assinatura (escreva seu nome completo):</label>
    <input type="text" name="Assinatura">

    <!-- Configurações do formsubmit -->
    <input type="hidden" name="_captcha" value="false">
    <input type="hidden" name="_next" value="https://SEUSITE.com/obrigado.html">

    <button type="submit">Enviar formulário</button>
  </form>
</body>
</html>
