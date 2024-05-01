<script setup> 
    const personagem = defineProps(["name", "url", "image", "status","species", "gender", "location", "episode"])
</script>

<template>
    <div class="col-md-3 d-flex">
        <div class="card mb-3 p-2">
            <img :src="personagem.image" class="card-img-top" height="300" alt="..."> 
            <div class="card-body">
                <p class="card-title text-center"><b>Nome:</b> {{ personagem.name }}</p>
                <p class="card-title text-center"><b>Status:</b> {{ personagem.status }}</p>
                <p class="card-title text-center"><b>Espécies:</b> {{ personagem.species }}</p>
                <p class="card-title text-center"><b>Gênero:</b> {{ personagem.gender }}</p>
                <p class="card-title text-center"><b>Localização:</b> {{ personagem.location.name }}</p>
                <p class="card-title text-center"><b>Episódios:</b> {{ personagem.episode.length }}</p>
            </div>
        </div>
    </div>
</template>

