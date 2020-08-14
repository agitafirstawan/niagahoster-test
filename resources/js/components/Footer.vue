<template>
    <div class="black-bg" >
        <div class="container-home pt-5" >
            <b-row>
                <b-col lg="3" md="4" xl="3" sm="12"  >
                    <div class="mb-4 mt-4" >
                        <p  >Hubungi Kami</p>
                    </div>
                    <div>
                        <span>0274-5305505</span>
                    </div>
                    <div>
                        <span>Senin - Minggu</span>
                    </div>
                    <div>
                        <span>24 Jam Nonstop</span>
                    </div>
                    <div class='mt-3' >
                        <span>JL Selokan Mataram Monjali Karangjati MT I/304 Sinduadi, Mlati, Sleman Yogyakarta 55284</span>
                    </div>
                </b-col>
                <b-col lg="3" md="4" xl="3" sm="12"  >
                    <div class='mb-4 mt-4' >
                        <p>Layanan</p>
                    </div>
                    <div>
                        <a href="#">Domain</a>
                    </div>
                    <div>
                        <a href="#">Shared Hosting</a>
                    </div>
                    <div>
                        <a href="#">Cloud VPS Hosting</a>
                    </div>
                    <div>
                        <a href="#">Managed VPS Hosting</a>

                    </div>
                    <div>
                        <a href="#">Web Builder</a>
                    </div>
                    <div>
                        <a href="#">Keamanan SSL / HTTPS</a>
                    </div>
                    <div>
                        <a href="#">Jasa Pembuatan Website</a>
                    </div>
                    <div>
                        <a href="#">Affiliasi</a>
                    </div>

                </b-col>
                <b-col lg="3" md="4" xl="3" sm="12"  >
                    <div class='mb-4 mt-4' >
                        <p>Service Hosting</p>
                    </div>
                    <div>
                        <a href="#">Hosting Murah</a>
                    </div>
                    <div>
                        <a href="#">Hosting indonesia</a>
                    </div>
                    <div>
                        <a href="#">Hosting Singapura</a>
                    </div>
                    <div>
                        <a href="#">Hosting PHP</a>

                    </div>
                    <div>
                        <a href="#">Hosting Wordpress</a>
                    </div>
                    <div>
                        <a href="#">Hosting Laravel</a>
                    </div>
                </b-col>
                <b-col lg="3" md="4" xl="3" sm="12"  >
                   <div class='mb-4 mt-4' >
                        <p>Tutorial</p>
                    </div>
                    <div>
                        <a href="#">Knowledge</a>
                    </div>
                    <div>
                        <a href="#">Blog</a>
                    </div>
                    <div>
                        <a href="#">Cara Pembayaran</a>
                    </div>
                </b-col>
                <b-col lg="3" md="4" xl="3" sm="12"  >
                    <div class='mb-4 mt-4' >
                        <p>Tentang Kami</p>
                    </div>
                    <div>
                        <a href="#">Tim Niagahoster</a>
                    </div>
                    <div>
                        <a href="#">Karir</a>
                    </div>
                    <div>
                        <a href="#">Events</a>
                    </div>
                    <div>
                        <a href="#">Penawaran dan Promo Spesial</a>
                    </div>
                    <div>
                        <a href="#">Kontak Kami</a>
                    </div>
                </b-col>
                <b-col lg="3" md="4" xl="3" sm="12"  >
                    <div class='mb-4 mt-4' >
                        <p>Penawaran dan Promo Spesial</p>
                    </div>
                    <div>
                        <a href="#">Kontak Kami</a>
                    </div>
                    <div>
                        <a href="#">Shared Hosting</a>
                    </div>
                    <div>
                        <a href="#">Cloud VPS Hosting</a>
                    </div>
                </b-col>
                <b-col lg="3" md="4" xl="3" sm="12"  >
                    <div class='mb-4 mt-4' >
                        <p>Newsletter</p>
                    </div>
                    <div class="newsletter-container" >
                        <b-row>
                            <b-col cols="12" >
                                <input type="text">
                                <button class='subscribe-btn' >Berlangganan</button>
                            </b-col>
                        </b-row>
                    </div>
                </b-col>
                <b-col lg="3" md="4" xl="3" sm="12"  >
                    <div class='mt-4' >
                        <b-row>
                            <b-col cols="4" >
                                    <button class="social" >
                                    <font-awesome-icon :icon="facebook" />
                                </button>

                            </b-col>
                            <b-col cols="4" >

                                <button class="social" >
                                    <font-awesome-icon :icon="twitter" />
                                </button>

                            </b-col>
                            <b-col cols="4" >
                                <button class="social" >
                                    <font-awesome-icon :icon="google" />
                                </button>
                            </b-col>
                        </b-row>
                    </div>
                </b-col>
                <b-col cols="12" >
                    <div class="mt-4" >
                        <p>Pembayaran</p>
                        <b-row></b-row>
                    <span>Aktivasi instan dengan e-Payment Hosting dan Domain langsung aktif</span>
                    </div>
                </b-col>
            </b-row>
        </div>
    </div>
</template>

<script>
import { faCheckCircle, faCommentAlt } from '@fortawesome/free-solid-svg-icons'
import { library } from '@fortawesome/fontawesome-svg-core'
import {faFacebook, faGoogle, faTwitter} from '@fortawesome/free-brands-svg-icons'
import Button from './Button'
library.add(faFacebook, faGoogle, faTwitter)
export default {
    name: 'Footer',
    data () {
        return {
            facebook: ['fab', 'facebook'],
            twitter: ['fab', 'twitter'],
            google: ['fab', 'google'],
            subscribe: 'Berlangganan'
        }
    },
    components: {
        Button
    }
}
</script>

<style scoped>
        .container-home {
            max-width: 1280px;
            margin: auto;
            padding: .5rem 1rem;
            margin-top: 0px;
        }

        .black-bg {
            background-color: #333 !important;
        }

        a {
            color: white !important;
            font-size: 12px;
        }

        p {
            color: white !important;
            font-size: 16px;
        }

        span {
            color: white !important;
        }

        .social {
            background-color: transparent !important;
            border: 1px solid white !important;
            border-radius: 50%;
            color: white;
            height: 50px;
            width: 50px;
        }

       input[type=text]{
        -webkit-border-radius: 20px;
        -moz-border-radius: 20px;
        border-radius: 20px;
        border: 1px solid #2d9fd9;
        color: #a0d18c;
        width: 100%;
        height: 40px;
        padding-left: 10px;
    }

    .subscribe-btn {
        position:absolute;right:7%; top:15%;
        border-radius: 20px;
        background-color: #2d9fd9;
        color: white;
        border: none !important;
    }
</style>
