<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Hello Vue 3 + Vite" />
</template>

<script setup>
import HelloWorld from './components/HelloWorld.vue'

// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/script-setup-2/active-rfcs/0000-script-setup.md
</script>

<style>
.card {
    width: 350px;
    margin: 10px;
    padding: 15px;
    border: 3px solid black;
}


.card img {
    width: 100%;
}

.card h2 {
  text-align: center;
  
}

.card p {
  text-align: center;
}

.details-button {
   
    text-decoration: none;
    background-color: #007BFF;
    color: #fff;
    padding: 8px 16px;
    border-radius: 4px;
}


#duplicateButton:hover,
#duplicateButton:focus {
    background-color: #007BFF;
    color: black;
    cursor: pointer;
}

.card.toggled-color {
    background-color: grey;
}


.details-toggle {
    display: none;
}

.details-label {
    cursor: pointer;
    background-color: #007BFF;
    color: #fff;
    padding: 8px 16px;
    border-radius: 4px;
}


.description p {
    display: none;
}

.details-toggle:checked + .description p {
    display: block;
}

@media (max-width: 800px) and (min-width: 500px){
    .details-button {
        display: inline-block;
    }
}


@media (max-width: 500px) {
    .card {
        max-width: 300px;
    }
}

@media screen and (max-width: 800px) {
    .details-button {
        display: none;
    }
}


</style>
