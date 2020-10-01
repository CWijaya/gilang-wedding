<template>
    <div id="app">
        <div id="gilang-milda">
            <p>Gilang</p>
            <img :src="require('@/assets/images/logo.svg')" alt="Logo" />
            <p>Milda</p>
        </div>
        <div id="header">
            <div class="couple-background"></div>
            <div class="title-box">
                <div class="inner">
                    <h1>WEDDING INVITATION</h1>
                    <h3>
                        <span>GILANG & MILDA</span>
                    </h3>
                    <div class="date-wrapper">
                        <img :src="require('@/assets/images/lego-small-icon.png')" alt />
                        <h3 class="date">24/10/2020</h3>
                        <img :src="require('@/assets/images/lego-small-icon.png')" alt />
                    </div>
                </div>
                <img
                    :src="require('@/assets/images/lego.svg')"
                    alt="Lego"
                    id="lego-1"
                    class="lego-scroll"
                    data-speed=".4"
                />
                <img
                    :src="require('@/assets/images/lego.svg')"
                    alt="Lego"
                    id="lego-2"
                    class="lego-scroll"
                    data-speed=".75"
                />
            </div>
        </div>
        <div id="invitation">
            <div class="invitation-background"></div>
            <div class="top">
                <div class="main-photo-wrapper">
                    <img :src="require('@/assets/images/main-photo.jpg')" alt="Gilang &amp; Milda" />
                    <img
                        :src="require('@/assets/images/lego.svg')"
                        alt="Lego"
                        id="lego-3"
                        class="lego-scroll"
                        data-speed=".7"
                    />
                </div>
                <img :src="require('@/assets/images/salam.png')" alt class="assalamualaikum" />
                <h2>Assalamualaikum Warahmahtullahi Wabarakatuh</h2>
                <p>Maha suci Allah SWT, yang telah menciptakan makhluk-Nya berpasang-pasangan.</p>
                <p class="bold">Perkenankanlah kami menikahkan Putra-Putri kami</p>
            </div>
            <div class="middle">
                <div class="love-icon-wrapper hidden-xs">
                    <img :src="require('@/assets/images/heart.svg')" alt="Love" class="heart" />
                    <img
                        :src="require('@/assets/images/heart-line.png')"
                        alt="Line"
                        class="heart-line"
                    />
                </div>
                <div class="row">
                    <div class="col-xs-12 col-sm-6 text-right">
                        <div class="profile right">
                            <div class="profile-image-wrapper">
                                <img
                                    :src="require('@/assets/images/lego-gilang.png')"
                                    alt="Ini Gilang"
                                    class="lego-image"
                                />

                                <img
                                    :src="require('@/assets/images/gilang.jpg')"
                                    alt="Ini Gilang"
                                    class="profile-image"
                                />
                            </div>
                            <h1>Gilang Ilham Akbar</h1>
                            <p>Putra ketiga dari Bapak Erizal Kosim dan Ibu Tety Rohyati</p>
                        </div>
                    </div>
                    <div class="col-xs-12 visible-xs">
                        <div class="love-icon-wrapper">
                            <img
                                :src="require('@/assets/images/heart.svg')"
                                alt="Love"
                                class="heart"
                            />
                            <img
                                :src="require('@/assets/images/heart-line.png')"
                                alt="Line"
                                class="heart-line"
                            />
                        </div>
                    </div>
                    <div class="col-xs-12 col-sm-6">
                        <div class="profile">
                            <div class="profile-image-wrapper">
                                <img
                                    :src="require('@/assets/images/lego-milda.png')"
                                    alt="Ini Milda"
                                    class="lego-image right"
                                />
                                <img
                                    :src="require('@/assets/images/milda.jpg')"
                                    alt="Ini Milda"
                                    class="profile-image"
                                />
                            </div>
                            <h1>Mildazahipa Ilmy Arsy</h1>
                            <p
                                class="milda"
                            >Putri pertama dari Bapak Ahmad Rosikin dan Ibu Eni Yunaida</p>
                            <img
                                :src="require('@/assets/images/lego.svg')"
                                alt="Lego"
                                id="lego-4"
                                class="lego-scroll"
                                data-speed=".5"
                            />
                        </div>
                    </div>
                </div>
            </div>
            <div class="bottom">
                <img
                    :src="require('@/assets/images/line-clip.png')"
                    alt="Line"
                    class="memories-rope"
                />
                <div class="inner">
                    <div class="row">
                        <div class="col-xs-6 col-sm-3 hidden-xs">
                            <div class="memories-wrapper no-1">
                                <img
                                    :src="require('@/assets/images/clip.png')"
                                    alt="Clip"
                                    class="clip"
                                />
                                <div class="memories-photo">
                                    <img
                                        :src="require('@/assets/images/memories-1.png')"
                                        alt="Waktu Milda Resign"
                                    />
                                    <p>12 Juli 2019</p>
                                </div>
                                <div class="memories-description">
                                    <img
                                        :src="require('@/assets/images/arrow.png')"
                                        alt="Keterangan"
                                    />
                                    <p>Milda resign, jadi udah nggak satu kantor lagi deh :(</p>
                                </div>
                            </div>
                        </div>
                        <div class="col-xs-6 col-sm-3">
                            <div class="memories-wrapper no-2">
                                <img
                                    :src="require('@/assets/images/clip.png')"
                                    alt="Clip"
                                    class="clip"
                                />
                                <div class="memories-photo">
                                    <img
                                        :src="require('@/assets/images/memories-2.png')"
                                        alt="Waktu Milda Resign"
                                    />
                                    <p>27 Agustus 2019</p>
                                </div>
                                <div class="memories-description top no-2">
                                    <p>Tahun pertama ulang tahun bareng, sibuk cari kado!</p>
                                    <img
                                        :src="require('@/assets/images/arrow.png')"
                                        alt="Keterangan"
                                    />
                                </div>
                            </div>
                        </div>
                        <div class="col-xs-6 col-sm-3">
                            <div class="memories-wrapper no-3">
                                <img
                                    :src="require('@/assets/images/clip.png')"
                                    alt="Clip"
                                    class="clip"
                                />
                                <div class="memories-photo">
                                    <img
                                        :src="require('@/assets/images/memories-3.png')"
                                        alt="Waktu Milda Resign"
                                    />
                                    <p>06 Desember 2019</p>
                                </div>
                                <div class="memories-description no-3">
                                    <img
                                        :src="require('@/assets/images/arrow.png')"
                                        alt="Keterangan"
                                    />
                                    <p>Jalan-jalan di Malang sama dua keluarga :)</p>
                                </div>
                            </div>
                        </div>
                        <div class="col-xs-6 col-sm-3 hidden-xs">
                            <div class="memories-wrapper no-4">
                                <img
                                    :src="require('@/assets/images/clip.png')"
                                    alt="Clip"
                                    class="clip"
                                />
                                <div class="memories-photo">
                                    <img
                                        :src="require('@/assets/images/memories-4.png')"
                                        alt="Waktu Milda Resign"
                                    />
                                    <p>27 Agustus 2020</p>
                                </div>
                                <div class="memories-description top no-4">
                                    <p>Kado sesuai request nggak serepot tahun lalu :P</p>
                                    <img
                                        :src="require('@/assets/images/arrow.png')"
                                        alt="Keterangan"
                                    />
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div id="photoshoot">
            <div class="row row-flex-desktop">
                <div class="col-xs-12 col-sm-6 no-padding-right-desktop position-relative">
                    <div class="photoshoot-main-cover"></div>
                    <img
                        :src="require('@/assets/images/photoshoot-main.jpg')"
                        alt="Gilang &amp; Milda"
                        class="photoshoot-main"
                    />
                </div>
                <div class="col-xs-12 col-sm-6 no-padding-left-desktop">
                    <div class="wedding-date-place">
                        <div class="inner">
                            <div class="content">
                                <p>Yang Insyaallah akan diselenggarakan pada:</p>
                                <h1>Sabtu, 24 Okt 2020</h1>
                                <div class="row">
                                    <div class="col-xs-12 col-sm-6">
                                        <div class="akad-syukuran">
                                            <p>01. Akad Nikah</p>
                                            <p>14.00 - 15.00 WIB</p>
                                        </div>
                                    </div>
                                    <div class="col-xs-12 col-sm-6">
                                        <div class="akad-syukuran">
                                            <p>02. Syukuran Akad Nikah</p>
                                            <p>15.30 - 17.30 WIB</p>
                                        </div>
                                    </div>
                                </div>
                                <div class="row">
                                    <div class="col-xs-12">
                                        <div class="akad-location">
                                            <div class="media">
                                                <div class="media-left">
                                                    <img
                                                        :src="require('@/assets/images/pin-location.png')"
                                                        alt="Location"
                                                        class="pin-location"
                                                    />
                                                </div>
                                                <div class="media-body">
                                                    <p>Taman Indie Resto</p>
                                                    <p>JL. Araya Megah No.9, Pandanwangi, Kec Blimbing, Kota Malang, Jawa Timur</p>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div id="photoshoot-grid">
            <div class="inner">
                <div class="row">
                    <div class="col-xs-12 col-sm-6">
                        <img
                            :src="require('@/assets/images/photoshoot-1.jpg')"
                            alt="Gilang &amp; Milda"
                            class="photoshoot-grid-image"
                        />
                    </div>
                    <div class="col-xs-12 col-sm-6">
                        <img
                            :src="require('@/assets/images/photoshoot-2.jpg')"
                            alt="Gilang &amp; Milda"
                            class="photoshoot-grid-image"
                        />
                    </div>
                </div>
                <div class="row">
                    <div class="col-xs-12 col-sm-6">
                        <img
                            :src="require('@/assets/images/photoshoot-3.jpg')"
                            alt="Gilang &amp; Milda"
                            class="photoshoot-grid-image"
                        />
                    </div>
                    <div class="col-xs-12 col-sm-6">
                        <img
                            :src="require('@/assets/images/photoshoot-4.jpg')"
                            alt="Gilang &amp; Milda"
                            class="photoshoot-grid-image"
                        />
                    </div>
                </div>
                <img
                    :src="require('@/assets/images/lego.svg')"
                    alt="Lego"
                    id="lego-5"
                    class="lego-scroll"
                    data-speed=".74"
                />

                <img
                    :src="require('@/assets/images/lego.svg')"
                    alt="Lego"
                    id="lego-6"
                    class="lego-scroll"
                    data-speed=".5"
                />
            </div>
        </div>
        <div id="map-embed">
            <iframe
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3951.5742926887124!2d112.66241581530943!3d-7.939449681278106!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2dd628e5abdb212f%3A0x7234a042cc61972f!2sTaman%20Indie!5e0!3m2!1sen!2sid!4v1600516113623!5m2!1sen!2sid"
                frameborder="0"
                style="border:0;"
                allowfullscreen
                aria-hidden="false"
                tabindex="0"
            ></iframe>
        </div>
        <div id="dresscode">
            <div class="dresscode-background"></div>
            <h2>Dresscode</h2>
            <h3>Laki - laki & Perempuan</h3>
            <div class="inner">
                <div class="row">
                    <div class="col-xs-12 col-sm-4">
                        <div class="dresscode-item">
                            <img
                                :src="require('@/assets/images/mask.png')"
                                alt="Mask"
                                class="dresscode-image image-1"
                            />
                            <p>Wajib pakai masker ya!</p>
                        </div>
                    </div>
                    <div class="col-xs-12 col-sm-4">
                        <div class="dresscode-item">
                            <img
                                :src="require('@/assets/images/dresscode.png')"
                                alt="Atasan"
                                class="dresscode-image image-2"
                            />
                            <p>Baju warna putih.</p>
                        </div>
                    </div>
                    <div class="col-xs-12 col-sm-4">
                        <div class="dresscode-item">
                            <img
                                :src="require('@/assets/images/dresscode-bottom.png')"
                                alt="Bawahan"
                                class="dresscode-image image-3"
                            />
                            <p>Celana / Rok warna netral.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div id="terimakasih">
            <div class="inner">
                <p>Merupakan suatu kehormatan dan kebahagiaan bagi kami apabila Bapak/Ibu/Saudara/i berkenan hadir untuk memberikan do’a restu kepada kedua mempelai.</p>
                <h4>Wassalamualaikum Warahmatullahi Wabarakatuh</h4>
            </div>
        </div>
        <footer id="footer">
            <div class="row">
                <div class="col-xs-6 text-right">
                    <div class="social-media-container left">
                        <a href="https://www.instagram.com/gilang.i_a/" target="_blank">
                            <div class="instagram-icon-wrapper">
                                <img
                                    :src="require('@/assets/images/instagram-icon.png')"
                                    alt="Instagram"
                                    class="instagram-icon"
                                />
                            </div>
                            <p>Gilang.i_a</p>
                        </a>
                    </div>
                </div>
                <div class="col-xs-6">
                    <div class="social-media-container right">
                        <a href="https://www.instagram.com/mildaza/" target="_blank">
                            <div class="instagram-icon-wrapper">
                                <img
                                    :src="require('@/assets/images/instagram-icon.png')"
                                    alt="Instagram"
                                    class="instagram-icon"
                                />
                            </div>
                            <p>Mildaza</p>
                        </a>
                    </div>
                </div>
            </div>
        </footer>
    </div>
</template>

<script>
import { gsap, ScrollTrigger } from "gsap/all";
gsap.registerPlugin(ScrollTrigger);
export default {
    name: "App",
    mounted() {
        gsap.utils.toArray(".lego-scroll").forEach((lego, index) => {
            if (index === 0 || index === 1) {
                gsap.to(lego, {
                    scrollTrigger: {
                        scrub: true,
                    },
                    y: (i, target) =>
                        -ScrollTrigger.maxScroll(window) * target.dataset.speed,
                    ease: "none",
                });
            } else {
                gsap.to(lego, {
                    scrollTrigger: {
                        trigger: lego,
                        scrub: true,
                        start: "center bottom", // the default values
                        end: "bottom top",
                    },
                    ease: "none",
                    // y: (i, target) =>
                    //     -ScrollTrigger.maxScroll(window) * target.dataset.speed,
                    // yPercent: -(lego.dataset.speed * 300),
                    y: -(lego.dataset.speed * 500),
                });
            }
        });
    },
};
</script>

<style lang="scss">
@import "./src/assets/main.scss";
@import "./src/assets/vars/variables";

#gilang-milda {
    position: absolute;
    width: 100%;
    top: 0;
    left: 0;
    display: flex;
    align-items: center;
    justify-content: center;
    z-index: 1;
    margin-top: 15px;

    @include media-query-tablet-portrait-up {
        margin-top: 30px;
    }

    img {
        flex: 0 0 auto;
        width: 55px;
        margin-left: 20px;
        margin-right: 20px;

        @include media-query-tablet-portrait-up {
            width: 84px;
        }
    }

    p {
        flex: 1;
        color: #fff;
        margin-bottom: 0;
        font-family: "DIN Alternate Light";
        text-transform: uppercase;

        &:first-child {
            text-align: right;
        }
    }
}

footer#footer {
    position: relative;
    width: 100%;
    padding: 10px 15px;

    .social-media-container {
        &.left {
            margin-right: 10px;
        }

        &.right {
            margin-left: 10px;
        }
        .instagram-icon-wrapper {
            display: inline-block;
            border-radius: 50%;
            background-color: #bc2a95;
            padding: 10px;
            vertical-align: middle;
            margin-right: 10px;

            @include media-query-tablet-portrait-up {
                margin-right: 15px;
            }

            img.instagram-icon {
                display: block;
                width: 20px;
            }
        }

        a {
            color: #383838;
            text-decoration: none;
        }

        p {
            display: inline-block;
            vertical-align: middle;
            margin-bottom: 0;
            font-size: 17px;

            @include media-query-tablet-portrait-up {
                font-size: 20px;
            }
        }
    }
}

#terimakasih {
    position: relative;
    width: 100%;
    background-image: url("./assets/images/lego-pattern.jpg");
    text-align: center;
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    padding: 12% 15px;

    @include media-query-tablet-portrait-up {
        padding: 5% 15px;
    }

    .inner {
        position: relative;
        width: 100%;
        max-width: 1100px;
        margin: 0 auto;
    }

    p,
    h4 {
        color: #fff;
    }

    p {
        font-family: "DIN Alternate Bold";
        line-height: 1.3;
    }

    h4 {
        color: $secondary-color;
    }
}

#dresscode {
    position: relative;
    width: 100%;
    background-color: $tertiary-color;
    padding: 50px 15px;
    text-align: center;

    .dresscode-background {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background-image: url("./assets/images/main-background.png");
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
        mix-blend-mode: multiply;
    }

    h2 {
        font-size: 50px;

        @include media-query-tablet-portrait-up {
            font-size: 64px;
        }
    }

    h3 {
        display: inline-block;
        color: $secondary-color;
        letter-spacing: 0;
        border-bottom: 5px solid $secondary-color;
        padding: 3px 20px;
        margin-top: 30px;
        margin-bottom: 60px;
    }

    .inner {
        position: relative;
        width: 76%;
        margin-left: auto;
        margin-right: auto;

        .dresscode-item {
            position: relative;
            text-align: center;
            margin-bottom: 35px;

            @include media-query-tablet-portrait-up {
                margin-bottom: 0;
            }

            img.dresscode-image {
                display: block;
                width: 100%;
                height: auto;
                object-fit: contain;
                margin-left: auto;
                margin-right: auto;
                margin-bottom: 15px;

                @include media-query-tablet-portrait-up {
                    height: 120px;
                    margin-bottom: 25px;
                }

                &.image-1 {
                    max-width: 250px;
                }
                &.image-2 {
                    max-width: 390px;
                }
                &.image-3 {
                    max-width: 310px;
                }
            }

            p {
                position: relative;
                display: inline-block;

                &:before {
                    content: "";
                    display: block;
                    position: absolute;
                    top: 50%;
                    left: -37px;
                    width: 24px;
                    height: 19px;
                    background-size: cover;
                    background-repeat: no-repeat;
                    background-image: url("./assets/images/lego-small-icon-blue.png");
                    transform: translateY(-50%);
                }
            }
        }
    }
}

#map-embed {
    iframe {
        position: relative;
        display: block;
        width: 100%;
        height: 380px;

        @include media-query-medium-desktop-up {
            height: 500px;
        }
    }
}

#photoshoot-grid {
    position: relative;
    width: 100%;
    background-color: #ffd6cb;
    background: linear-gradient(
        to bottom,
        #ffd6cb 0%,
        #ffd6cb 70%,
        $tertiary-color 70%,
        $tertiary-color 100%
    );
    padding: 14% 15px 15px;

    @include media-query-tablet-portrait-up {
        padding: 6% 5% 5%;
    }

    .inner {
        position: relative;
        width: 100%;
        margin-left: auto;
        margin-right: auto;

        @include media-query-tablet-portrait-up {
            width: 84%;
        }

        @include media-query-medium-desktop-up {
            width: 76%;
        }

        img.photoshoot-grid-image {
            display: block;
            width: 100%;
            border: 16px solid #fff;
            margin-bottom: 30px;
        }

        img#lego-5 {
            display: block;
            position: absolute;
            bottom: 7%;
            left: 0;
            width: 9%;
            width: 120px;
            transform: rotateZ(-4deg);
            z-index: 1;

            @include media-query-tablet-portrait-up {
                left: -5%;
            }
        }

        img#lego-6 {
            display: block;
            position: absolute;
            top: 10%;
            right: 0;
            width: 14%;
            transform: rotateZ(-17deg);
            z-index: 1;

            @include media-query-tablet-portrait-up {
                right: -9%;
            }
        }
    }
}

#photoshoot {
    .photoshoot-main-cover {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background-image: url("./assets/images/photoshoot-main.jpg");
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;

        @include media-query-mobile {
            display: none;
        }
    }

    img.photoshoot-main {
        display: none;
        width: 100%;

        @include media-query-mobile {
            display: block;
        }
    }

    .wedding-date-place {
        position: relative;
        width: 100%;
        background-image: url("./assets/images/lego-pattern-square.jpg");
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
        padding: 17px;

        .inner {
            border: 4px solid $secondary-color;
            border-radius: 15px;
            padding: 10% 15px 5%;
            text-align: center;

            .content {
                width: 94%;
                margin-left: auto;
                margin-right: auto;

                @include media-query-tablet-portrait-up {
                    width: 92%;
                }

                @include media-query-medium-desktop-up {
                    width: 88%;
                }
            }

            p {
                color: #fff;
            }

            h1 {
                color: #fff;
                position: relative;
                margin-top: 24px;
                margin-bottom: 24px;
                font-size: 35px;
                font-size: 9.5vw;
                padding: 25px 0;

                @include media-query-tablet-portrait-up {
                    font-size: 5.2vw;
                    line-height: 1.6;
                    margin-top: 7%;
                    margin-bottom: 7%;
                    padding: 0;
                }

                &:before,
                &:after {
                    content: "";
                    display: block;
                    top: 0;
                    left: 50%;
                    width: 100%;
                    height: 5px;
                    background-color: #fff;
                    transform: translateX(-50%);
                    position: absolute;
                }

                &:after {
                    top: initial;
                    bottom: 0;
                }
            }

            .akad-syukuran {
                text-align: left;
                padding-left: 20px;

                p {
                    margin-bottom: 0;

                    &:first-child {
                        color: $secondary-color;
                        font-family: "Din Alternate Bold";
                        margin-bottom: 0;

                        @include media-query-tablet-portrait-up {
                            margin-bottom: 10px;
                        }
                    }

                    &:last-child {
                        margin-left: 22px;
                        font-size: 20px;
                        margin-bottom: 20px;

                        @include media-query-tablet-portrait-up {
                            margin-left: 26px;
                            font-size: 25px;
                            margin-bottom: 0;
                        }

                        @include media-query-desktop-up {
                            margin-left: 34px;
                            font-size: 28px;
                        }

                        @include media-query-medium-desktop-up {
                            margin-left: 40px;
                            font-size: 32px;
                        }
                    }
                }
            }

            .akad-location {
                position: relative;
                padding-top: 7%;
                padding-left: 0;
                margin-top: 20px;
                text-align: left;

                @include media-query-tablet-portrait-up {
                    margin-top: 10%;
                    padding-left: 20px;
                }

                img.pin-location {
                    display: block;
                    width: 52px;
                }

                &:before {
                    content: "";
                    display: block;
                    width: 100%;
                    height: 1px;
                    background-color: $secondary-color;
                    position: absolute;
                    top: 0;
                    left: 0;
                }

                .media-body {
                    p {
                        line-height: 1.5;

                        &:first-child {
                            color: $secondary-color;
                            font-family: "Din Alternate Bold";
                            margin-bottom: 10px;
                        }
                    }
                }
            }
        }
    }
}

#invitation {
    position: relative;
    width: 100%;
    background-color: $tertiary-color;
    padding-bottom: 40%;

    @include media-query-tablet-portrait-up {
        padding-bottom: 18%;
    }

    @include media-query-desktop-up {
        padding-bottom: 15%;
    }

    .invitation-background {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background-image: url("./assets/images/main-background.png");
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
        mix-blend-mode: multiply;
    }

    .top {
        position: relative;
        width: 100%;
        padding: 0 15px;
        margin: 0 auto;
        top: -45px;
        text-align: center;

        @include media-query-tablet-portrait-up {
            width: 90%;
        }

        @include media-query-tablet-landscape-up {
            width: 85%;
        }

        @include media-query-desktop-up {
            width: 81%;
        }

        @include media-query-medium-desktop-up {
            width: 76%;
            top: -70px;
        }

        .main-photo-wrapper {
            position: relative;
            width: 100%;
            background-color: #fff;
            padding: 15px;
            margin-bottom: 6%;

            img {
                display: block;
                width: 100%;
            }

            img#lego-3 {
                display: block;
                position: absolute;
                top: 49%;
                left: 0;
                width: 21%;
                transform: rotateZ(-17deg);
                filter: blur(7px);

                @include media-query-tablet-portrait-up {
                    left: -13%;
                }
            }
        }

        img.assalamualaikum {
            display: block;
            width: 100%;
            max-width: 500px;
            margin: 0 auto;
            margin-bottom: 4%;

            @include media-query-mobile {
                margin-bottom: 20px;
            }
        }

        h2 {
            color: $secondary-color;
            margin-bottom: 35px;

            @include media-query-mobile {
                font-size: 4.5vw;
                font-size: 24px;
                margin-bottom: 30px;
            }
        }
    }

    .middle {
        position: relative;
        width: 100%;
        padding: 0 15px;

        .love-icon-wrapper {
            position: relative;

            @include media-query-tablet-portrait-up {
                position: absolute;
                top: 50%;
                left: 50%;
                transform: translateX(-50%) translateY(-74%);
            }

            @include media-query-desktop-up {
                transform: translateX(-50%) translateY(-62%);
            }

            @include media-query-medium-desktop-up {
                transform: translateX(-50%) translateY(-50%);
            }

            img.heart {
                display: block;
                width: 60px;
                margin: 0 auto;
                margin-bottom: 10px;
                margin-top: 40px;

                @include media-query-tablet-portrait-up {
                    margin-top: 0;
                }
            }

            img.heart-line {
                display: block;
                width: 127%;
                margin: 0 auto;
                margin-bottom: 40px;
                margin-left: -15px;
                margin-top: 15px;

                @include media-query-tablet-portrait-up {
                    margin-top: 0;
                    width: 100%;
                    margin-left: 7%;
                    width: 450px;
                    margin-bottom: 0;
                }
            }
        }

        .profile {
            position: relative;
            width: 100%;
            max-width: 570px;
            width: 82%;
            text-align: left;
            margin-left: 0;

            @include media-query-tablet-portrait-up {
                margin-left: 8%;
                width: 72%;
            }

            @include media-query-desktop-up {
                width: 62%;
            }

            &.right {
                margin-left: auto;
                margin-right: 0;

                @include media-query-tablet-portrait-up {
                    margin-right: 8%;
                }
            }

            .profile-image-wrapper {
                position: relative;

                img.lego-image {
                    position: absolute;
                    bottom: 10px;
                    right: 81%;
                    width: 49%;
                    z-index: 0;

                    @include media-query-mobile {
                        right: 78%;
                    }

                    &.right {
                        right: initial;
                        left: 81%;

                        @include media-query-mobile {
                            left: 79%;
                        }
                    }
                }

                img.profile-image {
                    position: relative;
                    display: block;
                    width: 100%;
                    border: 17px solid #fff;
                    margin-bottom: 35px;
                    z-index: 1;

                    @include media-query-tablet-portrait-up {
                        border: 21px solid #fff;
                    }

                    @include media-query-medium-desktop-up {
                        border: 26px solid #fff;
                    }

                    @include media-query-medium-desktop-up {
                        border: 32px solid #fff;
                    }
                }
            }

            h1 {
                font-weight: bold;
                letter-spacing: 0;
                font-size: 38px;

                @include media-query-tablet-portrait-up {
                    font-size: 3.85vw;
                }
            }

            p {
                color: #333333;
                line-height: 1.5;

                &.milda {
                    @include media-query-mobile {
                        width: 112%;
                    }
                }
            }

            img#lego-4 {
                display: block;
                position: absolute;
                top: 0;
                right: 0;
                width: 23%;
                transform: rotateZ(-17deg);
                z-index: 1;

                @include media-query-tablet-portrait-up {
                    right: -17%;
                }
            }
        }
    }

    .bottom {
        position: relative;
        width: 100%;
        margin-top: 40%;

        @include media-query-tablet-portrait-up {
            margin-top: 18%;
        }

        @include media-query-desktop-up {
            margin-top: 10%;
        }

        @include media-query-medium-desktop-up {
            margin-top: 8%;
        }

        img.memories-rope {
            position: relative;
            width: 100%;
            display: block;
        }

        .inner {
            position: relative;
            width: 100%;
            max-width: 1400px;
            padding: 0 15px;
            margin: 0 auto;

            .memories-wrapper {
                position: relative;
                width: 94%;
                margin: 0 auto;

                &.no-1 {
                    // img.clip {
                    //     top: -19%;
                    // }
                }

                &.no-2 {
                    margin-top: 10px;
                    transform: rotateZ(5deg);
                    margin-right: auto;
                    margin-left: 0;

                    img.clip {
                        transform: translateX(-50%) rotateZ(10deg);
                    }
                }

                &.no-3 {
                    transform: rotateZ(-5deg);
                    margin-left: auto;
                    margin-right: 0;

                    img.clip {
                        transform: translateX(-50%) rotateZ(10deg);
                    }
                }

                &.no-4 {
                    margin-top: -18px;

                    img.clip {
                        transform: translateX(-50%) rotateZ(15deg);
                    }
                }

                img.clip {
                    position: absolute;
                    left: 50%;
                    top: -23%;
                    transform: translateX(-50%);
                    z-index: 1;
                    width: 45px;

                    @include media-query-tablet-portrait-up {
                        width: 65px;
                    }

                    @include media-query-desktop-up {
                        width: 80px;
                    }

                    @include media-query-medium-desktop-up {
                        width: 90px;
                    }
                }

                .memories-photo {
                    position: relative;
                    padding: 12px;
                    background-color: #fff;

                    img {
                        display: block;
                        width: 100%;
                        margin-bottom: 10px;
                    }

                    p {
                        font-size: 17px;
                        color: $secondary-color;
                        margin-bottom: 0;

                        @include media-query-desktop-up {
                            font-size: 20px;
                        }
                    }
                }

                .memories-description {
                    position: absolute;
                    left: -9%;
                    top: 95%;

                    @include media-query-medium-desktop-up {
                        left: -18%;
                    }

                    &.top {
                        top: initial;
                        bottom: 100%;
                    }

                    &.no-2 {
                        left: -10%;
                        bottom: 96%;
                        width: 160%;
                        transform: rotateZ(-5deg);

                        @include media-query-tablet-portrait-up {
                            width: 110%;
                        }

                        img {
                            transform: scaleY(-1) rotateZ(13deg);
                            margin-left: 16px;
                        }

                        p {
                            text-align: left;
                            margin-bottom: 6px;
                        }
                    }

                    &.no-3 {
                        left: 4%;
                        top: 89%;
                        transform: rotateZ(5deg);

                        img {
                            transform: scaleX(-1) rotateZ(30deg);
                            margin-right: 36px;
                            margin-left: auto;
                        }

                        p {
                            text-align: left;
                        }
                    }

                    &.no-4 {
                        left: 2%;
                        bottom: 94%;
                        width: 120%;
                        transform: rotateZ(-5deg);

                        img {
                            transform: scaleY(-1) scaleX(-1);
                            margin-left: auto;
                            margin-right: 36px;
                        }

                        p {
                            text-align: left;
                            margin-bottom: 6px;
                        }
                    }

                    img {
                        display: block;
                        width: 30px;
                        margin-left: 36px;
                    }

                    p {
                        font-size: 13px;
                        text-align: center;
                        line-height: 1.5;
                        color: #333333;

                        @include media-query-tablet-portrait-up {
                            font-size: 16px;
                        }

                        @include media-query-desktop-up {
                            font-size: 18px;
                        }

                        @include media-query-medium-desktop-up {
                            left: -18%;
                            font-size: 21px;
                        }
                    }
                }
            }
        }
    }
}

#header {
    position: relative;
    width: 100%;
    height: 100%;
    height: 100vh;
    min-height: 400px;
    display: flex;
    align-items: center;
    justify-content: center;
    background-color: $primary-color;
    padding: 0 10px;

    .couple-background {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background-image: url("./assets/images/header.png");
        background-size: cover;
        background-position: top center;
        background-repeat: no-repeat;
        // opacity: 0.48;
        mix-blend-mode: overlay;

        @include media-query-mobile {
            background-image: url("./assets/images/header-mobile.png");
        }
    }

    .title-box {
        position: relative;
        width: 100%;
        max-width: 720px;
        margin: 0 auto;
        background-color: $tertiary-color;
        text-align: center;
        padding: 17px;
        margin-top: 7%;

        @include media-query-medium-desktop-up {
            margin-top: 4%;
        }

        .inner {
            border: 4px solid $secondary-color;
            border-radius: 15px;
            padding: 30px 15px;

            @include media-query-medium-desktop-up {
                padding: 50px 15px;
            }

            h1 {
                margin-bottom: 15px;

                @include media-query-tablet-portrait-up {
                    margin-bottom: 4px;
                }
            }

            h3 {
                position: relative;
                color: $secondary-color;

                span {
                    position: relative;
                    padding: 0 14px;
                    background-color: $tertiary-color;
                    z-index: 1;
                }

                &:before {
                    content: "";
                    display: block;
                    position: absolute;
                    top: 50%;
                    left: 50%;
                    width: 82%;
                    height: 4px;
                    transform: translate3d(-50%, -50%, 0);
                    background-color: $primary-color;
                }
            }

            .date-wrapper {
                display: flex;
                justify-content: center;
                margin-top: 40px;

                h3 {
                    &.date {
                        color: $black-color;

                        &:before {
                            content: none;
                        }
                    }
                }

                img {
                    width: 18px;
                    align-self: center;
                    margin-right: 10px;

                    &:last-child {
                        margin-right: 0;
                        margin-left: 10px;
                        transform: scaleX(-1);
                    }
                }
            }
        }

        img#lego-1,
        img#lego-2 {
            display: block;
            position: absolute;
            top: 6%;
            left: 0;
            width: 21%;

            @include media-query-tablet-portrait-up {
                left: -14%;
            }
        }

        img#lego-2 {
            left: initial;
            right: 0;
            top: initial;
            bottom: 9%;
            transform: rotateZ(-18deg);
            width: 16%;

            @include media-query-tablet-portrait-up {
                right: -8%;
            }
        }
    }
}
</style>
