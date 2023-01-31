<script>

</script>


<main>
<img src="" alt="">
    <div class="wrapper">
        <h1>Åpningstider</h1>
        <div class="container">
            <div class="dag man">Mandag: 10:00-16:00</div>
            <div class="dag tir">Tirsdag: 10:00-16:00</div>
            <div class="dag ons">Onsdag: 10:00-16:00</div>
            <div class="dag tor">Torsdag: 10:00-16:00</div>
            <div class="dag fre">Fredag: 10:00-16:00</div>
        </div>
    </div>

</main>


<style>
    main {
        display: grid;
        place-content: center;
        height: 100vh;
        width: 100vw;
    }
    p {
        text-align: center;
        font-size: larger;
    }

    .container {
        display: flex;
        flex-direction: column;
        gap: 10px;
    }

    .dag {
        width: 100%;
        font-size: 20px;

    }
</style>