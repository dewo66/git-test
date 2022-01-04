<template>
    <!DOCTYPE html>
<html>

<head>
    <title>Netflix Clone</title>
    <link rel="stylesheet" href="C:\Users\dewo9\OneDrive\Masaüstü\netflink\css\index.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"
        integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="icon" href="N.png" />

</head>

<body>

    <header
        style="display:flex; z-index: 99; align-items: center; justify-content: space-between; position: fixed; height: 8vh; width: 100%; background-color: black;">
        <div style="display:flex; align-items: center;">
            <a href="">
                <h2 style="color: red; font-size: 1vw; margin-right: 25px; margin-left: 2vw;">NETFLIX</h2>
            </a>
            <a href="index.html">Ana Sayfa</a>
            <a href="#Diziler">Diziler</a>
            <a href="#Filmler">Filmler</a>
            <a href="#YenivePopi">Yeni ve Popüler</a>
            <a href="#Listem">Listem</a>
        </div>
        <div style="display:flex; margin-left: 10vw; margin-right: 5vw; float: right;">
            <img style=" margin-right: 25px; max-height: 3vh;"
                src="C:\Users\dewo9\OneDrive\Masaüstü\netflink\images\icons\search.svg">
            <img style="margin-right: 25px;  max-height: 3vh;"
                src="C:\Users\dewo9\OneDrive\Masaüstü\netflink\images\icons\notification.svg">
            <img style=" margin-right: 25px;  max-height: 3vh;"
                src="C:\Users\dewo9\OneDrive\Masaüstü\netflink\images\icons\user.svg">
        </div>
    </header>
    <div
        style=" display: flex; justify-content: center; align-items: flex-center; flex-direction: column; position: relative; ">
        <div style="position: absolute; z-index: 4; size: 10vw; margin-left: 3vw;  max-width: 40rem;   line-height: 1.6vw; letter-spacing: 2px;
        ">
            <img style="width: auto; height:auto;"
                src="https://occ-0-4609-2774.1.nflxso.net/dnm/api/v6/LmEnxtiAuzezXBjYXPuDgfZ4zZQ/AAAABVYA9Q7tZkRiKh95MD8wP-TtX-Z01ewj_1MUpcNDSakmVRozWnViTVPgc-Xs9BeLC8NG9EQA-wDSIgq5X30LBWjU7dipBbT-raZiPCRYOBK2yHv2UKmrzBRn5pLU8HDp-42yB3gFzDQyE1N0OGnXmwAj62dJ-Q2pQ-jBAFf5VpKX3w.webp?r=583">
            <div>
                <h3 style="    font-size: 1.6vw;
                color: #fff;
                text-shadow: 2px 2px 4px rgb(0 0 0 / 45%);
                margin: 1vw 0;
                font-weight: 700;">2. Sezonu Şimdi İzleyin</h3>
                <p style=" font-size: 1.4vw;   color: #fff;
                font-weight: 400;
                line-height: normal;
                width: 100%;
                font-size: 1.4vw;
                text-shadow: 2px 2px 4px rgb(0 0 0 / 45%);
                margin-top: .1vw;">Doğaüstü bir varlıkla bir anlaşma yapan iki lise öğrencisi, olağanüstü güçlere sahip
                    olur ve bir
                    cinayeti çözmek için iş birliği yapar.</p>
            </div>
            <div style="margin-top: 2rem;">
                <button style="
                padding-left: 2rem;
                padding-right: 2.4rem;
                padding-top: 1rem;
                padding-bottom: 1rem;
                margin-bottom: 1rem;
                margin-top: 1rem;
                border-radius:3px; "><i class="fas fa-play" style="margin-right: 0.3vw;"></i> Oynat</button>
                <button style="background-color: gray; color: white; margin: 1rem; 
                
                padding-left: 2rem;
                padding-right: 2.4rem;
                padding-top: 0.5rem;
                padding-bottom: 1rem;
                border-radius:3px; 
                font-weight: 700;
                letter-spacing: 0.1rem;
                font-size: 1.5rem"><i class="fas fa-exclamation" style="margin: 0.3vw;"></i>

                    Daha Fazla Bilgi</button>
            </div>


        </div>
        <img class="static-image"
            src=" https://occ-0-4609-2774.1.nflxso.net/dnm/api/v6/6AYY37jfdO6hpXcMjf9Yu5cnmO0/AAAABaG7A9Caw2GIqvr4L_C7umZwnFTVtEaTx_cC-UQLMPefcKKC_WpHO1w2deY9554eJmnA5CaBvTJT7gaU8Ro0LKkBugpC.webp?r=cd1">

    </div>
  
    <footer style="background-color: #141414;">
        <div class="container">
            <div style="display: flex; justify-content: space-between;">
                <div>
                    <ul style="display: flex;  flex-direction: column;  justify-content: space-between; ">
                        <li class="list-item">Seslendire ve Alt Yazı</li>
                        <li class="list-item">Medya Merkezi</li>
                        <li class="list-item">Gizlilik</li>
                        <li class="list-item">Bize Ulaşın</li>
                    </ul>
                </div>
                <div>
                    <ul style="display: flex;  flex-direction: column;  justify-content: space-between; ">
                        <li class="list-item">Sesli Betimleme</li>
                        <li class="list-item">Yatırımcı İlişkileri</li>
                        <li class="list-item">Yasal Hükümler</li>
                    </ul>
                </div>
                <div>
                    <ul style="display: flex;  flex-direction: column;  justify-content: space-between; ">
                        <li class="list-item">Yardım Merkezi</li>
                        <li class="list-item">İş İlanlari</li>
                        <li class="list-item">Çerez Tercihleri</li>
                    </ul>
                </div>
                <div>
                    <ul style="display: flex;  flex-direction: column;  justify-content: space-between; ">
                        <li class="list-item">Hediye Kartlari</li>
                        <li class="list-item">Kullanim Koşullari</li>
                        <li class="list-item">Kurumsal Bilgiler</li>
                    </ul>
                </div>
            </div>
            <button style="
                border: 1px solid #808080;
                color: #808080;
                background-color: transparent;
                margin: 20px 0px;
                border-radius: 3px; 
                padding: 10px 20px; 
                font-size: 18px;">Hizmet Kodu</button>
            <p>@1997-2021 Netflix, Inc. {d1e6ae9b-cCc-iMCiCi-3bir-dumteqteq</p>
        </div>
    </footer>
</body>
</html>

</template>

<script>
    var popup = document.getElementById("detailPopup")
    function popupnone() {
        popup.style.display = "none";
    }

</script>
<style>
    body { 
        color: white;
        background-color: #141414;
    }
    html::-webkit-scrollbar {
    display: none;
}

    a {
        color: white;
        margin-left: 1vw;
        text-decoration: none;
    }

    .container {
        max-width: 100%;
        padding-left: 40px;
        padding-right: 40px;
    }

    .list-item {
        margin: 0.5vw;
        color: gray;
    }

    section {
        margin-left: 6vh;
    }

    .fill-container {
        position: absolute;
        left: 0;
        top: 0;
        right: 0;
        bottom: 0;
    }

    .static-image {
        left: 0;
        right: 0;
        top: 0;
        bottom: 0;
        width: 100%;
        z-index: 3;
    }

    .detailPopup {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        position: fixed;
        width: 100%;
        height: 100%;
        z-index: 99;
    }

    .detailPopup #gray {

        position: fixed;
        width: 100%;
        height: 100%;
        background-color: gray;
        opacity: 0.3;
        z-index: -99;
    }

    .detailContainer {
        position: relative;
    }

    .previewModel {
        position: absolute;
        top: 10rem;
        left: 10rem;
    }
</style>