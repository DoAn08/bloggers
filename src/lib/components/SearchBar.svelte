<script lang="ts">

</script>

<style lang="scss">
    .p {
        margin-bottom: 32px;
    }
    .searchform {
        width: calc(100% - 32px);
        padding: 16px;
        border: none;
        font-size: large;
        background-color: rgba(0, 0, 0, 0.03);
        font-family: 'Noto Sans', sans-serif;
    }
    .searchform:focus {
        outline: none;
    }
</style>

<div class="p">
    <form method="post">
        <input type="text" name="search" class="searchform" placeholder="search...">
    </form>
</div>