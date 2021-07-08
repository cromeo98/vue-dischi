<template>

    <main>
        <div class="container">
            <div class="row row-cols-5">
                <div class="col ms_cover-cont">
                    <img src="https://upload.wikimedia.org/wikipedia/en/thumb/2/2c/Bon_Jovi_New_Jersey.jpg/220px-Bon_Jovi_New_Jersey.jpg" alt="">
                    <p>testo1</p>
                    <p>testo2 più lungo di 1</p>
                </div>
            </div>
        </div>
    </main>

</template>

<script>
export default {
    name: 'Main',
}
</script>

<style scoped lang="scss">

main{
    background-color: rgb(30, 45, 59);
    height: calc(100vh - 60px);
}

</style>