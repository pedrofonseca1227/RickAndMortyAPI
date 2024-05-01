<template>
  <div class="accordion" id="accordionExample">
   <div class="accordion-item">
     <h2 class="accordion-header">
       <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
         Aluno
       </button>
     </h2>
     <div id="collapseOne" class="accordion-collapse collapse show" data-bs-parent="#accordionExample">
       <div class="accordion-body">
         <p><b>Nome: </b>Pedro Henrique Fonseca Dal Evedove</p> 
       </div>
       <div class="accordion-body">
        <p><b>RA: </b>1968106</p>        
      </div> 
     </div>
   </div>
   <div class="accordion-item">
     <h2 class="accordion-header">
       <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
         Curso
       </button>
     </h2>
     <div id="collapseTwo" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
       <div class="accordion-body">
         <h4>Análise de Desenvolvimento de Sistemas | 3º Termo</h4> 
       </div>
     </div>
   </div>
   <div class="accordion-item">
     <h2 class="accordion-header">
       <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
         Universidade
       </button>
     </h2>
     <div id="collapseThree" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
       <div class="accordion-body">
         <h4>Universidade de Marília | Unimar</h4> 
       </div>
     </div>
   </div>
 </div>
 </template>