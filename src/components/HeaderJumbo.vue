<script>

</script>

<template>
    <section class="ivy_jumbotron">
        <div class="ivy_hero">
            <img src="../assets/jumbo.png" alt="Boolzap image">
        </div>
        <div class="ivy_title_box">
            <h1 class="ivy_jumbo_title">
                Hi, I'm Alex
            </h1>
            <h2 class="ivy_jumbo_subtitle">
                Founder of Boolzap
            </h2>
        </div>
    </section>
</template>

<style scoped>
    .ivy_jumbotron{
        position: relative;
        display: flex;
        padding: 3rem 0;
        background-color: rgb(105, 228, 117);
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    }

    .ivy_hero{
        margin: auto;
    }
    .ivy_title_box{
        position: absolute;
        right: 100px;
        text-align: end;
    }

    .ivy_jumbo_title{
        font-size: 4.5rem;
        text-shadow: 0.5rem 0.5rem 0.5rem #0a900e;
    }

    .ivy_jumbo_subtitle{
        font-size: 3rem;
        text-shadow: 0.5rem 0.5rem 0.5rem #0a900e;
    }
</style>
