<script>
    import Icon from "./Icon.svelte";
</script>

<div class="navbar">
    <div class="navbar-start">
        <Icon />
        <!-- svelte-ignore a11y-missing-attribute -->
        <a class="btn btn-ghost normal-case text-xl">ChessIsFun</a>
    </div>
    <div class="navbar-center hidden lg:flex">
        <!-- svelte-ignore a11y-missing-attribute -->
        <a class="nav btn btn-ghost">About Me</a>
        <!-- svelte-ignore a11y-missing-attribute -->
        <a class="nav btn btn-ghost">Socials</a>
        <!-- svelte-ignore a11y-missing-attribute -->
        <a class="nav btn btn-ghost">Pricing</a>
    </div>
    <div class="navbar-end">
        <!-- svelte-ignore a11y-missing-attribute -->
        <a class="btn sign-up">Sign up</a>
    </div>
</div>

<div class="divider" />

<style>
    .navbar {
        margin-top: 15px;
    }

    .text-xl {
        font-size: 50px;
    }

    .sign-up {
        font-size: 30px;
        background-color: white;
        color: rgb(33, 33, 33);
        border-radius: 4px;
    }

    .nav {
        font-size: 28px;
    }

    .navbar {
        justify-content: space-around;
    }

    .navbar-start {
        width: 35%;
    }

    .navbar-center {
        justify-content: space-evenly;
        width: 50%;
    }

    .navbar-end {
        width: 15%;
    }

    .divider {
        width: 95%;
        height: 1px;
        background-color: white;
        margin-left: auto;
        margin-right: auto;
    }
</style>
