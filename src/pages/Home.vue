<template>
    <div class="crosspunk-home">
        <div class="text-center" style="margin-top: -50px">
            <div style="height: 670px" class="crosspunk-block crosspunk-mint-block">
                <div class="crosspunk-image bg-mint-image"></div>
                <div class="crosspunk-text container bg-mint-text">
                    <h1 class="crosspunk-h1">
                        Buy&nbsp;your&nbsp;CrossPunk&nbsp;now
                    </h1>
                    <p style="text-transform: uppercase;">
                        or&nbsp;watch&nbsp;your&nbsp;friends become&nbsp;millionaires&nbsp;later
                    </p>
                    <!-- <router-link :to="{ name : 'mint' }" id="go-to-mint" class="btn crosspunk-btn-rev">
                        Get one of {{ punkLeft }}
                    </router-link> -->
                </div>
            </div>
            <div style="height: 800px" class="crosspunk-block">
                <div class="crosspunk-image bg-our-image"></div>
                <div class="crosspunk-text container bg-our-text">
                    <h2 class="crosspunk-h1">Unique approach</h2>
                    <div>
                        <div class="row">
                            <img src="/img/01.png" />
                            <p class="col-9"><b>11 distinguished figures in the crypto field awaiting your Mint. Don't miss your turn to win!</b></p>
                        </div>
                        <div class="row">
                            <img src="/img/02.png" />
                            <p class="col-9"><b>We're on the Binance chain - closer to you.</b></p>
                        </div>
                        <div class="row">
                            <img src="/img/03.png" />
                            <p class="col-9"><b>Crypto enthusiasts team taking up the great challenge to make Crosschain NFT available for everyone.</b></p>
                        </div>
                    </div>
                </div>
            </div>
            <!-- <div style="height: 800px" class="crosspunk-block crosspunk-stats-block">
                <div class="crosspunk-image bg-stats-image"></div>
                <div class="crosspunk-text container bg-stats-text">
                    <h2 class="crosspunk-h1">Have a quick peek at some global Punks stats!</h2>
                    <p>The lowest selling price currently stands at <b>94.99 ETH ($ 358,906.43).</b></p>
                    <p>The average rate over the past year was <b>35.89 ETH (135,620.85 USD).</b></p>
                    <p>The average open bid is <b>4.09 ETH ($ 15,464.49).</b></p>
                    <p>The total cost of all current applications is <b>2,717.69 ETH (10,268,420.59 USD).</b></p>
                    <p>The average selling price of punk over the past year is <b>35.63 ETH ($ 134,615.76).</b></p>
                    <p>The total value of punks sold over the last year is <b>472,909.33 ETH (1,786,821,759.52 USD).</b></p>
                    <p><b>Just think about these numbers! Breathtaking, huh?</b></p>
                </div>
            </div> -->
            <!-- <div style="height: 800px" class="crosspunk-block crosspunk-how-block">
                <div class="crosspunk-image bg-how-image"></div>
                <div class="crosspunk-text container bg-how-text" style="height: 100%;">
                    <h2 class="crosspunk-h1">How to mint</h2>
                    <iframe width="100%" height="66%" src="https://www.youtube.com/embed/XuXulaydN9k?controls=0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                </div>
            </div> -->
            <div style="height: 530px" class="crosspunk-block crosspunk-what-block">
                <div class="crosspunk-image bg-what-image"></div>
                <div class="crosspunk-text container bg-what-text">
                    <h2 class="crosspunk-h1">What are the CrossPunks</h2>
                    <div>
                        <img src="/img/CP_PUNKS.png" style="float: left;">
                        <div style="margin-right: 0;">
                            <p>This is the first of its kind NFT cross-chain collection. 10,000 unique pixel characters. Including 11 the most important influencers in the Crypto World ever! 11 rare figures brought crypto and NFT future forward. Who inspired us as well!</p>
                            <p>Each punk you buy is 1 in 10,000 steps towards realizing the newest ability to move your NFTs across all blockchain networks.</p>
                        </div>
                    </div>
                </div>
            </div>
            <div style="height: 1000px" class="crosspunk-block crosspunk-roadmap-block">
                <div class="crosspunk-image bg-roadmap-image"></div>
                <div class="crosspunk-text container bg-roadmap-text">
                    <h2 class="crosspunk-h1">ROADMAP</h2>
                    <p>See upcoming steps of CROSSPUNKS project</p>
                    <img src="/img/roadmap.svg" />
                </div>
            </div>
            <div style="height: 530px" class="crosspunk-block crosspunk-why-block">
                <div class="crosspunk-image bg-why-image"></div>
                <div class="crosspunk-text container bg-why-text">
                    <h2 class="crosspunk-h1">Why now</h2>
                    <p>Are you familiar with a feeling of a missed train?</p>
                    <p>A wideass train fully stocked with explosive profit juice, and it runs near you just in a blink. Bang, you never had a moment to do something. What exactly do you feel at this point, perhaps you want to get back in time and buy first Punk for $30 or Bitcoin for $5 in 2012? Well, we don’t have a spare time machine, but, here we are to give you a precious possibility to be on time on a “profit platform”.</p>
                    <p>We’ll have you covered, and here’s your ticket!</p>
                </div>
            </div>
            <div style="height: 400px" class="crosspunk-block crosspunk-seen-block">
                <div class="crosspunk-image bg-seen-image"></div>
                <div class="crosspunk-text container bg-seen-text">
                    <h2 class="crosspunk-h1">As seen on</h2>
                    <div>
                        <a href="https://dappradar.com/binance-smart-chain/collectibles/crosspunks">
                            <img src="/img/dappradar.png">
                        </a>
                        <a href="https://nftcalendar.io/event/crosspunks-mint/">
                            <img src="/img/nftcalendar.png">
                        </a>
                        <a href="https://www.dapp.com/app/crosspunks">
                            <img src="/img/dapp.png">
                        </a>
                    </div>
                </div>
            </div>
        </div>
        <!-- <div v-if="other_devices">
            <transition name="modal">
                <div class="modal-mask">
                    <div class="modal-wrapper">
                        <div class="modal-dialog" role="document">
                            <div class="modal-content">
                                <div class="modal-header">
                                    <h5 class="modal-title">Other devices</h5>
                                    <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                                        <span aria-hidden="true" @click="other_devices = false">&times;</span>
                                    </button>
                                </div>
                                <div class="modal-body">
                                    Your device is not supported on this site. Please use our site on a desktop and use Chrome or Firefox.
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </transition>
        </div> -->
    </div>
</template>

<script>
export default {
    name: "Home",
    data() {
        return {
            searchById: "",
            punks: [],
            punkLeft: "10000",
        };
    },
    mounted() {
        let params = this.$route.params["id"];
        if (params > 0) {
            window.localStorage.setItem("inviteKey", params);
        }

        setInterval(() => {
            if (!this.loadPunk) {
                this.loadPunk = true;
                this.loadPunkLeft();
            }
        }, 100);
    },
    methods: {
        async loadPunkLeft() {
            await this.walletManager.checkId();
            setTimeout(async () => {
                let number = await this.walletManager.nft.totalSupply();
                this.punkLeft = 10000 - number;
            }, 1000);
        },
    },
};
</script>

<style>
@media only screen and (min-width: 1300px) {
    .crosspunk-h1 {
        font-size: 50pt;
    }

    .crosspunk-text a, .crosspunk-text p {
        font-size: 18pt;
    }
}

@media only screen and (max-width: 1299px) {
    .crosspunk-h1 {
        font-size: 45pt;
    }

    .crosspunk-text a, .crosspunk-text p {
        font-size: 16pt;
    }
}

@media only screen and (max-width: 1199px) {
    .crosspunk-h1 {
        font-size: 40pt;
    }

    .crosspunk-text a, .crosspunk-text p {
        font-size: 14pt;
    }

    .crosspunk-mint-block {
        height: 530px !important;
    }

    .crosspunk-stats-block {
        height: 700px !important;
    }

    .crosspunk-why-block {
        height: 400px !important;
    }

    .crosspunk-how-block {
        height: 600px !important;
    }

    .crosspunk-roadmap-block {
        height: 800px !important;
    }
}

@media only screen and (min-width: 992px) {
    .bg-our-text > div > .row:nth-child(2) > img {
        position: relative;
        right: -85%;
    }
}

@media only screen and (max-width: 991px) {
    .crosspunk-h1 {
        font-size: 30pt;
    }

    .crosspunk-mint-block {
        height: 400px !important;
    }

    .crosspunk-text a, .crosspunk-text p {
        font-size: 12pt;
    }

    .crosspunk-stats-block {
        height: 600px !important;
    }

    .crosspunk-why-block {
        height: 340px !important;
    }

    .crosspunk-roadmap-block {
        height: 600px !important;
    }
}

@media only screen and (min-width: 768px) {
    .bg-our-text .row p {
        text-align: left;
    }

    .bg-what-text div div {
        text-align: left;
    }
}

@media only screen and (max-width: 767px) {
    .crosspunk-h1 {
        font-size: 20pt;
    }

    .crosspunk-text a, .crosspunk-text p {
        font-size: 10pt;
    }

    .crosspunk-mint-block {
        height: 430px !important;
    }

    .bg-our-text {
        top: 5% !important;
    }

    .bg-our-text .row img {
        margin: auto;
        margin-bottom: 15px;
    }

    .crosspunk-stats-block {
        height: 500px !important;
    }

    .crosspunk-what-block {
        height: 430px !important;
    }

    .bg-what-text img {
        display: none;
    }

    .crosspunk-why-block {
        height: 300px !important;
    }

    .crosspunk-how-block {
        height: 500px !important;
    }

    .crosspunk-roadmap-block {
        height: 500px !important;
    }

    .crosspunk-seen-block {
        height: 500px !important;
    }
}

@media only screen and (max-width: 499px) {
    .crosspunk-h1 {
        font-size: 14pt;
    }

    .crosspunk-text a, .crosspunk-text p {
        font-size: 8pt;
    }

    .crosspunk-mint-block {
        height: 300px !important;
    }

    .crosspunk-what-block {
        height: 330px !important;
    }

    .crosspunk-why-block {
        height: 260px !important;
    }

    .crosspunk-roadmap-block {
        height: 400px !important;
    }
}

@media only screen and (max-width: 420px) {
    .crosspunk-h1 {
        font-size: 12pt;
    }

    .crosspunk-text a, .crosspunk-text p {
        font-size: 8pt;
    }

    .crosspunk-stats-block {
        height: 500px !important;
    }

    .crosspunk-what-block {
        height: 330px !important;
    }

    .crosspunk-why-block {
        height: 270px !important;
    }

    .crosspunk-how-block {
        height: 500px !important;
    }

    .crosspunk-roadmap-block {
        height: 350px !important;
    }

    .crosspunk-seen-block {
        height: 700px !important;
    }
}

.crosspunk-h1 {
    font-family: 'Montserrat', sans-serif;
    font-weight: 500;
    text-transform: uppercase;
}

.crosspunk-block {
    position: relative;
}

.crosspunk-image {
    /* Full height */
    height: 100%;
    /* Center and scale the image nicely */
    background-position: bottom;
    background-repeat: no-repeat;
    background-size: cover;
    position: absolute;
    top: 0;
    width: 100%;
    z-index: 1;
}

.bg-mint-image {
    background-image: url("/img/cp_web_bg_03_punk.jpg");
}

.bg-our-image {
    background-image: url("/img/cp_web_bg_02.jpg");
}

.bg-what-image {
    background-image: url("/img/bg_03.jpg");
}

.bg-why-image {
    background: rgb(217,61,118);
    background: linear-gradient(180deg, rgba(217,61,118,1) 0%, rgba(124,64,220,1) 50%);
}

.bg-roadmap-image{
    background: rgb(84,35,124);
    background: linear-gradient(180deg, rgba(84,35,124,1) 0%, rgba(23,33,58,1) 50%);
}

.crosspunk-text {
    background-color: rgb(0, 0, 0);
    /* Fallback color */
    background-color: rgba(0, 0, 0, 0);
    /* Black w/opacity/see-through */
    color: white;
    margin: 0 auto;
    position: relative;
    z-index: 2;
    width: 100%;
}

.crosspunk-text p {
    font-family: 'Montserrat', sans-serif;
    font-weight: 300;
}

.bg-mint-text {
    top: 20%;
}

.bg-our-text {
    top: 15%;
}

.bg-our-text .row {
    margin: 15px 0;
}

.bg-our-text .row p {
    height: min-content;
    margin: auto;
}

.bg-stats-text {
    top: 15%;
}

.bg-stats-text p b {
    font-family: 'Montserrat', sans-serif;
    font-weight: 500;
}

.bg-what-text {
    top: 20%;
}

.bg-what-text div img {
    margin-right: 20px;
}

.bg-why-text {
    top: 10%;
}

.bg-how-text {
    top: 10%;
}

.bg-how-text p {
    text-align: left;
}

.bg-how-text a {
    color: #d93d76 !important;
    text-shadow: #d93d76 0 0 10px;
}

.bg-how-text a:hover {
    text-decoration: none;
}

.bg-roadmap-text {
    top: 10%;
}

.bg-roadmap-text img {
    width: 100%;
}

.bg-seen-text {
    top: 10%;
}

.bg-seen-text div {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.bg-seen-text img {
    height: 190px;
    border-radius: calc(.25rem - 1px);
}

.bg-pinku {
    background-color: rgba(255, 192, 203, var(--tw-bg-opacity));
}

.pageboxborder {
    border-radius: 4px;
    border-color: #003760;
}

.vw5 {
    font-size: 5vw;
}

.text-blau {
    color: #296588 !important;
}

.text-center {
    text-align: center;
}

.vw2 {
    font-size: 2vw;
}

.text-pink-500 {
    --tw-text-opacity: 1;
    color: rgba(236, 72, 153, var(--tw-text-opacity));
}

.text-green-900 {
    --tw-text-opacity: 1;
    color: rgba(6, 78, 59, var(--tw-text-opacity));
}

.flex-wrap {
    display: block;
}

.border-8 {
    border-width: 8px;
    border-style: dashed;
}

.p-8 {
    padding: 2rem;
}

.modal-content {
    color: white;
}
</style>
