<script lang="ts">
    import ProgressIcon from "./ProgressIcon.svelte";

</script>

<div class="banner-wrapper">
    <ProgressIcon />
    <ProgressIcon />
</div>


<style>
    .banner-wrapper {
        margin: -5rem auto 0 auto;
        width: 500px;
        display: flex;
        justify-content: space-between;
        background-image: url("/images/backgrounds/bg1.png");
        padding: 2rem;
        border-radius: 1rem;
    }
</style>