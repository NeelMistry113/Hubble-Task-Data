<template>
    <dropContainer>
        <drop-comp />
    </dropContainer>
</template>

<script>
import DropComp from './DropComp.vue';
    export default {
        name: 'Dropdown',
        components: {
            DropComp
        },
    }
</script>

<style scoped>
.dropContainer{
    position: relative;
    background: #fff;
}
</style>