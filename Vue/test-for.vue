<template>
    <div>
        <a v-for="item in obj" :key="item"></a>
        <ul>
            <li v-for="item in obj" :key="item"></li>
        </ul>
    </div>
</template>

<script>
export default {

}
</script>

<style>

</style>