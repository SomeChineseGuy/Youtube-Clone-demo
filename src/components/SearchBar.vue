<template>
    <div>
        <input v-on:input="onInput"/>
    </div>
</template>

<script>
export default {
    name: 'Search-Bar',

    methods: {
        onInput: function(event) {
            window.console.log(event.target.value)
        }
    }
};
</script>

<style>

</style>