<template>
    <div id="header" class="grid grid-cols-2">
        <div class="grid grid-cols-2">
            <div class="kotak"></div>
            <div class="judul">
                <p>
                    Profile PBJI
                </p>
                <p>
                    Daerah Istimewa Yogyakarta
                </p>
                <h5>Pengurus Besar Jiu-Jitsu Indonesia</h5>
            </div>
        </div>
        <div class="foto">
            <img src="../assets/fotojjs-resize.jpg" alt="">
        </div>
    </div>

    <div id="about" class="">
        <div class="judul1">
            <h3>Tentang PBJI</h3>
        </div>
        <div class="fill">
            <p>
                Pengurus Besar Ju-Jitsu Indonesia (PBJI) Daerah Istimewa Yogyakarta resmi dilantik pada tanggal 10 Februari
                2022. PBJI Daerah Istimewa Yogyakarta dipimpin oleh Marjono, S.H. dan M. Herbowo E. yang akan bekerja dalam
                masa bakti 2022 - 2026.
            </p>
        </div>
    </div>

    <div id="about2" class="">
        <div class="judul2">
            <!-- <h3>Tentang PBJI DIY</h3> -->
        </div>
        <div class="clear"></div>
        <div class="fill2">
            <p>
                Pelantikan dilakukan oleh Sekretaris Jenderal PBJI Pusat mewakili Ketua Umum PBJI Pusat, Dr. Dedy
                Triharyanto, di Gedung Garuda RSPAU dr. Suhardi Hardjolukito Jl. Janti Yogyakarta, Lanud Adisucipto, Jl.
                Ringroad Timur, Karang Jambe, Banguntapan, Bantul, D.I. Yogyakarta.
            </p>
        </div>
    </div>


    <div class="visimisi">
        <div class="visi">
            <h3>Visi</h3>
            <p>
                Salah satu visi PBJI D.I. Yogyakarta adalah mencetak atlet dalam bentuk pembinaan atlet agar berprestasi dan
                mencari bibit - bibit atlet. Selain itu diharapkan bahwa Ju-Jitsu tidak hanya menjadi olahraga beladiri
                namun juga olahraga prestasi.
            </p>
        </div>
    </div>
</template>

<style>
.gambar img {
    width: 100px;
}

#header {
    box-sizing: border-box;
    margin-top: 20px;
    background-color: rgb(255, 255, 255);
}

.kotak {
    width: 122px;
    height: 400px;
    background-color: #636262;
    border-radius: 0px 20px 20px 0px;
}

.judul {
    margin: auto 0px;
}

.judul p {
    text-align: start;
    font-size: 40px;
    font-weight: bold;
}

.judul h5 {
    margin-top: 20px;
    font-style: italic;
    text-align: start;
    font-weight: bold;
}

.foto {
    background-color: rgb(255, 255, 255);
    display: flex;
    justify-content: flex-end;
    align-items: center;
}

.foto img {
    width: 416px;
    height: 314px;
    border-radius: 24px 0px 0px 24px;
}

#about {
    width: 800px;
    margin: 100px auto 20px;
    background-color: rgb(255, 255, 255);
}

#about2 {
    width: 800px;
    margin: 70px auto 130px;
    background-color: rgb(255, 255, 255);
}

#about .judul1 {
    width: 180px;
    height: 50px;
    background-color: rgb(255, 255, 255);
    border-bottom: 10px solid #CE231C;
}

#about .judul1 h3 {
    font-size: 22px;
    font-weight: bolder;
}

.fill {
    width: fit-content;
    margin: 20px 0px 0px 0px;
    background-color: rgb(255, 255, 255);
}

.fill p {
    text-align: start;
}

.judul2 {
    background-color: rgb(255, 255, 255);
    width: 180px;
    height: 50px;
    border-bottom: 10px solid #CE231C;
    float: right;
}

.fill2 {
    width: fit-content;
    margin: 20px 0px 0px 0px;
}

.fill2 p {
    text-align: end;
}

.clear {
    clear: right;
}

.visimisi {
    background-color: #CE231C;
    padding-bottom: 5%;
    width: 100%;
}

.visimisi .visi {
    width: 800px;
    /* background-color: aquamarine; */
    margin: 0px auto 0px;
    padding: 50px 0px 50px 0px;
}

.visi h3 {
    text-align: start;
    color: white;
    font-size: 32px;
}

.visi p {
    text-align: start;
    color: white;
}
</style>

<script setup>

</script>