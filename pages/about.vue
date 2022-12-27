<template>
    <div>
        <h2>About</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Reprehenderit magni neque repudiandae, provident ipsa vel nesciunt, nihil, dolores voluptates id nisi ea. Reiciendis consequatur et porro, pariatur minus excepturi maiores.</p><p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nihil, praesentium fugit repudiandae, facere eos illum vel ducimus iusto architecto, aut amet quaerat mollitia cumque et magni earum expedita accusantium numquam!</p>
        <p>api response:</p>
        <div>{{ data }}</div>
    </div>
</template>

<script setup>
    // const { data } = await useFetch('/api/ninja?name=mario')
    // const { data } = await useFetch('/api/ninja?name=mario', {
    //   method: 'post',
    //   body: {age: 30}
    // })

    const { data } = await useFetch('/api/api')
</script>

<style scoped>
    h2 {
        margin-bottom: 20px;
        font-size: 36px;
    }
    p {
        margin: 20px;
    }
</style>