# Formulario
 
<form class="form-horizontal">
<fieldset>

<!-- Form Name -->
<legend>Cadastro</legend>

<!-- Text input-->
<div class="form-group">
  <label class="col-md-4 control-label" for="Nome">Nome</label>  
  <div class="col-md-5">
  <input id="Nome" name="Nome" type="text" placeholder="" class="form-control input-md" required="">
    
  </div>
</div>

<!-- Search input-->
<div class="form-group">
  <label class="col-md-4 control-label" for="searchinput">Telefone</label>
  <div class="col-md-4">
    <input id="searchinput" name="searchinput" type="search" placeholder="xx-xxxxx-xxxx" class="form-control input-md" required="">
    
  </div>
</div>

<!-- Text input-->
<div class="form-group">
  <label class="col-md-4 control-label" for="email">e-mail</label>  
  <div class="col-md-5">
  <input id="email" name="email" type="text" placeholder="xxxx@xxxxxx.xxx" class="form-control input-md" required="">
    
  </div>
</div>

<!-- Search input-->
<div class="form-group">
  <label class="col-md-4 control-label" for="searchinput">Data de nascimento</label>
  <div class="col-md-2">
    <input id="searchinput" name="searchinput" type="search" placeholder="__/__/____" class="form-control input-md">
    
  </div>
</div>

<!-- Select Basic -->
<div class="form-group">
  <label class="col-md-4 control-label" for="selectbasic">Escolaridade</label>
  <div class="col-md-5">
    <select id="selectbasic" name="selectbasic" class="form-control">
      <option value="1">Ensino Fundamental Incompleto</option>
      <option value="2">Ensino Fundamental Completo</option>
      <option value="3">Ensino Médio Incompleto</option>
      <option value="4">Ensino Médio Completo</option>
      <option value="5">Graduação Incompleta</option>
      <option value="6">Graduação Completa</option>
    </select>
  </div>
</div>

<!-- Textarea -->
<div class="form-group">
  <label class="col-md-4 control-label" for="textarea">Descrição</label>
  <div class="col-md-4">                     
    <textarea class="form-control" id="textarea" name="textarea"></textarea>
  </div>
</div>

<!-- File Button --> 
<div class="form-group">
  <label class="col-md-4 control-label" for="filebutton">Anexar Documentos</label>
  <div class="col-md-4">
    <input id="filebutton" name="filebutton" class="input-file" type="file">
  </div>
</div>

<!-- Button -->
<div class="form-group">
  <label class="col-md-4 control-label" for="singlebutton"></label>
  <div class="col-md-4">
    <button id="singlebutton" name="singlebutton" class="btn btn-primary">Enviar</button>
  </div>
</div>

</fieldset>
</form>
