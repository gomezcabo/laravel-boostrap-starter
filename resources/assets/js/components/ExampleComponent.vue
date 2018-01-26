<template>
    <div>
        {{ message }}
    </div>
</template>

<script>
    export default {
        data: function() {
            return {
                message: 'Hello Vue!'
            }
        },

        mounted: function() {
            console.log('Component mounted.')
        }
    }
</script>
