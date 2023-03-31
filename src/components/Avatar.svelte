<script lang="ts">
    const names: string[] = ["Indigo", "Holli"];
    const name: string = names[Math.floor(Math.random() * names.length)].toUpperCase();

</script>

    <div class="avatar-wrapper">
        <div class="avatar">
            <div class="avatar-inner-circle">
                <img src="images/avatars/chococat.png" alt="avatar">
            </div>
        </div>
        <h2>{name}</h2>
    </div>

<style>
    .avatar-wrapper {
        display: flex;
        flex-direction: column;
        justify-content: center;
        width: fit-content;
    }

    h2 {
        color: white;
        font-weight: 300;
        margin: 0;
    }

    .avatar {
        display: flex;
        align-items: center;
        justify-content: center;
        width: 100px;
        height: 100px;
        background-color: black; 
        border-radius: 50%;
        margin: 1rem;
    }

    .avatar-inner-circle {
        display: flex;
        align-items: center;
        width: 65px;
        height: 65px;
        background-color: grey;
        border-radius: 50%;
    }

    img {
        width: inherit;
    }
</style>