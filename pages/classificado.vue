<template>
    <section class="section">
        <h1 class="title">Marketplace - Novo Classificado</h1>

        <b-field label="Nome do Produto ">
            <b-input></b-input>
        </b-field>

        <b-field label="Valor ">
            <b-input value="R$"></b-input>
        </b-field>

        <b-field label="Descricao" :label-position="labelPosition">
            <b-input maxlength="200" type="textarea"></b-input>
        </b-field>

        <div class="columns">
        <div class="column">
            <b-field label="Data de Publicacao" :label-position="labelPosition">
            <b-datepicker
                placeholder="Selecione a data..."
                icon="calendar-today"
                trap-focus>
            </b-datepicker>
        </b-field>
        </div>
        <div class="column">
            <b-field label="Data de Validade" :label-position="labelPosition">
            <b-datepicker
                placeholder="Selecione a data..."
                icon="calendar-today"
                trap-focus>
            </b-datepicker>
        </b-field>
            
        </div>

        </div>

        <div class="buttons">
 
  <button class="button is-success">Salvar</button>
  <button class="button is-danger">Cancelar</button>
</div>



    </section>
</template>
  