<template>
  <q-page class="q-pa-lg">
    <q-btn
      flat
      color="primary"
      icon="arrow_back"
      style="height: 32px; width: 32px"
    />

    <!-- <q-separator /> -->
    <div
      class="text-center"
      style="
        font-size: 36px;
        font-family: 'Calistoga'
        font-weight: 400;
      "
    >
      B7 <span class="text-primary">•</span> Burger
    </div>

  <div class="q-py-lg text-center">
    Use suas credenciais para realizar o login
  </div>

    <div class="q-gutter-md">
      <q-input outlined filled square label="Digite seu e-mail"></q-input>
      <q-input outlined filled square label="Digite sua senha">
        <template v-slot:append>
          <q-icon name="visibility_off" />
        </template>
      </q-input>
    </div>
    <div class="q-py-lg">
      <q-btn label="Entrar" color="primary" class="full-width" />
    </div>

    <div class="q-py-lg">
      <span>Esqueceu sua senha? <q-btn class="text-primary">Clique aqui</q-btn></span>
    </div>
<div class="q-py-lg">
    <q-separator />
</div>

    <q-btn outline label="Quero me cadastrar" color="primary" class="full-width" />
  </q-page>
</template>
<style>
@import url("https://fonts.googleapis.com/css2?family=Calistoga&display=swap");
</style>
