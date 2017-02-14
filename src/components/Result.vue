<template>
    <p>Counter is: {{ counter }}</p>
</template>

<script>
    export default {
        computed: {
            counter() {
<<<<<<< HEAD
                return this.$store.getters.doubleCounter;
=======
                return this.$store.state.counter;
>>>>>>> parent of 156c3ed... lecture256 finished
            }
        }
    }
</script>