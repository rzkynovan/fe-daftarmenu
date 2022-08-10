<script setup>

</script>

<template>
    <section class="beranda-sectio">
        <div class="container">
            <div class="d-flex flex-column">
                <h1>Edit Menu Resto</h1>
                <p>Edit menu restoranmu dibawah ini</p>
            </div>
            <div class="row d-flex justify-content-between">
                <div class="col-lg-10">
                <input type="text" class="form-control ">  
                </div>
                <div class="col-lg-2">
                <a href="" class="btn d-flex align-center gap-2"><img src="../assets/img/add-icon.png" alt=""> Tambah Menu</a>
                </div>

                <div class="table-responsive">
                    <div class="table-wrapper">
                        <table class="table-bordered  w-100">
                            <thead>
                                <tr>
                                    <th>Nama</th>
                                    <th>Harga</th>
                                    <th>Satuan</th>
                                    <th>Diskon</th>
                                    <th>Status</th>
                                    <th>Aksi</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr>
                                    <td><img src="../assets/img/hamburger.png" alt="">Bebek Goreng</td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
 .btn{
     background-color: orange;
 }
</style>
