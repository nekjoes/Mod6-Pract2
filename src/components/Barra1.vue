<template>
        <nav id="Bar1" class="navbar navbar-expand-lg " >
        <div class="container-fluid">
            <a class="navbar-brand" href="#" >TituloPagina</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false"
                aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link" aria-current="page" href="#">menu1</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">menu2</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</template>

<script> 
export default {
  name: 'Barra',
  
}

</script>

<style scoped>
#Bar1{
    background-color: lightblue;
}
</style>