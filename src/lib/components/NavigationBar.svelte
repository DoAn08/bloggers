<script lang="ts">
    import home from '$lib/imgs/home.svg';
</script>

<style lang="scss">
    .p {
        margin: 24px 16px 24px 16px;
        height: fit-content;
        display: flex;
        align-items: center;
    }
    .center {
        margin-left: auto;
        margin-right: auto;
    }
</style>

<div class="p">
    <a href="/">home</a>
    <a href="/" class="center"><img src={home} alt="logo/home" height="64px" width="64px"></a>
    <a href="/about">about</a>
</div>