<template>
    <div>
        <nav class="navbar navbar-expand-lg navbar-light flex-column">

            <a class="navbar-brand" href="/">
                <img src="../assets/company-logo_60x60.png">
                Klicken Creative
            </a>

            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>

            <div class="flex-row">
                <div class="collapse navbar-collapse" id="navbarNav">
                    <div class="navbar-nav mr-auto navbar-center">
                        <router-link class="nav-item nav-link" to="/">Home</router-link>
                    </div>
                </div>

                <div class="collapse navbar-collapse" id="navbarNav">
                    <div class="navbar-nav mr-auto navbar-center">
                        <router-link class="nav-item nav-link" to="/">Gallery</router-link>
                    </div>
                </div>
            </div>

        </nav>

        <router-view></router-view>
    </div>
</template>

<style>
    .navbar {
        font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        font-size: 200%;
    }
</style>