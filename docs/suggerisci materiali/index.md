---
title: Suggerisci materiali
excerpt: >-
  Da qui è possibile suggerire materiali o tutorial da pubblicare nel sito per la DaD
layout: docs
---

<div class="note">
  <strong>Nota:</strong> Sei un docente? o un alunno?? vuoi suggerire argomenti, tutorial o guide sulla didattica? sei nel posto giusto, clicca qui sotto e scrivici tutto!!<br>
  <strong>Compila il form qui sotto</strong>
</div>

### Suggerisci contenuti

Compila il form per inviare al Team Digitale un contenuto o un tutorial che ritieni possa essere utile alla comunità scolastica. Se veramente ineteressante sarà messo a disposizione di tutti

<form name="materiali" method="POST" data-netlify="true">
  <p>
    <label>Il tuo nome: <input type="text" name="name" /></label>   
  </p>
  <p>
    <label>La tua mail: <input type="email" name="email" /></label>
  </p>
  <p>
    <label>Tipo di materiale suggerito <select name="role[]" multiple>
      <option value="leader">Tutorial</option>
      <option value="follower">Link a risorsa</option>
      <option value="follower">Varie</option>
    </select></label>
  </p>
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <p> <label>Carica un file: </label><input type="file" id="myfile" name="myfile">
  <p>
    <button type="submit">Invia <i class="fa fa-share-square"></i></button>
  </p>
