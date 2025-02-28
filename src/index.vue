<script>
import Header from './components/header.vue';
export default {
    components: {
        Header
    }
}
</script>

<template>
    <div class="flex flex-col items-center h-screen">
        <Header></Header>
        <!-- Head -->
        <div class="w-full h-80 flex flex-row justify-start">
            <div class="ml-32 mt-12 w-7/12">
                <h1 class="text-7xl leading-tight font-bold">Je m'appelle Ibrahim,<br>un étudiant en informatique<span class="text-gray-500"><br>basé en Belgique.</span></h1>
                <div class="text-justify font-medium">
                    <p class="">
                    </p>
                </div>
            </div>
        </div>
    </div>
</template>