<template>
    <div class="home">
        <img alt="Vue logo" src="../assets/logo.png">
        <HelloWorld msg="Wellcome to Your vue.js App"/>

    </div>
</template>

<script>
    import HelloWorld from '../components/HelloWorld.vue'

    export default {
        name: 'home',
        components: {
            HelloWorld
        },
        props: {
            arg: String
        },
        data(){
            return{
                message: 'message',
                a: 'xxxx'
            }
        },
        methods: {
            getData(){

            },
        },
        created(){

        },
    }
</script>