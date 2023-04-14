<template>
    <div class="container">
        <div>4444444444444</div>
        <div>Name: {{ name }}</div>
        <button @click="changeName">Click</button>
        <ExampleComponent></ExampleComponent>
    </div>
</template>

<script>
import ExampleComponent from './ExampleComponent.vue';
export default {
    components: {
        ExampleComponent
    },

    data() {
        return {
            name: 'Jan',
        }
    },

    methods: {
        changeName() {
            this.name='Nick'
        }
    }
}
</script>

