<template>
    <div class="home">
        <img
            alt="Gorman Photo Logo"
            src="@/assets/gorman_photo.svg"
            class="logo"
        >
        <router-view />
    </div>
</template>
<style
    lang="sass"
>
    html,
    body
        max-width: 100vw
        width: 100%
        min-height: 100vh
        margin: 0
        padding: 0

        .logo
            max-width: 25rem
            margin: 2rem

        .home
            display: flex
            flex-direction: column
            align-items: center


</style>
