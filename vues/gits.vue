<template>
    <h3>Git Repo List - Building</h3>
    <div class="container">
        <hr>
        <ul>
            <li v-for="todo in todos" v-bind:title="todo">{{todo.key}}</li>
        </ul>
    </div>
</template>

<script>
    'use strict';
    export default {
        name: "gits",
        data() {
            return {
                appName: 'my-gits',
                todos: {
                    "id1": {
                        "name": "abc1",
                        "time": 2016
                    },
                    "id2": {
                        "name": "abc2",
                        "time": 2016
                    }
                }
            }
        }
        methods: {}
    }

</script>

<style>


</style>
