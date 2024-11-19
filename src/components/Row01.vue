<script setup>
import Home from '@/components/Home.vue'
import Loading from '@/components/Loading.vue'
</script>

<template>
    <div class="container text-center mt-2">
        <div class="row">
            <div class="col bg-primary-subtle m-2">
                1 of 3
            </div>
            <div class="col bg-success-subtle p-2">
                <Loading />
            </div>
            <div class="col bg-primary-subtle m-2">
                3 of 3
            </div>
        </div>
    </div>
</template>

<style></style>