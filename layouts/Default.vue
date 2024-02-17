<template>
    <div id="body-layout">
        <Header />
        <div class="page-content">
            <nuxt-page />
        </div>
        <Footer />
    </div>
</template>

<script setup>
import Header from "~/components/Header.vue";
import Footer from "~/components/Footer.vue";
</script>
