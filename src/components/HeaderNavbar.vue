<script>

</script>

<template>
    <nav>
        <h1>MyPortfolio</h1>
        <ul class="ivy_nav_items">
            <li class="ivy_nav_item">
                <a href="#">Home</a>
            </li>
            <li class="ivy_nav_item">
                <a href="#">About</a>
            </li>
            <li class="ivy_nav_item">
                <a href="#">Gallery</a>
            </li>
            <li class="ivy_nav_item">
                <a href="#">Contact me</a>              
            </li>
        </ul>
    </nav>
</template>

<style scoped>
    nav{
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 0.5rem 1rem;
        background-color: rgb(215, 245, 248);
    }

    .ivy_nav_items{
        display: flex;
        list-style: none;
    }

    .ivy_nav_item{
        padding: 1rem 0;
        margin: 0 0.5rem;
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        font-size: 1.1rem;
        position: relative;
    }

    .ivy_nav_item a{
        text-decoration: none;
        color: #000;
    }

    .ivy_nav_item::after{
        content: '';
        position: absolute;
        height: 3px;
        border-radius: 5px;
        top: 75%;
        left: 0;
        width: 100%;
    }
    .ivy_nav_item:hover::after{
        background-color: #000;
        animation: borderSlide 1s ease-in-out;
    }

    @keyframes borderSlide{
        0%{
            width: 0;
            opacity: 0;
        }
        5%{
            opacity: 1;
        }
        100%{
            width: 100%;
        }
    }
</style>
