<script setup>
    import {ref} from 'vue'
    const title = '"First, solve the problem. Then, write the code."'
    const authorName  = 'Jhone Jonhson'
    const anotherLink = 'Another'
</script>

<template>
    <main>
        <div class="card">
            <h1>{{title}}</h1>
            <span>{{authorName}}</span>
            <a href="/">{{anotherLink}}</a>
        </div>
    </main>
</template>

<style scoped>
    .card {
        display: flex;
        flex-direction: column;
        padding: 2rem 2.5rem;
        border-radius: 0 10px;
        background-color: rgb(189, 201, 218);
    }
    h1 {
        font-size: 1.8rem;
        max-width: 14rem;
        font-style: italic;
        text-align: left;
        color: #000;
        margin: 0 0 0.4rem;
    }
    span {
        text-align: right;
        margin-bottom: 3rem;
        color: rgb(34, 109, 153);
    }
    a {
        width: 6rem;
        padding: 0.6rem;
        color: #fff;
        text-decoration: none;
        font-weight: 600;
        border-radius: 0 4px;
        margin: 0 auto;
        background-color: rgb(34, 109, 153);
    }
</style>