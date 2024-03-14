@charset "UTF-8";
@import url(https://fonts.googleapis.com/css?family=Raleway:300,400,600);
.icheckbox_square-blue,
.iradio_square-blue {
    background: url(../images/vendor/icheck/skins/square/blue.png?47dfe954bc521a5356050b61b12c0cd0) no-repeat;
    border: none;
    cursor: pointer;
    display: inline-block;
    height: 22px;
    margin: 0;
    padding: 0;
    vertical-align: middle;
    width: 22px
}

.icheckbox_square-blue {
    background-position: 0 0
}

.icheckbox_square-blue.hover {
    background-position: -24px 0
}

.icheckbox_square-blue.checked {
    background-position: -48px 0
}

.icheckbox_square-blue.disabled {
    background-position: -72px 0;
    cursor: default
}

.icheckbox_square-blue.checked.disabled {
    background-position: -96px 0
}

.iradio_square-blue {
    background-position: -120px 0
}

.iradio_square-blue.hover {
    background-position: -144px 0
}

.iradio_square-blue.checked {
    background-position: -168px 0
}

.iradio_square-blue.disabled {
    background-position: -192px 0;
    cursor: default
}

.iradio_square-blue.checked.disabled {
    background-position: -216px 0
}

@media (-webkit-min-device-pixel-ratio:1.25),
(min-resolution:120dpi) {
    .icheckbox_square-blue,
    .iradio_square-blue {
        background-image: url(../images/vendor/icheck/skins/square/blue@2x.png?eb5592d094a6555c844bc1ba04c7259e);
        background-size: 240px 24px
    }
}

/*!
 * Ladda
 * http://lab.hakim.se/ladda
 * MIT licensed
 *
 * Copyright (C) 2018 Hakim El Hattab, http://hakim.se
 */

@keyframes ladda-spinner-line-fade {
    0%,
    to {
        opacity: .22
    }
    1% {
        opacity: 1
    }
}

.ladda-button {
    position: relative
}

.ladda-button .ladda-spinner {
    display: inline-block;
    margin-top: 0;
    opacity: 0;
    pointer-events: none;
    position: absolute;
    top: 50%;
    width: 32px;
    z-index: 2
}

.ladda-button .ladda-label {
    position: relative;
    z-index: 3
}

.ladda-button .ladda-progress {
    background: rgba(0, 0, 0, .2);
    display: none;
    height: 100%;
    left: 0;
    position: absolute;
    top: 0;
    transition: all .1s linear;
    width: 0
}

.ladda-button[data-loading] .ladda-progress {
    display: block
}

.ladda-button,
.ladda-button .ladda-label,
.ladda-button .ladda-spinner {
    transition: all .3s cubic-bezier(.175, .885, .32, 1.275)
}

.ladda-button[data-style=zoom-in],
.ladda-button[data-style=zoom-in] .ladda-label,
.ladda-button[data-style=zoom-in] .ladda-spinner,
.ladda-button[data-style=zoom-out],
.ladda-button[data-style=zoom-out] .ladda-label,
.ladda-button[data-style=zoom-out] .ladda-spinner {
    transition: all .3s ease
}

.ladda-button[data-style=expand-right] .ladda-spinner {
    right: -6px
}

.ladda-button[data-style=expand-right][data-size=s] .ladda-spinner,
.ladda-button[data-style=expand-right][data-size=xs] .ladda-spinner {
    right: -12px
}

.ladda-button[data-style=expand-right][data-loading] {
    padding-right: 56px
}

.ladda-button[data-style=expand-right][data-loading] .ladda-spinner {
    opacity: 1
}

.ladda-button[data-style=expand-right][data-loading][data-size=s],
.ladda-button[data-style=expand-right][data-loading][data-size=xs] {
    padding-right: 40px
}

.ladda-button[data-style=expand-left] .ladda-spinner {
    left: 26px
}

.ladda-button[data-style=expand-left][data-size=s] .ladda-spinner,
.ladda-button[data-style=expand-left][data-size=xs] .ladda-spinner {
    left: 4px
}

.ladda-button[data-style=expand-left][data-loading] {
    padding-left: 56px
}

.ladda-button[data-style=expand-left][data-loading] .ladda-spinner {
    opacity: 1
}

.ladda-button[data-style=expand-left][data-loading][data-size=s],
.ladda-button[data-style=expand-left][data-loading][data-size=xs] {
    padding-left: 40px
}

.ladda-button[data-style=expand-up] {
    overflow: hidden
}

.ladda-button[data-style=expand-up] .ladda-spinner {
    left: 50%;
    margin-left: 0;
    top: -32px
}

.ladda-button[data-style=expand-up][data-loading] {
    padding-top: 54px
}

.ladda-button[data-style=expand-up][data-loading] .ladda-spinner {
    margin-top: 0;
    opacity: 1;
    top: 26px
}

.ladda-button[data-style=expand-up][data-loading][data-size=s],
.ladda-button[data-style=expand-up][data-loading][data-size=xs] {
    padding-top: 32px
}

.ladda-button[data-style=expand-up][data-loading][data-size=s] .ladda-spinner,
.ladda-button[data-style=expand-up][data-loading][data-size=xs] .ladda-spinner {
    top: 4px
}

.ladda-button[data-style=expand-down] {
    overflow: hidden
}

.ladda-button[data-style=expand-down] .ladda-spinner {
    left: 50%;
    margin-left: 0;
    top: 62px
}

.ladda-button[data-style=expand-down][data-size=s] .ladda-spinner,
.ladda-button[data-style=expand-down][data-size=xs] .ladda-spinner {
    top: 40px
}

.ladda-button[data-style=expand-down][data-loading] {
    padding-bottom: 54px
}

.ladda-button[data-style=expand-down][data-loading] .ladda-spinner {
    opacity: 1
}

.ladda-button[data-style=expand-down][data-loading][data-size=s],
.ladda-button[data-style=expand-down][data-loading][data-size=xs] {
    padding-bottom: 32px
}

.ladda-button[data-style=slide-left] {
    overflow: hidden
}

.ladda-button[data-style=slide-left] .ladda-label {
    position: relative
}

.ladda-button[data-style=slide-left] .ladda-spinner {
    left: 100%;
    margin-left: 0
}

.ladda-button[data-style=slide-left][data-loading] .ladda-label {
    left: -100%;
    opacity: 0
}

.ladda-button[data-style=slide-left][data-loading] .ladda-spinner {
    left: 50%;
    opacity: 1
}

.ladda-button[data-style=slide-right] {
    overflow: hidden
}

.ladda-button[data-style=slide-right] .ladda-label {
    position: relative
}

.ladda-button[data-style=slide-right] .ladda-spinner {
    left: 16px;
    margin-left: 0;
    right: 100%
}

[dir=rtl] .ladda-button[data-style=slide-right] .ladda-spinner {
    right: auto
}

.ladda-button[data-style=slide-right][data-loading] .ladda-label {
    left: 100%;
    opacity: 0
}

.ladda-button[data-style=slide-right][data-loading] .ladda-spinner {
    left: 50%;
    opacity: 1
}

.ladda-button[data-style=slide-up] {
    overflow: hidden
}

.ladda-button[data-style=slide-up] .ladda-label {
    position: relative
}

.ladda-button[data-style=slide-up] .ladda-spinner {
    left: 50%;
    margin-left: 0;
    margin-top: 1em
}

.ladda-button[data-style=slide-up][data-loading] .ladda-label {
    opacity: 0;
    top: -1em
}

.ladda-button[data-style=slide-up][data-loading] .ladda-spinner {
    margin-top: 0;
    opacity: 1
}

.ladda-button[data-style=slide-down] {
    overflow: hidden
}

.ladda-button[data-style=slide-down] .ladda-label {
    position: relative
}

.ladda-button[data-style=slide-down] .ladda-spinner {
    left: 50%;
    margin-left: 0;
    margin-top: -2em
}

.ladda-button[data-style=slide-down][data-loading] .ladda-label {
    opacity: 0;
    top: 1em
}

.ladda-button[data-style=slide-down][data-loading] .ladda-spinner {
    margin-top: 0;
    opacity: 1
}

.ladda-button[data-style=zoom-out] {
    overflow: hidden
}

.ladda-button[data-style=zoom-out] .ladda-label {
    display: inline-block;
    position: relative
}

.ladda-button[data-style=zoom-out] .ladda-spinner {
    left: 50%;
    margin-left: 32px;
    transform: scale(2.5)
}

.ladda-button[data-style=zoom-out][data-loading] .ladda-label {
    opacity: 0;
    transform: scale(.5)
}

.ladda-button[data-style=zoom-out][data-loading] .ladda-spinner {
    margin-left: 0;
    opacity: 1;
    transform: none
}

.ladda-button[data-style=zoom-in] {
    overflow: hidden
}

.ladda-button[data-style=zoom-in] .ladda-label {
    display: inline-block;
    position: relative
}

.ladda-button[data-style=zoom-in] .ladda-spinner {
    left: 50%;
    margin-left: -16px;
    transform: scale(.2)
}

.ladda-button[data-style=zoom-in][data-loading] .ladda-label {
    opacity: 0;
    transform: scale(2.2)
}

.ladda-button[data-style=zoom-in][data-loading] .ladda-spinner {
    margin-left: 0;
    opacity: 1;
    transform: none
}

.ladda-button[data-style=contract] {
    overflow: hidden;
    width: 100px
}

.ladda-button[data-style=contract] .ladda-spinner {
    left: 50%;
    margin-left: 0
}

.ladda-button[data-style=contract][data-loading] {
    border-radius: 50%;
    width: 52px
}

.ladda-button[data-style=contract][data-loading] .ladda-label {
    opacity: 0
}

.ladda-button[data-style=contract][data-loading] .ladda-spinner {
    opacity: 1
}

.ladda-button[data-style=contract-overlay] {
    box-shadow: 0 0 0 2000px transparent;
    overflow: hidden;
    width: 100px
}

.ladda-button[data-style=contract-overlay] .ladda-spinner {
    left: 50%;
    margin-left: 0
}

.ladda-button[data-style=contract-overlay][data-loading] {
    border-radius: 50%;
    box-shadow: 0 0 0 2000px rgba(0, 0, 0, .8);
    width: 52px
}

.ladda-button[data-style=contract-overlay][data-loading] .ladda-label {
    opacity: 0
}

.ladda-button[data-style=contract-overlay][data-loading] .ladda-spinner {
    opacity: 1
}

[dir=rtl] .ladda-spinner>div {
    left: 25% !important
}

/*!
 * Font Awesome Free 5.15.4 by @fontawesome - https://fontawesome.com
 * License - https://fontawesome.com/license/free (Icons: CC BY 4.0, Fonts: SIL OFL 1.1, Code: MIT License)
 */

.fa,
.fab,
.fad,
.fal,
.far,
.fas {
    -moz-osx-font-smoothing: grayscale;
    -webkit-font-smoothing: antialiased;
    display: inline-block;
    font-style: normal;
    font-variant: normal;
    line-height: 1;
    text-rendering: auto
}

.fa-lg {
    font-size: 1.3333333333em;
    line-height: .75em;
    vertical-align: -.0667em
}

.fa-xs {
    font-size: .75em
}

.fa-sm {
    font-size: .875em
}

.fa-1x {
    font-size: 1em
}

.fa-2x {
    font-size: 2em
}

.fa-3x {
    font-size: 3em
}

.fa-4x {
    font-size: 4em
}

.fa-5x {
    font-size: 5em
}

.fa-6x {
    font-size: 6em
}

.fa-7x {
    font-size: 7em
}

.fa-8x {
    font-size: 8em
}

.fa-9x {
    font-size: 9em
}

.fa-10x {
    font-size: 10em
}

.fa-fw {
    text-align: center;
    width: 1.25em
}

.fa-ul {
    list-style-type: none;
    margin-left: 2.5em;
    padding-left: 0
}

.fa-ul>li {
    position: relative
}

.fa-li {
    left: -2em;
    line-height: inherit;
    position: absolute;
    text-align: center;
    width: 2em
}

.fa-border {
    border: .08em solid #eee;
    border-radius: .1em;
    padding: .2em .25em .15em
}

.fa-pull-left {
    float: left
}

.fa-pull-right {
    float: right
}

.fa.fa-pull-left,
.fab.fa-pull-left,
.fal.fa-pull-left,
.far.fa-pull-left,
.fas.fa-pull-left {
    margin-right: .3em
}

.fa.fa-pull-right,
.fab.fa-pull-right,
.fal.fa-pull-right,
.far.fa-pull-right,
.fas.fa-pull-right {
    margin-left: .3em
}

.fa-spin {
    animation: fa-spin 2s linear infinite
}

.fa-pulse {
    animation: fa-spin 1s steps(8) infinite
}

@keyframes fa-spin {
    0% {
        transform: rotate(0)
    }
    to {
        transform: rotate(1turn)
    }
}

.fa-rotate-90 {
    transform: rotate(90deg)
}

.fa-rotate-180 {
    transform: rotate(180deg)
}

.fa-rotate-270 {
    transform: rotate(270deg)
}

.fa-flip-horizontal {
    transform: scaleX(-1)
}

.fa-flip-vertical {
    transform: scaleY(-1)
}

.fa-flip-both,
.fa-flip-horizontal.fa-flip-vertical {
    transform: scale(-1)
}

:root .fa-flip-both,
:root .fa-flip-horizontal,
:root .fa-flip-vertical,
:root .fa-rotate-180,
:root .fa-rotate-270,
:root .fa-rotate-90 {
    filter: none
}

.fa-stack {
    display: inline-block;
    height: 2em;
    line-height: 2em;
    position: relative;
    vertical-align: middle;
    width: 2.5em
}

.fa-stack-1x,
.fa-stack-2x {
    left: 0;
    position: absolute;
    text-align: center;
    width: 100%
}

.fa-stack-1x {
    line-height: inherit
}

.fa-stack-2x {
    font-size: 2em
}

.fa-inverse {
    color: #fff
}

.fa-500px:before {
    content: "\f26e"
}

.fa-accessible-icon:before {
    content: "\f368"
}

.fa-accusoft:before {
    content: "\f369"
}

.fa-acquisitions-incorporated:before {
    content: "\f6af"
}

.fa-ad:before {
    content: "\f641"
}

.fa-address-book:before {
    content: "\f2b9"
}

.fa-address-card:before {
    content: "\f2bb"
}

.fa-adjust:before {
    content: "\f042"
}

.fa-adn:before {
    content: "\f170"
}

.fa-adversal:before {
    content: "\f36a"
}

.fa-affiliatetheme:before {
    content: "\f36b"
}

.fa-air-freshener:before {
    content: "\f5d0"
}

.fa-airbnb:before {
    content: "\f834"
}

.fa-algolia:before {
    content: "\f36c"
}

.fa-align-center:before {
    content: "\f037"
}

.fa-align-justify:before {
    content: "\f039"
}

.fa-align-left:before {
    content: "\f036"
}

.fa-align-right:before {
    content: "\f038"
}

.fa-alipay:before {
    content: "\f642"
}

.fa-allergies:before {
    content: "\f461"
}

.fa-amazon:before {
    content: "\f270"
}

.fa-amazon-pay:before {
    content: "\f42c"
}

.fa-ambulance:before {
    content: "\f0f9"
}

.fa-american-sign-language-interpreting:before {
    content: "\f2a3"
}

.fa-amilia:before {
    content: "\f36d"
}

.fa-anchor:before {
    content: "\f13d"
}

.fa-android:before {
    content: "\f17b"
}

.fa-angellist:before {
    content: "\f209"
}

.fa-angle-double-down:before {
    content: "\f103"
}

.fa-angle-double-left:before {
    content: "\f100"
}

.fa-angle-double-right:before {
    content: "\f101"
}

.fa-angle-double-up:before {
    content: "\f102"
}

.fa-angle-down:before {
    content: "\f107"
}

.fa-angle-left:before {
    content: "\f104"
}

.fa-angle-right:before {
    content: "\f105"
}

.fa-angle-up:before {
    content: "\f106"
}

.fa-angry:before {
    content: "\f556"
}

.fa-angrycreative:before {
    content: "\f36e"
}

.fa-angular:before {
    content: "\f420"
}

.fa-ankh:before {
    content: "\f644"
}

.fa-app-store:before {
    content: "\f36f"
}

.fa-app-store-ios:before {
    content: "\f370"
}

.fa-apper:before {
    content: "\f371"
}

.fa-apple:before {
    content: "\f179"
}

.fa-apple-alt:before {
    content: "\f5d1"
}

.fa-apple-pay:before {
    content: "\f415"
}

.fa-archive:before {
    content: "\f187"
}

.fa-archway:before {
    content: "\f557"
}

.fa-arrow-alt-circle-down:before {
    content: "\f358"
}

.fa-arrow-alt-circle-left:before {
    content: "\f359"
}

.fa-arrow-alt-circle-right:before {
    content: "\f35a"
}

.fa-arrow-alt-circle-up:before {
    content: "\f35b"
}

.fa-arrow-circle-down:before {
    content: "\f0ab"
}

.fa-arrow-circle-left:before {
    content: "\f0a8"
}

.fa-arrow-circle-right:before {
    content: "\f0a9"
}

.fa-arrow-circle-up:before {
    content: "\f0aa"
}

.fa-arrow-down:before {
    content: "\f063"
}

.fa-arrow-left:before {
    content: "\f060"
}

.fa-arrow-right:before {
    content: "\f061"
}

.fa-arrow-up:before {
    content: "\f062"
}

.fa-arrows-alt:before {
    content: "\f0b2"
}

.fa-arrows-alt-h:before {
    content: "\f337"
}

.fa-arrows-alt-v:before {
    content: "\f338"
}

.fa-artstation:before {
    content: "\f77a"
}

.fa-assistive-listening-systems:before {
    content: "\f2a2"
}

.fa-asterisk:before {
    content: "\f069"
}

.fa-asymmetrik:before {
    content: "\f372"
}

.fa-at:before {
    content: "\f1fa"
}

.fa-atlas:before {
    content: "\f558"
}

.fa-atlassian:before {
    content: "\f77b"
}

.fa-atom:before {
    content: "\f5d2"
}

.fa-audible:before {
    content: "\f373"
}

.fa-audio-description:before {
    content: "\f29e"
}

.fa-autoprefixer:before {
    content: "\f41c"
}

.fa-avianex:before {
    content: "\f374"
}

.fa-aviato:before {
    content: "\f421"
}

.fa-award:before {
    content: "\f559"
}

.fa-aws:before {
    content: "\f375"
}

.fa-baby:before {
    content: "\f77c"
}

.fa-baby-carriage:before {
    content: "\f77d"
}

.fa-backspace:before {
    content: "\f55a"
}

.fa-backward:before {
    content: "\f04a"
}

.fa-bacon:before {
    content: "\f7e5"
}

.fa-bacteria:before {
    content: "\e059"
}

.fa-bacterium:before {
    content: "\e05a"
}

.fa-bahai:before {
    content: "\f666"
}

.fa-balance-scale:before {
    content: "\f24e"
}

.fa-balance-scale-left:before {
    content: "\f515"
}

.fa-balance-scale-right:before {
    content: "\f516"
}

.fa-ban:before {
    content: "\f05e"
}

.fa-band-aid:before {
    content: "\f462"
}

.fa-bandcamp:before {
    content: "\f2d5"
}

.fa-barcode:before {
    content: "\f02a"
}

.fa-bars:before {
    content: "\f0c9"
}

.fa-baseball-ball:before {
    content: "\f433"
}

.fa-basketball-ball:before {
    content: "\f434"
}

.fa-bath:before {
    content: "\f2cd"
}

.fa-battery-empty:before {
    content: "\f244"
}

.fa-battery-full:before {
    content: "\f240"
}

.fa-battery-half:before {
    content: "\f242"
}

.fa-battery-quarter:before {
    content: "\f243"
}

.fa-battery-three-quarters:before {
    content: "\f241"
}

.fa-battle-net:before {
    content: "\f835"
}

.fa-bed:before {
    content: "\f236"
}

.fa-beer:before {
    content: "\f0fc"
}

.fa-behance:before {
    content: "\f1b4"
}

.fa-behance-square:before {
    content: "\f1b5"
}

.fa-bell:before {
    content: "\f0f3"
}

.fa-bell-slash:before {
    content: "\f1f6"
}

.fa-bezier-curve:before {
    content: "\f55b"
}

.fa-bible:before {
    content: "\f647"
}

.fa-bicycle:before {
    content: "\f206"
}

.fa-biking:before {
    content: "\f84a"
}

.fa-bimobject:before {
    content: "\f378"
}

.fa-binoculars:before {
    content: "\f1e5"
}

.fa-biohazard:before {
    content: "\f780"
}

.fa-birthday-cake:before {
    content: "\f1fd"
}

.fa-bitbucket:before {
    content: "\f171"
}

.fa-bitcoin:before {
    content: "\f379"
}

.fa-bity:before {
    content: "\f37a"
}

.fa-black-tie:before {
    content: "\f27e"
}

.fa-blackberry:before {
    content: "\f37b"
}

.fa-blender:before {
    content: "\f517"
}

.fa-blender-phone:before {
    content: "\f6b6"
}

.fa-blind:before {
    content: "\f29d"
}

.fa-blog:before {
    content: "\f781"
}

.fa-blogger:before {
    content: "\f37c"
}

.fa-blogger-b:before {
    content: "\f37d"
}

.fa-bluetooth:before {
    content: "\f293"
}

.fa-bluetooth-b:before {
    content: "\f294"
}

.fa-bold:before {
    content: "\f032"
}

.fa-bolt:before {
    content: "\f0e7"
}

.fa-bomb:before {
    content: "\f1e2"
}

.fa-bone:before {
    content: "\f5d7"
}

.fa-bong:before {
    content: "\f55c"
}

.fa-book:before {
    content: "\f02d"
}

.fa-book-dead:before {
    content: "\f6b7"
}

.fa-book-medical:before {
    content: "\f7e6"
}

.fa-book-open:before {
    content: "\f518"
}

.fa-book-reader:before {
    content: "\f5da"
}

.fa-bookmark:before {
    content: "\f02e"
}

.fa-bootstrap:before {
    content: "\f836"
}

.fa-border-all:before {
    content: "\f84c"
}

.fa-border-none:before {
    content: "\f850"
}

.fa-border-style:before {
    content: "\f853"
}

.fa-bowling-ball:before {
    content: "\f436"
}

.fa-box:before {
    content: "\f466"
}

.fa-box-open:before {
    content: "\f49e"
}

.fa-box-tissue:before {
    content: "\e05b"
}

.fa-boxes:before {
    content: "\f468"
}

.fa-braille:before {
    content: "\f2a1"
}

.fa-brain:before {
    content: "\f5dc"
}

.fa-bread-slice:before {
    content: "\f7ec"
}

.fa-briefcase:before {
    content: "\f0b1"
}

.fa-briefcase-medical:before {
    content: "\f469"
}

.fa-broadcast-tower:before {
    content: "\f519"
}

.fa-broom:before {
    content: "\f51a"
}

.fa-brush:before {
    content: "\f55d"
}

.fa-btc:before {
    content: "\f15a"
}

.fa-buffer:before {
    content: "\f837"
}

.fa-bug:before {
    content: "\f188"
}

.fa-building:before {
    content: "\f1ad"
}

.fa-bullhorn:before {
    content: "\f0a1"
}

.fa-bullseye:before {
    content: "\f140"
}

.fa-burn:before {
    content: "\f46a"
}

.fa-buromobelexperte:before {
    content: "\f37f"
}

.fa-bus:before {
    content: "\f207"
}

.fa-bus-alt:before {
    content: "\f55e"
}

.fa-business-time:before {
    content: "\f64a"
}

.fa-buy-n-large:before {
    content: "\f8a6"
}

.fa-buysellads:before {
    content: "\f20d"
}

.fa-calculator:before {
    content: "\f1ec"
}

.fa-calendar:before {
    content: "\f133"
}

.fa-calendar-alt:before {
    content: "\f073"
}

.fa-calendar-check:before {
    content: "\f274"
}

.fa-calendar-day:before {
    content: "\f783"
}

.fa-calendar-minus:before {
    content: "\f272"
}

.fa-calendar-plus:before {
    content: "\f271"
}

.fa-calendar-times:before {
    content: "\f273"
}

.fa-calendar-week:before {
    content: "\f784"
}

.fa-camera:before {
    content: "\f030"
}

.fa-camera-retro:before {
    content: "\f083"
}

.fa-campground:before {
    content: "\f6bb"
}

.fa-canadian-maple-leaf:before {
    content: "\f785"
}

.fa-candy-cane:before {
    content: "\f786"
}

.fa-cannabis:before {
    content: "\f55f"
}

.fa-capsules:before {
    content: "\f46b"
}

.fa-car:before {
    content: "\f1b9"
}

.fa-car-alt:before {
    content: "\f5de"
}

.fa-car-battery:before {
    content: "\f5df"
}

.fa-car-crash:before {
    content: "\f5e1"
}

.fa-car-side:before {
    content: "\f5e4"
}

.fa-caravan:before {
    content: "\f8ff"
}

.fa-caret-down:before {
    content: "\f0d7"
}

.fa-caret-left:before {
    content: "\f0d9"
}

.fa-caret-right:before {
    content: "\f0da"
}

.fa-caret-square-down:before {
    content: "\f150"
}

.fa-caret-square-left:before {
    content: "\f191"
}

.fa-caret-square-right:before {
    content: "\f152"
}

.fa-caret-square-up:before {
    content: "\f151"
}

.fa-caret-up:before {
    content: "\f0d8"
}

.fa-carrot:before {
    content: "\f787"
}

.fa-cart-arrow-down:before {
    content: "\f218"
}

.fa-cart-plus:before {
    content: "\f217"
}

.fa-cash-register:before {
    content: "\f788"
}

.fa-cat:before {
    content: "\f6be"
}

.fa-cc-amazon-pay:before {
    content: "\f42d"
}

.fa-cc-amex:before {
    content: "\f1f3"
}

.fa-cc-apple-pay:before {
    content: "\f416"
}

.fa-cc-diners-club:before {
    content: "\f24c"
}

.fa-cc-discover:before {
    content: "\f1f2"
}

.fa-cc-jcb:before {
    content: "\f24b"
}

.fa-cc-mastercard:before {
    content: "\f1f1"
}

.fa-cc-paypal:before {
    content: "\f1f4"
}

.fa-cc-stripe:before {
    content: "\f1f5"
}

.fa-cc-visa:before {
    content: "\f1f0"
}

.fa-centercode:before {
    content: "\f380"
}

.fa-centos:before {
    content: "\f789"
}

.fa-certificate:before {
    content: "\f0a3"
}

.fa-chair:before {
    content: "\f6c0"
}

.fa-chalkboard:before {
    content: "\f51b"
}

.fa-chalkboard-teacher:before {
    content: "\f51c"
}

.fa-charging-station:before {
    content: "\f5e7"
}

.fa-chart-area:before {
    content: "\f1fe"
}

.fa-chart-bar:before {
    content: "\f080"
}

.fa-chart-line:before {
    content: "\f201"
}

.fa-chart-pie:before {
    content: "\f200"
}

.fa-check:before {
    content: "\f00c"
}

.fa-check-circle:before {
    content: "\f058"
}

.fa-check-double:before {
    content: "\f560"
}

.fa-check-square:before {
    content: "\f14a"
}

.fa-cheese:before {
    content: "\f7ef"
}

.fa-chess:before {
    content: "\f439"
}

.fa-chess-bishop:before {
    content: "\f43a"
}

.fa-chess-board:before {
    content: "\f43c"
}

.fa-chess-king:before {
    content: "\f43f"
}

.fa-chess-knight:before {
    content: "\f441"
}

.fa-chess-pawn:before {
    content: "\f443"
}

.fa-chess-queen:before {
    content: "\f445"
}

.fa-chess-rook:before {
    content: "\f447"
}

.fa-chevron-circle-down:before {
    content: "\f13a"
}

.fa-chevron-circle-left:before {
    content: "\f137"
}

.fa-chevron-circle-right:before {
    content: "\f138"
}

.fa-chevron-circle-up:before {
    content: "\f139"
}

.fa-chevron-down:before {
    content: "\f078"
}

.fa-chevron-left:before {
    content: "\f053"
}

.fa-chevron-right:before {
    content: "\f054"
}

.fa-chevron-up:before {
    content: "\f077"
}

.fa-child:before {
    content: "\f1ae"
}

.fa-chrome:before {
    content: "\f268"
}

.fa-chromecast:before {
    content: "\f838"
}

.fa-church:before {
    content: "\f51d"
}

.fa-circle:before {
    content: "\f111"
}

.fa-circle-notch:before {
    content: "\f1ce"
}

.fa-city:before {
    content: "\f64f"
}

.fa-clinic-medical:before {
    content: "\f7f2"
}

.fa-clipboard:before {
    content: "\f328"
}

.fa-clipboard-check:before {
    content: "\f46c"
}

.fa-clipboard-list:before {
    content: "\f46d"
}

.fa-clock:before {
    content: "\f017"
}

.fa-clone:before {
    content: "\f24d"
}

.fa-closed-captioning:before {
    content: "\f20a"
}

.fa-cloud:before {
    content: "\f0c2"
}

.fa-cloud-download-alt:before {
    content: "\f381"
}

.fa-cloud-meatball:before {
    content: "\f73b"
}

.fa-cloud-moon:before {
    content: "\f6c3"
}

.fa-cloud-moon-rain:before {
    content: "\f73c"
}

.fa-cloud-rain:before {
    content: "\f73d"
}

.fa-cloud-showers-heavy:before {
    content: "\f740"
}

.fa-cloud-sun:before {
    content: "\f6c4"
}

.fa-cloud-sun-rain:before {
    content: "\f743"
}

.fa-cloud-upload-alt:before {
    content: "\f382"
}

.fa-cloudflare:before {
    content: "\e07d"
}

.fa-cloudscale:before {
    content: "\f383"
}

.fa-cloudsmith:before {
    content: "\f384"
}

.fa-cloudversify:before {
    content: "\f385"
}

.fa-cocktail:before {
    content: "\f561"
}

.fa-code:before {
    content: "\f121"
}

.fa-code-branch:before {
    content: "\f126"
}

.fa-codepen:before {
    content: "\f1cb"
}

.fa-codiepie:before {
    content: "\f284"
}

.fa-coffee:before {
    content: "\f0f4"
}

.fa-cog:before {
    content: "\f013"
}

.fa-cogs:before {
    content: "\f085"
}

.fa-coins:before {
    content: "\f51e"
}

.fa-columns:before {
    content: "\f0db"
}

.fa-comment:before {
    content: "\f075"
}

.fa-comment-alt:before {
    content: "\f27a"
}

.fa-comment-dollar:before {
    content: "\f651"
}

.fa-comment-dots:before {
    content: "\f4ad"
}

.fa-comment-medical:before {
    content: "\f7f5"
}

.fa-comment-slash:before {
    content: "\f4b3"
}

.fa-comments:before {
    content: "\f086"
}

.fa-comments-dollar:before {
    content: "\f653"
}

.fa-compact-disc:before {
    content: "\f51f"
}

.fa-compass:before {
    content: "\f14e"
}

.fa-compress:before {
    content: "\f066"
}

.fa-compress-alt:before {
    content: "\f422"
}

.fa-compress-arrows-alt:before {
    content: "\f78c"
}

.fa-concierge-bell:before {
    content: "\f562"
}

.fa-confluence:before {
    content: "\f78d"
}

.fa-connectdevelop:before {
    content: "\f20e"
}

.fa-contao:before {
    content: "\f26d"
}

.fa-cookie:before {
    content: "\f563"
}

.fa-cookie-bite:before {
    content: "\f564"
}

.fa-copy:before {
    content: "\f0c5"
}

.fa-copyright:before {
    content: "\f1f9"
}

.fa-cotton-bureau:before {
    content: "\f89e"
}

.fa-couch:before {
    content: "\f4b8"
}

.fa-cpanel:before {
    content: "\f388"
}

.fa-creative-commons:before {
    content: "\f25e"
}

.fa-creative-commons-by:before {
    content: "\f4e7"
}

.fa-creative-commons-nc:before {
    content: "\f4e8"
}

.fa-creative-commons-nc-eu:before {
    content: "\f4e9"
}

.fa-creative-commons-nc-jp:before {
    content: "\f4ea"
}

.fa-creative-commons-nd:before {
    content: "\f4eb"
}

.fa-creative-commons-pd:before {
    content: "\f4ec"
}

.fa-creative-commons-pd-alt:before {
    content: "\f4ed"
}

.fa-creative-commons-remix:before {
    content: "\f4ee"
}

.fa-creative-commons-sa:before {
    content: "\f4ef"
}

.fa-creative-commons-sampling:before {
    content: "\f4f0"
}

.fa-creative-commons-sampling-plus:before {
    content: "\f4f1"
}

.fa-creative-commons-share:before {
    content: "\f4f2"
}

.fa-creative-commons-zero:before {
    content: "\f4f3"
}

.fa-credit-card:before {
    content: "\f09d"
}

.fa-critical-role:before {
    content: "\f6c9"
}

.fa-crop:before {
    content: "\f125"
}

.fa-crop-alt:before {
    content: "\f565"
}

.fa-cross:before {
    content: "\f654"
}

.fa-crosshairs:before {
    content: "\f05b"
}

.fa-crow:before {
    content: "\f520"
}

.fa-crown:before {
    content: "\f521"
}

.fa-crutch:before {
    content: "\f7f7"
}

.fa-css3:before {
    content: "\f13c"
}

.fa-css3-alt:before {
    content: "\f38b"
}

.fa-cube:before {
    content: "\f1b2"
}

.fa-cubes:before {
    content: "\f1b3"
}

.fa-cut:before {
    content: "\f0c4"
}

.fa-cuttlefish:before {
    content: "\f38c"
}

.fa-d-and-d:before {
    content: "\f38d"
}

.fa-d-and-d-beyond:before {
    content: "\f6ca"
}

.fa-dailymotion:before {
    content: "\e052"
}

.fa-dashcube:before {
    content: "\f210"
}

.fa-database:before {
    content: "\f1c0"
}

.fa-deaf:before {
    content: "\f2a4"
}

.fa-deezer:before {
    content: "\e077"
}

.fa-delicious:before {
    content: "\f1a5"
}

.fa-democrat:before {
    content: "\f747"
}

.fa-deploydog:before {
    content: "\f38e"
}

.fa-deskpro:before {
    content: "\f38f"
}

.fa-desktop:before {
    content: "\f108"
}

.fa-dev:before {
    content: "\f6cc"
}

.fa-deviantart:before {
    content: "\f1bd"
}

.fa-dharmachakra:before {
    content: "\f655"
}

.fa-dhl:before {
    content: "\f790"
}

.fa-diagnoses:before {
    content: "\f470"
}

.fa-diaspora:before {
    content: "\f791"
}

.fa-dice:before {
    content: "\f522"
}

.fa-dice-d20:before {
    content: "\f6cf"
}

.fa-dice-d6:before {
    content: "\f6d1"
}

.fa-dice-five:before {
    content: "\f523"
}

.fa-dice-four:before {
    content: "\f524"
}

.fa-dice-one:before {
    content: "\f525"
}

.fa-dice-six:before {
    content: "\f526"
}

.fa-dice-three:before {
    content: "\f527"
}

.fa-dice-two:before {
    content: "\f528"
}

.fa-digg:before {
    content: "\f1a6"
}

.fa-digital-ocean:before {
    content: "\f391"
}

.fa-digital-tachograph:before {
    content: "\f566"
}

.fa-directions:before {
    content: "\f5eb"
}

.fa-discord:before {
    content: "\f392"
}

.fa-discourse:before {
    content: "\f393"
}

.fa-disease:before {
    content: "\f7fa"
}

.fa-divide:before {
    content: "\f529"
}

.fa-dizzy:before {
    content: "\f567"
}

.fa-dna:before {
    content: "\f471"
}

.fa-dochub:before {
    content: "\f394"
}

.fa-docker:before {
    content: "\f395"
}

.fa-dog:before {
    content: "\f6d3"
}

.fa-dollar-sign:before {
    content: "\f155"
}

.fa-dolly:before {
    content: "\f472"
}

.fa-dolly-flatbed:before {
    content: "\f474"
}

.fa-donate:before {
    content: "\f4b9"
}

.fa-door-closed:before {
    content: "\f52a"
}

.fa-door-open:before {
    content: "\f52b"
}

.fa-dot-circle:before {
    content: "\f192"
}

.fa-dove:before {
    content: "\f4ba"
}

.fa-download:before {
    content: "\f019"
}

.fa-draft2digital:before {
    content: "\f396"
}

.fa-drafting-compass:before {
    content: "\f568"
}

.fa-dragon:before {
    content: "\f6d5"
}

.fa-draw-polygon:before {
    content: "\f5ee"
}

.fa-dribbble:before {
    content: "\f17d"
}

.fa-dribbble-square:before {
    content: "\f397"
}

.fa-dropbox:before {
    content: "\f16b"
}

.fa-drum:before {
    content: "\f569"
}

.fa-drum-steelpan:before {
    content: "\f56a"
}

.fa-drumstick-bite:before {
    content: "\f6d7"
}

.fa-drupal:before {
    content: "\f1a9"
}

.fa-dumbbell:before {
    content: "\f44b"
}

.fa-dumpster:before {
    content: "\f793"
}

.fa-dumpster-fire:before {
    content: "\f794"
}

.fa-dungeon:before {
    content: "\f6d9"
}

.fa-dyalog:before {
    content: "\f399"
}

.fa-earlybirds:before {
    content: "\f39a"
}

.fa-ebay:before {
    content: "\f4f4"
}

.fa-edge:before {
    content: "\f282"
}

.fa-edge-legacy:before {
    content: "\e078"
}

.fa-edit:before {
    content: "\f044"
}

.fa-egg:before {
    content: "\f7fb"
}

.fa-eject:before {
    content: "\f052"
}

.fa-elementor:before {
    content: "\f430"
}

.fa-ellipsis-h:before {
    content: "\f141"
}

.fa-ellipsis-v:before {
    content: "\f142"
}

.fa-ello:before {
    content: "\f5f1"
}

.fa-ember:before {
    content: "\f423"
}

.fa-empire:before {
    content: "\f1d1"
}

.fa-envelope:before {
    content: "\f0e0"
}

.fa-envelope-open:before {
    content: "\f2b6"
}

.fa-envelope-open-text:before {
    content: "\f658"
}

.fa-envelope-square:before {
    content: "\f199"
}

.fa-envira:before {
    content: "\f299"
}

.fa-equals:before {
    content: "\f52c"
}

.fa-eraser:before {
    content: "\f12d"
}

.fa-erlang:before {
    content: "\f39d"
}

.fa-ethereum:before {
    content: "\f42e"
}

.fa-ethernet:before {
    content: "\f796"
}

.fa-etsy:before {
    content: "\f2d7"
}

.fa-euro-sign:before {
    content: "\f153"
}

.fa-evernote:before {
    content: "\f839"
}

.fa-exchange-alt:before {
    content: "\f362"
}

.fa-exclamation:before {
    content: "\f12a"
}

.fa-exclamation-circle:before {
    content: "\f06a"
}

.fa-exclamation-triangle:before {
    content: "\f071"
}

.fa-expand:before {
    content: "\f065"
}

.fa-expand-alt:before {
    content: "\f424"
}

.fa-expand-arrows-alt:before {
    content: "\f31e"
}

.fa-expeditedssl:before {
    content: "\f23e"
}

.fa-external-link-alt:before {
    content: "\f35d"
}

.fa-external-link-square-alt:before {
    content: "\f360"
}

.fa-eye:before {
    content: "\f06e"
}

.fa-eye-dropper:before {
    content: "\f1fb"
}

.fa-eye-slash:before {
    content: "\f070"
}

.fa-facebook:before {
    content: "\f09a"
}

.fa-facebook-f:before {
    content: "\f39e"
}

.fa-facebook-messenger:before {
    content: "\f39f"
}

.fa-facebook-square:before {
    content: "\f082"
}

.fa-fan:before {
    content: "\f863"
}

.fa-fantasy-flight-games:before {
    content: "\f6dc"
}

.fa-fast-backward:before {
    content: "\f049"
}

.fa-fast-forward:before {
    content: "\f050"
}

.fa-faucet:before {
    content: "\e005"
}

.fa-fax:before {
    content: "\f1ac"
}

.fa-feather:before {
    content: "\f52d"
}

.fa-feather-alt:before {
    content: "\f56b"
}

.fa-fedex:before {
    content: "\f797"
}

.fa-fedora:before {
    content: "\f798"
}

.fa-female:before {
    content: "\f182"
}

.fa-fighter-jet:before {
    content: "\f0fb"
}

.fa-figma:before {
    content: "\f799"
}

.fa-file:before {
    content: "\f15b"
}

.fa-file-alt:before {
    content: "\f15c"
}

.fa-file-archive:before {
    content: "\f1c6"
}

.fa-file-audio:before {
    content: "\f1c7"
}

.fa-file-code:before {
    content: "\f1c9"
}

.fa-file-contract:before {
    content: "\f56c"
}

.fa-file-csv:before {
    content: "\f6dd"
}

.fa-file-download:before {
    content: "\f56d"
}

.fa-file-excel:before {
    content: "\f1c3"
}

.fa-file-export:before {
    content: "\f56e"
}

.fa-file-image:before {
    content: "\f1c5"
}

.fa-file-import:before {
    content: "\f56f"
}

.fa-file-invoice:before {
    content: "\f570"
}

.fa-file-invoice-dollar:before {
    content: "\f571"
}

.fa-file-medical:before {
    content: "\f477"
}

.fa-file-medical-alt:before {
    content: "\f478"
}

.fa-file-pdf:before {
    content: "\f1c1"
}

.fa-file-powerpoint:before {
    content: "\f1c4"
}

.fa-file-prescription:before {
    content: "\f572"
}

.fa-file-signature:before {
    content: "\f573"
}

.fa-file-upload:before {
    content: "\f574"
}

.fa-file-video:before {
    content: "\f1c8"
}

.fa-file-word:before {
    content: "\f1c2"
}

.fa-fill:before {
    content: "\f575"
}

.fa-fill-drip:before {
    content: "\f576"
}

.fa-film:before {
    content: "\f008"
}

.fa-filter:before {
    content: "\f0b0"
}

.fa-fingerprint:before {
    content: "\f577"
}

.fa-fire:before {
    content: "\f06d"
}

.fa-fire-alt:before {
    content: "\f7e4"
}

.fa-fire-extinguisher:before {
    content: "\f134"
}

.fa-firefox:before {
    content: "\f269"
}

.fa-firefox-browser:before {
    content: "\e007"
}

.fa-first-aid:before {
    content: "\f479"
}

.fa-first-order:before {
    content: "\f2b0"
}

.fa-first-order-alt:before {
    content: "\f50a"
}

.fa-firstdraft:before {
    content: "\f3a1"
}

.fa-fish:before {
    content: "\f578"
}

.fa-fist-raised:before {
    content: "\f6de"
}

.fa-flag:before {
    content: "\f024"
}

.fa-flag-checkered:before {
    content: "\f11e"
}

.fa-flag-usa:before {
    content: "\f74d"
}

.fa-flask:before {
    content: "\f0c3"
}

.fa-flickr:before {
    content: "\f16e"
}

.fa-flipboard:before {
    content: "\f44d"
}

.fa-flushed:before {
    content: "\f579"
}

.fa-fly:before {
    content: "\f417"
}

.fa-folder:before {
    content: "\f07b"
}

.fa-folder-minus:before {
    content: "\f65d"
}

.fa-folder-open:before {
    content: "\f07c"
}

.fa-folder-plus:before {
    content: "\f65e"
}

.fa-font:before {
    content: "\f031"
}

.fa-font-awesome:before {
    content: "\f2b4"
}

.fa-font-awesome-alt:before {
    content: "\f35c"
}

.fa-font-awesome-flag:before {
    content: "\f425"
}

.fa-font-awesome-logo-full:before {
    content: "\f4e6"
}

.fa-fonticons:before {
    content: "\f280"
}

.fa-fonticons-fi:before {
    content: "\f3a2"
}

.fa-football-ball:before {
    content: "\f44e"
}

.fa-fort-awesome:before {
    content: "\f286"
}

.fa-fort-awesome-alt:before {
    content: "\f3a3"
}

.fa-forumbee:before {
    content: "\f211"
}

.fa-forward:before {
    content: "\f04e"
}

.fa-foursquare:before {
    content: "\f180"
}

.fa-free-code-camp:before {
    content: "\f2c5"
}

.fa-freebsd:before {
    content: "\f3a4"
}

.fa-frog:before {
    content: "\f52e"
}

.fa-frown:before {
    content: "\f119"
}

.fa-frown-open:before {
    content: "\f57a"
}

.fa-fulcrum:before {
    content: "\f50b"
}

.fa-funnel-dollar:before {
    content: "\f662"
}

.fa-futbol:before {
    content: "\f1e3"
}

.fa-galactic-republic:before {
    content: "\f50c"
}

.fa-galactic-senate:before {
    content: "\f50d"
}

.fa-gamepad:before {
    content: "\f11b"
}

.fa-gas-pump:before {
    content: "\f52f"
}

.fa-gavel:before {
    content: "\f0e3"
}

.fa-gem:before {
    content: "\f3a5"
}

.fa-genderless:before {
    content: "\f22d"
}

.fa-get-pocket:before {
    content: "\f265"
}

.fa-gg:before {
    content: "\f260"
}

.fa-gg-circle:before {
    content: "\f261"
}

.fa-ghost:before {
    content: "\f6e2"
}

.fa-gift:before {
    content: "\f06b"
}

.fa-gifts:before {
    content: "\f79c"
}

.fa-git:before {
    content: "\f1d3"
}

.fa-git-alt:before {
    content: "\f841"
}

.fa-git-square:before {
    content: "\f1d2"
}

.fa-github:before {
    content: "\f09b"
}

.fa-github-alt:before {
    content: "\f113"
}

.fa-github-square:before {
    content: "\f092"
}

.fa-gitkraken:before {
    content: "\f3a6"
}

.fa-gitlab:before {
    content: "\f296"
}

.fa-gitter:before {
    content: "\f426"
}

.fa-glass-cheers:before {
    content: "\f79f"
}

.fa-glass-martini:before {
    content: "\f000"
}

.fa-glass-martini-alt:before {
    content: "\f57b"
}

.fa-glass-whiskey:before {
    content: "\f7a0"
}

.fa-glasses:before {
    content: "\f530"
}

.fa-glide:before {
    content: "\f2a5"
}

.fa-glide-g:before {
    content: "\f2a6"
}

.fa-globe:before {
    content: "\f0ac"
}

.fa-globe-africa:before {
    content: "\f57c"
}

.fa-globe-americas:before {
    content: "\f57d"
}

.fa-globe-asia:before {
    content: "\f57e"
}

.fa-globe-europe:before {
    content: "\f7a2"
}

.fa-gofore:before {
    content: "\f3a7"
}

.fa-golf-ball:before {
    content: "\f450"
}

.fa-goodreads:before {
    content: "\f3a8"
}

.fa-goodreads-g:before {
    content: "\f3a9"
}

.fa-google:before {
    content: "\f1a0"
}

.fa-google-drive:before {
    content: "\f3aa"
}

.fa-google-pay:before {
    content: "\e079"
}

.fa-google-play:before {
    content: "\f3ab"
}

.fa-google-plus:before {
    content: "\f2b3"
}

.fa-google-plus-g:before {
    content: "\f0d5"
}

.fa-google-plus-square:before {
    content: "\f0d4"
}

.fa-google-wallet:before {
    content: "\f1ee"
}

.fa-gopuram:before {
    content: "\f664"
}

.fa-graduation-cap:before {
    content: "\f19d"
}

.fa-gratipay:before {
    content: "\f184"
}

.fa-grav:before {
    content: "\f2d6"
}

.fa-greater-than:before {
    content: "\f531"
}

.fa-greater-than-equal:before {
    content: "\f532"
}

.fa-grimace:before {
    content: "\f57f"
}

.fa-grin:before {
    content: "\f580"
}

.fa-grin-alt:before {
    content: "\f581"
}

.fa-grin-beam:before {
    content: "\f582"
}

.fa-grin-beam-sweat:before {
    content: "\f583"
}

.fa-grin-hearts:before {
    content: "\f584"
}

.fa-grin-squint:before {
    content: "\f585"
}

.fa-grin-squint-tears:before {
    content: "\f586"
}

.fa-grin-stars:before {
    content: "\f587"
}

.fa-grin-tears:before {
    content: "\f588"
}

.fa-grin-tongue:before {
    content: "\f589"
}

.fa-grin-tongue-squint:before {
    content: "\f58a"
}

.fa-grin-tongue-wink:before {
    content: "\f58b"
}

.fa-grin-wink:before {
    content: "\f58c"
}

.fa-grip-horizontal:before {
    content: "\f58d"
}

.fa-grip-lines:before {
    content: "\f7a4"
}

.fa-grip-lines-vertical:before {
    content: "\f7a5"
}

.fa-grip-vertical:before {
    content: "\f58e"
}

.fa-gripfire:before {
    content: "\f3ac"
}

.fa-grunt:before {
    content: "\f3ad"
}

.fa-guilded:before {
    content: "\e07e"
}

.fa-guitar:before {
    content: "\f7a6"
}

.fa-gulp:before {
    content: "\f3ae"
}

.fa-h-square:before {
    content: "\f0fd"
}

.fa-hacker-news:before {
    content: "\f1d4"
}

.fa-hacker-news-square:before {
    content: "\f3af"
}

.fa-hackerrank:before {
    content: "\f5f7"
}

.fa-hamburger:before {
    content: "\f805"
}

.fa-hammer:before {
    content: "\f6e3"
}

.fa-hamsa:before {
    content: "\f665"
}

.fa-hand-holding:before {
    content: "\f4bd"
}

.fa-hand-holding-heart:before {
    content: "\f4be"
}

.fa-hand-holding-medical:before {
    content: "\e05c"
}

.fa-hand-holding-usd:before {
    content: "\f4c0"
}

.fa-hand-holding-water:before {
    content: "\f4c1"
}

.fa-hand-lizard:before {
    content: "\f258"
}

.fa-hand-middle-finger:before {
    content: "\f806"
}

.fa-hand-paper:before {
    content: "\f256"
}

.fa-hand-peace:before {
    content: "\f25b"
}

.fa-hand-point-down:before {
    content: "\f0a7"
}

.fa-hand-point-left:before {
    content: "\f0a5"
}

.fa-hand-point-right:before {
    content: "\f0a4"
}

.fa-hand-point-up:before {
    content: "\f0a6"
}

.fa-hand-pointer:before {
    content: "\f25a"
}

.fa-hand-rock:before {
    content: "\f255"
}

.fa-hand-scissors:before {
    content: "\f257"
}

.fa-hand-sparkles:before {
    content: "\e05d"
}

.fa-hand-spock:before {
    content: "\f259"
}

.fa-hands:before {
    content: "\f4c2"
}

.fa-hands-helping:before {
    content: "\f4c4"
}

.fa-hands-wash:before {
    content: "\e05e"
}

.fa-handshake:before {
    content: "\f2b5"
}

.fa-handshake-alt-slash:before {
    content: "\e05f"
}

.fa-handshake-slash:before {
    content: "\e060"
}

.fa-hanukiah:before {
    content: "\f6e6"
}

.fa-hard-hat:before {
    content: "\f807"
}

.fa-hashtag:before {
    content: "\f292"
}

.fa-hat-cowboy:before {
    content: "\f8c0"
}

.fa-hat-cowboy-side:before {
    content: "\f8c1"
}

.fa-hat-wizard:before {
    content: "\f6e8"
}

.fa-hdd:before {
    content: "\f0a0"
}

.fa-head-side-cough:before {
    content: "\e061"
}

.fa-head-side-cough-slash:before {
    content: "\e062"
}

.fa-head-side-mask:before {
    content: "\e063"
}

.fa-head-side-virus:before {
    content: "\e064"
}

.fa-heading:before {
    content: "\f1dc"
}

.fa-headphones:before {
    content: "\f025"
}

.fa-headphones-alt:before {
    content: "\f58f"
}

.fa-headset:before {
    content: "\f590"
}

.fa-heart:before {
    content: "\f004"
}

.fa-heart-broken:before {
    content: "\f7a9"
}

.fa-heartbeat:before {
    content: "\f21e"
}

.fa-helicopter:before {
    content: "\f533"
}

.fa-highlighter:before {
    content: "\f591"
}

.fa-hiking:before {
    content: "\f6ec"
}

.fa-hippo:before {
    content: "\f6ed"
}

.fa-hips:before {
    content: "\f452"
}

.fa-hire-a-helper:before {
    content: "\f3b0"
}

.fa-history:before {
    content: "\f1da"
}

.fa-hive:before {
    content: "\e07f"
}

.fa-hockey-puck:before {
    content: "\f453"
}

.fa-holly-berry:before {
    content: "\f7aa"
}

.fa-home:before {
    content: "\f015"
}

.fa-hooli:before {
    content: "\f427"
}

.fa-hornbill:before {
    content: "\f592"
}

.fa-horse:before {
    content: "\f6f0"
}

.fa-horse-head:before {
    content: "\f7ab"
}

.fa-hospital:before {
    content: "\f0f8"
}

.fa-hospital-alt:before {
    content: "\f47d"
}

.fa-hospital-symbol:before {
    content: "\f47e"
}

.fa-hospital-user:before {
    content: "\f80d"
}

.fa-hot-tub:before {
    content: "\f593"
}

.fa-hotdog:before {
    content: "\f80f"
}

.fa-hotel:before {
    content: "\f594"
}

.fa-hotjar:before {
    content: "\f3b1"
}

.fa-hourglass:before {
    content: "\f254"
}

.fa-hourglass-end:before {
    content: "\f253"
}

.fa-hourglass-half:before {
    content: "\f252"
}

.fa-hourglass-start:before {
    content: "\f251"
}

.fa-house-damage:before {
    content: "\f6f1"
}

.fa-house-user:before {
    content: "\e065"
}

.fa-houzz:before {
    content: "\f27c"
}

.fa-hryvnia:before {
    content: "\f6f2"
}

.fa-html5:before {
    content: "\f13b"
}

.fa-hubspot:before {
    content: "\f3b2"
}

.fa-i-cursor:before {
    content: "\f246"
}

.fa-ice-cream:before {
    content: "\f810"
}

.fa-icicles:before {
    content: "\f7ad"
}

.fa-icons:before {
    content: "\f86d"
}

.fa-id-badge:before {
    content: "\f2c1"
}

.fa-id-card:before {
    content: "\f2c2"
}

.fa-id-card-alt:before {
    content: "\f47f"
}

.fa-ideal:before {
    content: "\e013"
}

.fa-igloo:before {
    content: "\f7ae"
}

.fa-image:before {
    content: "\f03e"
}

.fa-images:before {
    content: "\f302"
}

.fa-imdb:before {
    content: "\f2d8"
}

.fa-inbox:before {
    content: "\f01c"
}

.fa-indent:before {
    content: "\f03c"
}

.fa-industry:before {
    content: "\f275"
}

.fa-infinity:before {
    content: "\f534"
}

.fa-info:before {
    content: "\f129"
}

.fa-info-circle:before {
    content: "\f05a"
}

.fa-innosoft:before {
    content: "\e080"
}

.fa-instagram:before {
    content: "\f16d"
}

.fa-instagram-square:before {
    content: "\e055"
}

.fa-instalod:before {
    content: "\e081"
}

.fa-intercom:before {
    content: "\f7af"
}

.fa-internet-explorer:before {
    content: "\f26b"
}

.fa-invision:before {
    content: "\f7b0"
}

.fa-ioxhost:before {
    content: "\f208"
}

.fa-italic:before {
    content: "\f033"
}

.fa-itch-io:before {
    content: "\f83a"
}

.fa-itunes:before {
    content: "\f3b4"
}

.fa-itunes-note:before {
    content: "\f3b5"
}

.fa-java:before {
    content: "\f4e4"
}

.fa-jedi:before {
    content: "\f669"
}

.fa-jedi-order:before {
    content: "\f50e"
}

.fa-jenkins:before {
    content: "\f3b6"
}

.fa-jira:before {
    content: "\f7b1"
}

.fa-joget:before {
    content: "\f3b7"
}

.fa-joint:before {
    content: "\f595"
}

.fa-joomla:before {
    content: "\f1aa"
}

.fa-journal-whills:before {
    content: "\f66a"
}

.fa-js:before {
    content: "\f3b8"
}

.fa-js-square:before {
    content: "\f3b9"
}

.fa-jsfiddle:before {
    content: "\f1cc"
}

.fa-kaaba:before {
    content: "\f66b"
}

.fa-kaggle:before {
    content: "\f5fa"
}

.fa-key:before {
    content: "\f084"
}

.fa-keybase:before {
    content: "\f4f5"
}

.fa-keyboard:before {
    content: "\f11c"
}

.fa-keycdn:before {
    content: "\f3ba"
}

.fa-khanda:before {
    content: "\f66d"
}

.fa-kickstarter:before {
    content: "\f3bb"
}

.fa-kickstarter-k:before {
    content: "\f3bc"
}

.fa-kiss:before {
    content: "\f596"
}

.fa-kiss-beam:before {
    content: "\f597"
}

.fa-kiss-wink-heart:before {
    content: "\f598"
}

.fa-kiwi-bird:before {
    content: "\f535"
}

.fa-korvue:before {
    content: "\f42f"
}

.fa-landmark:before {
    content: "\f66f"
}

.fa-language:before {
    content: "\f1ab"
}

.fa-laptop:before {
    content: "\f109"
}

.fa-laptop-code:before {
    content: "\f5fc"
}

.fa-laptop-house:before {
    content: "\e066"
}

.fa-laptop-medical:before {
    content: "\f812"
}

.fa-laravel:before {
    content: "\f3bd"
}

.fa-lastfm:before {
    content: "\f202"
}

.fa-lastfm-square:before {
    content: "\f203"
}

.fa-laugh:before {
    content: "\f599"
}

.fa-laugh-beam:before {
    content: "\f59a"
}

.fa-laugh-squint:before {
    content: "\f59b"
}

.fa-laugh-wink:before {
    content: "\f59c"
}

.fa-layer-group:before {
    content: "\f5fd"
}

.fa-leaf:before {
    content: "\f06c"
}

.fa-leanpub:before {
    content: "\f212"
}

.fa-lemon:before {
    content: "\f094"
}

.fa-less:before {
    content: "\f41d"
}

.fa-less-than:before {
    content: "\f536"
}

.fa-less-than-equal:before {
    content: "\f537"
}

.fa-level-down-alt:before {
    content: "\f3be"
}

.fa-level-up-alt:before {
    content: "\f3bf"
}

.fa-life-ring:before {
    content: "\f1cd"
}

.fa-lightbulb:before {
    content: "\f0eb"
}

.fa-line:before {
    content: "\f3c0"
}

.fa-link:before {
    content: "\f0c1"
}

.fa-linkedin:before {
    content: "\f08c"
}

.fa-linkedin-in:before {
    content: "\f0e1"
}

.fa-linode:before {
    content: "\f2b8"
}

.fa-linux:before {
    content: "\f17c"
}

.fa-lira-sign:before {
    content: "\f195"
}

.fa-list:before {
    content: "\f03a"
}

.fa-list-alt:before {
    content: "\f022"
}

.fa-list-ol:before {
    content: "\f0cb"
}

.fa-list-ul:before {
    content: "\f0ca"
}

.fa-location-arrow:before {
    content: "\f124"
}

.fa-lock:before {
    content: "\f023"
}

.fa-lock-open:before {
    content: "\f3c1"
}

.fa-long-arrow-alt-down:before {
    content: "\f309"
}

.fa-long-arrow-alt-left:before {
    content: "\f30a"
}

.fa-long-arrow-alt-right:before {
    content: "\f30b"
}

.fa-long-arrow-alt-up:before {
    content: "\f30c"
}

.fa-low-vision:before {
    content: "\f2a8"
}

.fa-luggage-cart:before {
    content: "\f59d"
}

.fa-lungs:before {
    content: "\f604"
}

.fa-lungs-virus:before {
    content: "\e067"
}

.fa-lyft:before {
    content: "\f3c3"
}

.fa-magento:before {
    content: "\f3c4"
}

.fa-magic:before {
    content: "\f0d0"
}

.fa-magnet:before {
    content: "\f076"
}

.fa-mail-bulk:before {
    content: "\f674"
}

.fa-mailchimp:before {
    content: "\f59e"
}

.fa-male:before {
    content: "\f183"
}

.fa-mandalorian:before {
    content: "\f50f"
}

.fa-map:before {
    content: "\f279"
}

.fa-map-marked:before {
    content: "\f59f"
}

.fa-map-marked-alt:before {
    content: "\f5a0"
}

.fa-map-marker:before {
    content: "\f041"
}

.fa-map-marker-alt:before {
    content: "\f3c5"
}

.fa-map-pin:before {
    content: "\f276"
}

.fa-map-signs:before {
    content: "\f277"
}

.fa-markdown:before {
    content: "\f60f"
}

.fa-marker:before {
    content: "\f5a1"
}

.fa-mars:before {
    content: "\f222"
}

.fa-mars-double:before {
    content: "\f227"
}

.fa-mars-stroke:before {
    content: "\f229"
}

.fa-mars-stroke-h:before {
    content: "\f22b"
}

.fa-mars-stroke-v:before {
    content: "\f22a"
}

.fa-mask:before {
    content: "\f6fa"
}

.fa-mastodon:before {
    content: "\f4f6"
}

.fa-maxcdn:before {
    content: "\f136"
}

.fa-mdb:before {
    content: "\f8ca"
}

.fa-medal:before {
    content: "\f5a2"
}

.fa-medapps:before {
    content: "\f3c6"
}

.fa-medium:before {
    content: "\f23a"
}

.fa-medium-m:before {
    content: "\f3c7"
}

.fa-medkit:before {
    content: "\f0fa"
}

.fa-medrt:before {
    content: "\f3c8"
}

.fa-meetup:before {
    content: "\f2e0"
}

.fa-megaport:before {
    content: "\f5a3"
}

.fa-meh:before {
    content: "\f11a"
}

.fa-meh-blank:before {
    content: "\f5a4"
}

.fa-meh-rolling-eyes:before {
    content: "\f5a5"
}

.fa-memory:before {
    content: "\f538"
}

.fa-mendeley:before {
    content: "\f7b3"
}

.fa-menorah:before {
    content: "\f676"
}

.fa-mercury:before {
    content: "\f223"
}

.fa-meteor:before {
    content: "\f753"
}

.fa-microblog:before {
    content: "\e01a"
}

.fa-microchip:before {
    content: "\f2db"
}

.fa-microphone:before {
    content: "\f130"
}

.fa-microphone-alt:before {
    content: "\f3c9"
}

.fa-microphone-alt-slash:before {
    content: "\f539"
}

.fa-microphone-slash:before {
    content: "\f131"
}

.fa-microscope:before {
    content: "\f610"
}

.fa-microsoft:before {
    content: "\f3ca"
}

.fa-minus:before {
    content: "\f068"
}

.fa-minus-circle:before {
    content: "\f056"
}

.fa-minus-square:before {
    content: "\f146"
}

.fa-mitten:before {
    content: "\f7b5"
}

.fa-mix:before {
    content: "\f3cb"
}

.fa-mixcloud:before {
    content: "\f289"
}

.fa-mixer:before {
    content: "\e056"
}

.fa-mizuni:before {
    content: "\f3cc"
}

.fa-mobile:before {
    content: "\f10b"
}

.fa-mobile-alt:before {
    content: "\f3cd"
}

.fa-modx:before {
    content: "\f285"
}

.fa-monero:before {
    content: "\f3d0"
}

.fa-money-bill:before {
    content: "\f0d6"
}

.fa-money-bill-alt:before {
    content: "\f3d1"
}

.fa-money-bill-wave:before {
    content: "\f53a"
}

.fa-money-bill-wave-alt:before {
    content: "\f53b"
}

.fa-money-check:before {
    content: "\f53c"
}

.fa-money-check-alt:before {
    content: "\f53d"
}

.fa-monument:before {
    content: "\f5a6"
}

.fa-moon:before {
    content: "\f186"
}

.fa-mortar-pestle:before {
    content: "\f5a7"
}

.fa-mosque:before {
    content: "\f678"
}

.fa-motorcycle:before {
    content: "\f21c"
}

.fa-mountain:before {
    content: "\f6fc"
}

.fa-mouse:before {
    content: "\f8cc"
}

.fa-mouse-pointer:before {
    content: "\f245"
}

.fa-mug-hot:before {
    content: "\f7b6"
}

.fa-music:before {
    content: "\f001"
}

.fa-napster:before {
    content: "\f3d2"
}

.fa-neos:before {
    content: "\f612"
}

.fa-network-wired:before {
    content: "\f6ff"
}

.fa-neuter:before {
    content: "\f22c"
}

.fa-newspaper:before {
    content: "\f1ea"
}

.fa-nimblr:before {
    content: "\f5a8"
}

.fa-node:before {
    content: "\f419"
}

.fa-node-js:before {
    content: "\f3d3"
}

.fa-not-equal:before {
    content: "\f53e"
}

.fa-notes-medical:before {
    content: "\f481"
}

.fa-npm:before {
    content: "\f3d4"
}

.fa-ns8:before {
    content: "\f3d5"
}

.fa-nutritionix:before {
    content: "\f3d6"
}

.fa-object-group:before {
    content: "\f247"
}

.fa-object-ungroup:before {
    content: "\f248"
}

.fa-octopus-deploy:before {
    content: "\e082"
}

.fa-odnoklassniki:before {
    content: "\f263"
}

.fa-odnoklassniki-square:before {
    content: "\f264"
}

.fa-oil-can:before {
    content: "\f613"
}

.fa-old-republic:before {
    content: "\f510"
}

.fa-om:before {
    content: "\f679"
}

.fa-opencart:before {
    content: "\f23d"
}

.fa-openid:before {
    content: "\f19b"
}

.fa-opera:before {
    content: "\f26a"
}

.fa-optin-monster:before {
    content: "\f23c"
}

.fa-orcid:before {
    content: "\f8d2"
}

.fa-osi:before {
    content: "\f41a"
}

.fa-otter:before {
    content: "\f700"
}

.fa-outdent:before {
    content: "\f03b"
}

.fa-page4:before {
    content: "\f3d7"
}

.fa-pagelines:before {
    content: "\f18c"
}

.fa-pager:before {
    content: "\f815"
}

.fa-paint-brush:before {
    content: "\f1fc"
}

.fa-paint-roller:before {
    content: "\f5aa"
}

.fa-palette:before {
    content: "\f53f"
}

.fa-palfed:before {
    content: "\f3d8"
}

.fa-pallet:before {
    content: "\f482"
}

.fa-paper-plane:before {
    content: "\f1d8"
}

.fa-paperclip:before {
    content: "\f0c6"
}

.fa-parachute-box:before {
    content: "\f4cd"
}

.fa-paragraph:before {
    content: "\f1dd"
}

.fa-parking:before {
    content: "\f540"
}

.fa-passport:before {
    content: "\f5ab"
}

.fa-pastafarianism:before {
    content: "\f67b"
}

.fa-paste:before {
    content: "\f0ea"
}

.fa-patreon:before {
    content: "\f3d9"
}

.fa-pause:before {
    content: "\f04c"
}

.fa-pause-circle:before {
    content: "\f28b"
}

.fa-paw:before {
    content: "\f1b0"
}

.fa-paypal:before {
    content: "\f1ed"
}

.fa-peace:before {
    content: "\f67c"
}

.fa-pen:before {
    content: "\f304"
}

.fa-pen-alt:before {
    content: "\f305"
}

.fa-pen-fancy:before {
    content: "\f5ac"
}

.fa-pen-nib:before {
    content: "\f5ad"
}

.fa-pen-square:before {
    content: "\f14b"
}

.fa-pencil-alt:before {
    content: "\f303"
}

.fa-pencil-ruler:before {
    content: "\f5ae"
}

.fa-penny-arcade:before {
    content: "\f704"
}

.fa-people-arrows:before {
    content: "\e068"
}

.fa-people-carry:before {
    content: "\f4ce"
}

.fa-pepper-hot:before {
    content: "\f816"
}

.fa-perbyte:before {
    content: "\e083"
}

.fa-percent:before {
    content: "\f295"
}

.fa-percentage:before {
    content: "\f541"
}

.fa-periscope:before {
    content: "\f3da"
}

.fa-person-booth:before {
    content: "\f756"
}

.fa-phabricator:before {
    content: "\f3db"
}

.fa-phoenix-framework:before {
    content: "\f3dc"
}

.fa-phoenix-squadron:before {
    content: "\f511"
}

.fa-phone:before {
    content: "\f095"
}

.fa-phone-alt:before {
    content: "\f879"
}

.fa-phone-slash:before {
    content: "\f3dd"
}

.fa-phone-square:before {
    content: "\f098"
}

.fa-phone-square-alt:before {
    content: "\f87b"
}

.fa-phone-volume:before {
    content: "\f2a0"
}

.fa-photo-video:before {
    content: "\f87c"
}

.fa-php:before {
    content: "\f457"
}

.fa-pied-piper:before {
    content: "\f2ae"
}

.fa-pied-piper-alt:before {
    content: "\f1a8"
}

.fa-pied-piper-hat:before {
    content: "\f4e5"
}

.fa-pied-piper-pp:before {
    content: "\f1a7"
}

.fa-pied-piper-square:before {
    content: "\e01e"
}

.fa-piggy-bank:before {
    content: "\f4d3"
}

.fa-pills:before {
    content: "\f484"
}

.fa-pinterest:before {
    content: "\f0d2"
}

.fa-pinterest-p:before {
    content: "\f231"
}

.fa-pinterest-square:before {
    content: "\f0d3"
}

.fa-pizza-slice:before {
    content: "\f818"
}

.fa-place-of-worship:before {
    content: "\f67f"
}

.fa-plane:before {
    content: "\f072"
}

.fa-plane-arrival:before {
    content: "\f5af"
}

.fa-plane-departure:before {
    content: "\f5b0"
}

.fa-plane-slash:before {
    content: "\e069"
}

.fa-play:before {
    content: "\f04b"
}

.fa-play-circle:before {
    content: "\f144"
}

.fa-playstation:before {
    content: "\f3df"
}

.fa-plug:before {
    content: "\f1e6"
}

.fa-plus:before {
    content: "\f067"
}

.fa-plus-circle:before {
    content: "\f055"
}

.fa-plus-square:before {
    content: "\f0fe"
}

.fa-podcast:before {
    content: "\f2ce"
}

.fa-poll:before {
    content: "\f681"
}

.fa-poll-h:before {
    content: "\f682"
}

.fa-poo:before {
    content: "\f2fe"
}

.fa-poo-storm:before {
    content: "\f75a"
}

.fa-poop:before {
    content: "\f619"
}

.fa-portrait:before {
    content: "\f3e0"
}

.fa-pound-sign:before {
    content: "\f154"
}

.fa-power-off:before {
    content: "\f011"
}

.fa-pray:before {
    content: "\f683"
}

.fa-praying-hands:before {
    content: "\f684"
}

.fa-prescription:before {
    content: "\f5b1"
}

.fa-prescription-bottle:before {
    content: "\f485"
}

.fa-prescription-bottle-alt:before {
    content: "\f486"
}

.fa-print:before {
    content: "\f02f"
}

.fa-procedures:before {
    content: "\f487"
}

.fa-product-hunt:before {
    content: "\f288"
}

.fa-project-diagram:before {
    content: "\f542"
}

.fa-pump-medical:before {
    content: "\e06a"
}

.fa-pump-soap:before {
    content: "\e06b"
}

.fa-pushed:before {
    content: "\f3e1"
}

.fa-puzzle-piece:before {
    content: "\f12e"
}

.fa-python:before {
    content: "\f3e2"
}

.fa-qq:before {
    content: "\f1d6"
}

.fa-qrcode:before {
    content: "\f029"
}

.fa-question:before {
    content: "\f128"
}

.fa-question-circle:before {
    content: "\f059"
}

.fa-quidditch:before {
    content: "\f458"
}

.fa-quinscape:before {
    content: "\f459"
}

.fa-quora:before {
    content: "\f2c4"
}

.fa-quote-left:before {
    content: "\f10d"
}

.fa-quote-right:before {
    content: "\f10e"
}

.fa-quran:before {
    content: "\f687"
}

.fa-r-project:before {
    content: "\f4f7"
}

.fa-radiation:before {
    content: "\f7b9"
}

.fa-radiation-alt:before {
    content: "\f7ba"
}

.fa-rainbow:before {
    content: "\f75b"
}

.fa-random:before {
    content: "\f074"
}

.fa-raspberry-pi:before {
    content: "\f7bb"
}

.fa-ravelry:before {
    content: "\f2d9"
}

.fa-react:before {
    content: "\f41b"
}

.fa-reacteurope:before {
    content: "\f75d"
}

.fa-readme:before {
    content: "\f4d5"
}

.fa-rebel:before {
    content: "\f1d0"
}

.fa-receipt:before {
    content: "\f543"
}

.fa-record-vinyl:before {
    content: "\f8d9"
}

.fa-recycle:before {
    content: "\f1b8"
}

.fa-red-river:before {
    content: "\f3e3"
}

.fa-reddit:before {
    content: "\f1a1"
}

.fa-reddit-alien:before {
    content: "\f281"
}

.fa-reddit-square:before {
    content: "\f1a2"
}

.fa-redhat:before {
    content: "\f7bc"
}

.fa-redo:before {
    content: "\f01e"
}

.fa-redo-alt:before {
    content: "\f2f9"
}

.fa-registered:before {
    content: "\f25d"
}

.fa-remove-format:before {
    content: "\f87d"
}

.fa-renren:before {
    content: "\f18b"
}

.fa-reply:before {
    content: "\f3e5"
}

.fa-reply-all:before {
    content: "\f122"
}

.fa-replyd:before {
    content: "\f3e6"
}

.fa-republican:before {
    content: "\f75e"
}

.fa-researchgate:before {
    content: "\f4f8"
}

.fa-resolving:before {
    content: "\f3e7"
}

.fa-restroom:before {
    content: "\f7bd"
}

.fa-retweet:before {
    content: "\f079"
}

.fa-rev:before {
    content: "\f5b2"
}

.fa-ribbon:before {
    content: "\f4d6"
}

.fa-ring:before {
    content: "\f70b"
}

.fa-road:before {
    content: "\f018"
}

.fa-robot:before {
    content: "\f544"
}

.fa-rocket:before {
    content: "\f135"
}

.fa-rocketchat:before {
    content: "\f3e8"
}

.fa-rockrms:before {
    content: "\f3e9"
}

.fa-route:before {
    content: "\f4d7"
}

.fa-rss:before {
    content: "\f09e"
}

.fa-rss-square:before {
    content: "\f143"
}

.fa-ruble-sign:before {
    content: "\f158"
}

.fa-ruler:before {
    content: "\f545"
}

.fa-ruler-combined:before {
    content: "\f546"
}

.fa-ruler-horizontal:before {
    content: "\f547"
}

.fa-ruler-vertical:before {
    content: "\f548"
}

.fa-running:before {
    content: "\f70c"
}

.fa-rupee-sign:before {
    content: "\f156"
}

.fa-rust:before {
    content: "\e07a"
}

.fa-sad-cry:before {
    content: "\f5b3"
}

.fa-sad-tear:before {
    content: "\f5b4"
}

.fa-safari:before {
    content: "\f267"
}

.fa-salesforce:before {
    content: "\f83b"
}

.fa-sass:before {
    content: "\f41e"
}

.fa-satellite:before {
    content: "\f7bf"
}

.fa-satellite-dish:before {
    content: "\f7c0"
}

.fa-save:before {
    content: "\f0c7"
}

.fa-schlix:before {
    content: "\f3ea"
}

.fa-school:before {
    content: "\f549"
}

.fa-screwdriver:before {
    content: "\f54a"
}

.fa-scribd:before {
    content: "\f28a"
}

.fa-scroll:before {
    content: "\f70e"
}

.fa-sd-card:before {
    content: "\f7c2"
}

.fa-search:before {
    content: "\f002"
}

.fa-search-dollar:before {
    content: "\f688"
}

.fa-search-location:before {
    content: "\f689"
}

.fa-search-minus:before {
    content: "\f010"
}

.fa-search-plus:before {
    content: "\f00e"
}

.fa-searchengin:before {
    content: "\f3eb"
}

.fa-seedling:before {
    content: "\f4d8"
}

.fa-sellcast:before {
    content: "\f2da"
}

.fa-sellsy:before {
    content: "\f213"
}

.fa-server:before {
    content: "\f233"
}

.fa-servicestack:before {
    content: "\f3ec"
}

.fa-shapes:before {
    content: "\f61f"
}

.fa-share:before {
    content: "\f064"
}

.fa-share-alt:before {
    content: "\f1e0"
}

.fa-share-alt-square:before {
    content: "\f1e1"
}

.fa-share-square:before {
    content: "\f14d"
}

.fa-shekel-sign:before {
    content: "\f20b"
}

.fa-shield-alt:before {
    content: "\f3ed"
}

.fa-shield-virus:before {
    content: "\e06c"
}

.fa-ship:before {
    content: "\f21a"
}

.fa-shipping-fast:before {
    content: "\f48b"
}

.fa-shirtsinbulk:before {
    content: "\f214"
}

.fa-shoe-prints:before {
    content: "\f54b"
}

.fa-shopify:before {
    content: "\e057"
}

.fa-shopping-bag:before {
    content: "\f290"
}

.fa-shopping-basket:before {
    content: "\f291"
}

.fa-shopping-cart:before {
    content: "\f07a"
}

.fa-shopware:before {
    content: "\f5b5"
}

.fa-shower:before {
    content: "\f2cc"
}

.fa-shuttle-van:before {
    content: "\f5b6"
}

.fa-sign:before {
    content: "\f4d9"
}

.fa-sign-in-alt:before {
    content: "\f2f6"
}

.fa-sign-language:before {
    content: "\f2a7"
}

.fa-sign-out-alt:before {
    content: "\f2f5"
}

.fa-signal:before {
    content: "\f012"
}

.fa-signature:before {
    content: "\f5b7"
}

.fa-sim-card:before {
    content: "\f7c4"
}

.fa-simplybuilt:before {
    content: "\f215"
}

.fa-sink:before {
    content: "\e06d"
}

.fa-sistrix:before {
    content: "\f3ee"
}

.fa-sitemap:before {
    content: "\f0e8"
}

.fa-sith:before {
    content: "\f512"
}

.fa-skating:before {
    content: "\f7c5"
}

.fa-sketch:before {
    content: "\f7c6"
}

.fa-skiing:before {
    content: "\f7c9"
}

.fa-skiing-nordic:before {
    content: "\f7ca"
}

.fa-skull:before {
    content: "\f54c"
}

.fa-skull-crossbones:before {
    content: "\f714"
}

.fa-skyatlas:before {
    content: "\f216"
}

.fa-skype:before {
    content: "\f17e"
}

.fa-slack:before {
    content: "\f198"
}

.fa-slack-hash:before {
    content: "\f3ef"
}

.fa-slash:before {
    content: "\f715"
}

.fa-sleigh:before {
    content: "\f7cc"
}

.fa-sliders-h:before {
    content: "\f1de"
}

.fa-slideshare:before {
    content: "\f1e7"
}

.fa-smile:before {
    content: "\f118"
}

.fa-smile-beam:before {
    content: "\f5b8"
}

.fa-smile-wink:before {
    content: "\f4da"
}

.fa-smog:before {
    content: "\f75f"
}

.fa-smoking:before {
    content: "\f48d"
}

.fa-smoking-ban:before {
    content: "\f54d"
}

.fa-sms:before {
    content: "\f7cd"
}

.fa-snapchat:before {
    content: "\f2ab"
}

.fa-snapchat-ghost:before {
    content: "\f2ac"
}

.fa-snapchat-square:before {
    content: "\f2ad"
}

.fa-snowboarding:before {
    content: "\f7ce"
}

.fa-snowflake:before {
    content: "\f2dc"
}

.fa-snowman:before {
    content: "\f7d0"
}

.fa-snowplow:before {
    content: "\f7d2"
}

.fa-soap:before {
    content: "\e06e"
}

.fa-socks:before {
    content: "\f696"
}

.fa-solar-panel:before {
    content: "\f5ba"
}

.fa-sort:before {
    content: "\f0dc"
}

.fa-sort-alpha-down:before {
    content: "\f15d"
}

.fa-sort-alpha-down-alt:before {
    content: "\f881"
}

.fa-sort-alpha-up:before {
    content: "\f15e"
}

.fa-sort-alpha-up-alt:before {
    content: "\f882"
}

.fa-sort-amount-down:before {
    content: "\f160"
}

.fa-sort-amount-down-alt:before {
    content: "\f884"
}

.fa-sort-amount-up:before {
    content: "\f161"
}

.fa-sort-amount-up-alt:before {
    content: "\f885"
}

.fa-sort-down:before {
    content: "\f0dd"
}

.fa-sort-numeric-down:before {
    content: "\f162"
}

.fa-sort-numeric-down-alt:before {
    content: "\f886"
}

.fa-sort-numeric-up:before {
    content: "\f163"
}

.fa-sort-numeric-up-alt:before {
    content: "\f887"
}

.fa-sort-up:before {
    content: "\f0de"
}

.fa-soundcloud:before {
    content: "\f1be"
}

.fa-sourcetree:before {
    content: "\f7d3"
}

.fa-spa:before {
    content: "\f5bb"
}

.fa-space-shuttle:before {
    content: "\f197"
}

.fa-speakap:before {
    content: "\f3f3"
}

.fa-speaker-deck:before {
    content: "\f83c"
}

.fa-spell-check:before {
    content: "\f891"
}

.fa-spider:before {
    content: "\f717"
}

.fa-spinner:before {
    content: "\f110"
}

.fa-splotch:before {
    content: "\f5bc"
}

.fa-spotify:before {
    content: "\f1bc"
}

.fa-spray-can:before {
    content: "\f5bd"
}

.fa-square:before {
    content: "\f0c8"
}

.fa-square-full:before {
    content: "\f45c"
}

.fa-square-root-alt:before {
    content: "\f698"
}

.fa-squarespace:before {
    content: "\f5be"
}

.fa-stack-exchange:before {
    content: "\f18d"
}

.fa-stack-overflow:before {
    content: "\f16c"
}

.fa-stackpath:before {
    content: "\f842"
}

.fa-stamp:before {
    content: "\f5bf"
}

.fa-star:before {
    content: "\f005"
}

.fa-star-and-crescent:before {
    content: "\f699"
}

.fa-star-half:before {
    content: "\f089"
}

.fa-star-half-alt:before {
    content: "\f5c0"
}

.fa-star-of-david:before {
    content: "\f69a"
}

.fa-star-of-life:before {
    content: "\f621"
}

.fa-staylinked:before {
    content: "\f3f5"
}

.fa-steam:before {
    content: "\f1b6"
}

.fa-steam-square:before {
    content: "\f1b7"
}

.fa-steam-symbol:before {
    content: "\f3f6"
}

.fa-step-backward:before {
    content: "\f048"
}

.fa-step-forward:before {
    content: "\f051"
}

.fa-stethoscope:before {
    content: "\f0f1"
}

.fa-sticker-mule:before {
    content: "\f3f7"
}

.fa-sticky-note:before {
    content: "\f249"
}

.fa-stop:before {
    content: "\f04d"
}

.fa-stop-circle:before {
    content: "\f28d"
}

.fa-stopwatch:before {
    content: "\f2f2"
}

.fa-stopwatch-20:before {
    content: "\e06f"
}

.fa-store:before {
    content: "\f54e"
}

.fa-store-alt:before {
    content: "\f54f"
}

.fa-store-alt-slash:before {
    content: "\e070"
}

.fa-store-slash:before {
    content: "\e071"
}

.fa-strava:before {
    content: "\f428"
}

.fa-stream:before {
    content: "\f550"
}

.fa-street-view:before {
    content: "\f21d"
}

.fa-strikethrough:before {
    content: "\f0cc"
}

.fa-stripe:before {
    content: "\f429"
}

.fa-stripe-s:before {
    content: "\f42a"
}

.fa-stroopwafel:before {
    content: "\f551"
}

.fa-studiovinari:before {
    content: "\f3f8"
}

.fa-stumbleupon:before {
    content: "\f1a4"
}

.fa-stumbleupon-circle:before {
    content: "\f1a3"
}

.fa-subscript:before {
    content: "\f12c"
}

.fa-subway:before {
    content: "\f239"
}

.fa-suitcase:before {
    content: "\f0f2"
}

.fa-suitcase-rolling:before {
    content: "\f5c1"
}

.fa-sun:before {
    content: "\f185"
}

.fa-superpowers:before {
    content: "\f2dd"
}

.fa-superscript:before {
    content: "\f12b"
}

.fa-supple:before {
    content: "\f3f9"
}

.fa-surprise:before {
    content: "\f5c2"
}

.fa-suse:before {
    content: "\f7d6"
}

.fa-swatchbook:before {
    content: "\f5c3"
}

.fa-swift:before {
    content: "\f8e1"
}

.fa-swimmer:before {
    content: "\f5c4"
}

.fa-swimming-pool:before {
    content: "\f5c5"
}

.fa-symfony:before {
    content: "\f83d"
}

.fa-synagogue:before {
    content: "\f69b"
}

.fa-sync:before {
    content: "\f021"
}

.fa-sync-alt:before {
    content: "\f2f1"
}

.fa-syringe:before {
    content: "\f48e"
}

.fa-table:before {
    content: "\f0ce"
}

.fa-table-tennis:before {
    content: "\f45d"
}

.fa-tablet:before {
    content: "\f10a"
}

.fa-tablet-alt:before {
    content: "\f3fa"
}

.fa-tablets:before {
    content: "\f490"
}

.fa-tachometer-alt:before {
    content: "\f3fd"
}

.fa-tag:before {
    content: "\f02b"
}

.fa-tags:before {
    content: "\f02c"
}

.fa-tape:before {
    content: "\f4db"
}

.fa-tasks:before {
    content: "\f0ae"
}

.fa-taxi:before {
    content: "\f1ba"
}

.fa-teamspeak:before {
    content: "\f4f9"
}

.fa-teeth:before {
    content: "\f62e"
}

.fa-teeth-open:before {
    content: "\f62f"
}

.fa-telegram:before {
    content: "\f2c6"
}

.fa-telegram-plane:before {
    content: "\f3fe"
}

.fa-temperature-high:before {
    content: "\f769"
}

.fa-temperature-low:before {
    content: "\f76b"
}

.fa-tencent-weibo:before {
    content: "\f1d5"
}

.fa-tenge:before {
    content: "\f7d7"
}

.fa-terminal:before {
    content: "\f120"
}

.fa-text-height:before {
    content: "\f034"
}

.fa-text-width:before {
    content: "\f035"
}

.fa-th:before {
    content: "\f00a"
}

.fa-th-large:before {
    content: "\f009"
}

.fa-th-list:before {
    content: "\f00b"
}

.fa-the-red-yeti:before {
    content: "\f69d"
}

.fa-theater-masks:before {
    content: "\f630"
}

.fa-themeco:before {
    content: "\f5c6"
}

.fa-themeisle:before {
    content: "\f2b2"
}

.fa-thermometer:before {
    content: "\f491"
}

.fa-thermometer-empty:before {
    content: "\f2cb"
}

.fa-thermometer-full:before {
    content: "\f2c7"
}

.fa-thermometer-half:before {
    content: "\f2c9"
}

.fa-thermometer-quarter:before {
    content: "\f2ca"
}

.fa-thermometer-three-quarters:before {
    content: "\f2c8"
}

.fa-think-peaks:before {
    content: "\f731"
}

.fa-thumbs-down:before {
    content: "\f165"
}

.fa-thumbs-up:before {
    content: "\f164"
}

.fa-thumbtack:before {
    content: "\f08d"
}

.fa-ticket-alt:before {
    content: "\f3ff"
}

.fa-tiktok:before {
    content: "\e07b"
}

.fa-times:before {
    content: "\f00d"
}

.fa-times-circle:before {
    content: "\f057"
}

.fa-tint:before {
    content: "\f043"
}

.fa-tint-slash:before {
    content: "\f5c7"
}

.fa-tired:before {
    content: "\f5c8"
}

.fa-toggle-off:before {
    content: "\f204"
}

.fa-toggle-on:before {
    content: "\f205"
}

.fa-toilet:before {
    content: "\f7d8"
}

.fa-toilet-paper:before {
    content: "\f71e"
}

.fa-toilet-paper-slash:before {
    content: "\e072"
}

.fa-toolbox:before {
    content: "\f552"
}

.fa-tools:before {
    content: "\f7d9"
}

.fa-tooth:before {
    content: "\f5c9"
}

.fa-torah:before {
    content: "\f6a0"
}

.fa-torii-gate:before {
    content: "\f6a1"
}

.fa-tractor:before {
    content: "\f722"
}

.fa-trade-federation:before {
    content: "\f513"
}

.fa-trademark:before {
    content: "\f25c"
}

.fa-traffic-light:before {
    content: "\f637"
}

.fa-trailer:before {
    content: "\e041"
}

.fa-train:before {
    content: "\f238"
}

.fa-tram:before {
    content: "\f7da"
}

.fa-transgender:before {
    content: "\f224"
}

.fa-transgender-alt:before {
    content: "\f225"
}

.fa-trash:before {
    content: "\f1f8"
}

.fa-trash-alt:before {
    content: "\f2ed"
}

.fa-trash-restore:before {
    content: "\f829"
}

.fa-trash-restore-alt:before {
    content: "\f82a"
}

.fa-tree:before {
    content: "\f1bb"
}

.fa-trello:before {
    content: "\f181"
}

.fa-trophy:before {
    content: "\f091"
}

.fa-truck:before {
    content: "\f0d1"
}

.fa-truck-loading:before {
    content: "\f4de"
}

.fa-truck-monster:before {
    content: "\f63b"
}

.fa-truck-moving:before {
    content: "\f4df"
}

.fa-truck-pickup:before {
    content: "\f63c"
}

.fa-tshirt:before {
    content: "\f553"
}

.fa-tty:before {
    content: "\f1e4"
}

.fa-tumblr:before {
    content: "\f173"
}

.fa-tumblr-square:before {
    content: "\f174"
}

.fa-tv:before {
    content: "\f26c"
}

.fa-twitch:before {
    content: "\f1e8"
}

.fa-twitter:before {
    content: "\f099"
}

.fa-twitter-square:before {
    content: "\f081"
}

.fa-typo3:before {
    content: "\f42b"
}

.fa-uber:before {
    content: "\f402"
}

.fa-ubuntu:before {
    content: "\f7df"
}

.fa-uikit:before {
    content: "\f403"
}

.fa-umbraco:before {
    content: "\f8e8"
}

.fa-umbrella:before {
    content: "\f0e9"
}

.fa-umbrella-beach:before {
    content: "\f5ca"
}

.fa-uncharted:before {
    content: "\e084"
}

.fa-underline:before {
    content: "\f0cd"
}

.fa-undo:before {
    content: "\f0e2"
}

.fa-undo-alt:before {
    content: "\f2ea"
}

.fa-uniregistry:before {
    content: "\f404"
}

.fa-unity:before {
    content: "\e049"
}

.fa-universal-access:before {
    content: "\f29a"
}

.fa-university:before {
    content: "\f19c"
}

.fa-unlink:before {
    content: "\f127"
}

.fa-unlock:before {
    content: "\f09c"
}

.fa-unlock-alt:before {
    content: "\f13e"
}

.fa-unsplash:before {
    content: "\e07c"
}

.fa-untappd:before {
    content: "\f405"
}

.fa-upload:before {
    content: "\f093"
}

.fa-ups:before {
    content: "\f7e0"
}

.fa-usb:before {
    content: "\f287"
}

.fa-user:before {
    content: "\f007"
}

.fa-user-alt:before {
    content: "\f406"
}

.fa-user-alt-slash:before {
    content: "\f4fa"
}

.fa-user-astronaut:before {
    content: "\f4fb"
}

.fa-user-check:before {
    content: "\f4fc"
}

.fa-user-circle:before {
    content: "\f2bd"
}

.fa-user-clock:before {
    content: "\f4fd"
}

.fa-user-cog:before {
    content: "\f4fe"
}

.fa-user-edit:before {
    content: "\f4ff"
}

.fa-user-friends:before {
    content: "\f500"
}

.fa-user-graduate:before {
    content: "\f501"
}

.fa-user-injured:before {
    content: "\f728"
}

.fa-user-lock:before {
    content: "\f502"
}

.fa-user-md:before {
    content: "\f0f0"
}

.fa-user-minus:before {
    content: "\f503"
}

.fa-user-ninja:before {
    content: "\f504"
}

.fa-user-nurse:before {
    content: "\f82f"
}

.fa-user-plus:before {
    content: "\f234"
}

.fa-user-secret:before {
    content: "\f21b"
}

.fa-user-shield:before {
    content: "\f505"
}

.fa-user-slash:before {
    content: "\f506"
}

.fa-user-tag:before {
    content: "\f507"
}

.fa-user-tie:before {
    content: "\f508"
}

.fa-user-times:before {
    content: "\f235"
}

.fa-users:before {
    content: "\f0c0"
}

.fa-users-cog:before {
    content: "\f509"
}

.fa-users-slash:before {
    content: "\e073"
}

.fa-usps:before {
    content: "\f7e1"
}

.fa-ussunnah:before {
    content: "\f407"
}

.fa-utensil-spoon:before {
    content: "\f2e5"
}

.fa-utensils:before {
    content: "\f2e7"
}

.fa-vaadin:before {
    content: "\f408"
}

.fa-vector-square:before {
    content: "\f5cb"
}

.fa-venus:before {
    content: "\f221"
}

.fa-venus-double:before {
    content: "\f226"
}

.fa-venus-mars:before {
    content: "\f228"
}

.fa-vest:before {
    content: "\e085"
}

.fa-vest-patches:before {
    content: "\e086"
}

.fa-viacoin:before {
    content: "\f237"
}

.fa-viadeo:before {
    content: "\f2a9"
}

.fa-viadeo-square:before {
    content: "\f2aa"
}

.fa-vial:before {
    content: "\f492"
}

.fa-vials:before {
    content: "\f493"
}

.fa-viber:before {
    content: "\f409"
}

.fa-video:before {
    content: "\f03d"
}

.fa-video-slash:before {
    content: "\f4e2"
}

.fa-vihara:before {
    content: "\f6a7"
}

.fa-vimeo:before {
    content: "\f40a"
}

.fa-vimeo-square:before {
    content: "\f194"
}

.fa-vimeo-v:before {
    content: "\f27d"
}

.fa-vine:before {
    content: "\f1ca"
}

.fa-virus:before {
    content: "\e074"
}

.fa-virus-slash:before {
    content: "\e075"
}

.fa-viruses:before {
    content: "\e076"
}

.fa-vk:before {
    content: "\f189"
}

.fa-vnv:before {
    content: "\f40b"
}

.fa-voicemail:before {
    content: "\f897"
}

.fa-volleyball-ball:before {
    content: "\f45f"
}

.fa-volume-down:before {
    content: "\f027"
}

.fa-volume-mute:before {
    content: "\f6a9"
}

.fa-volume-off:before {
    content: "\f026"
}

.fa-volume-up:before {
    content: "\f028"
}

.fa-vote-yea:before {
    content: "\f772"
}

.fa-vr-cardboard:before {
    content: "\f729"
}

.fa-vuejs:before {
    content: "\f41f"
}

.fa-walking:before {
    content: "\f554"
}

.fa-wallet:before {
    content: "\f555"
}

.fa-warehouse:before {
    content: "\f494"
}

.fa-watchman-monitoring:before {
    content: "\e087"
}

.fa-water:before {
    content: "\f773"
}

.fa-wave-square:before {
    content: "\f83e"
}

.fa-waze:before {
    content: "\f83f"
}

.fa-weebly:before {
    content: "\f5cc"
}

.fa-weibo:before {
    content: "\f18a"
}

.fa-weight:before {
    content: "\f496"
}

.fa-weight-hanging:before {
    content: "\f5cd"
}

.fa-weixin:before {
    content: "\f1d7"
}

.fa-whatsapp:before {
    content: "\f232"
}

.fa-whatsapp-square:before {
    content: "\f40c"
}

.fa-wheelchair:before {
    content: "\f193"
}

.fa-whmcs:before {
    content: "\f40d"
}

.fa-wifi:before {
    content: "\f1eb"
}

.fa-wikipedia-w:before {
    content: "\f266"
}

.fa-wind:before {
    content: "\f72e"
}

.fa-window-close:before {
    content: "\f410"
}

.fa-window-maximize:before {
    content: "\f2d0"
}

.fa-window-minimize:before {
    content: "\f2d1"
}

.fa-window-restore:before {
    content: "\f2d2"
}

.fa-windows:before {
    content: "\f17a"
}

.fa-wine-bottle:before {
    content: "\f72f"
}

.fa-wine-glass:before {
    content: "\f4e3"
}

.fa-wine-glass-alt:before {
    content: "\f5ce"
}

.fa-wix:before {
    content: "\f5cf"
}

.fa-wizards-of-the-coast:before {
    content: "\f730"
}

.fa-wodu:before {
    content: "\e088"
}

.fa-wolf-pack-battalion:before {
    content: "\f514"
}

.fa-won-sign:before {
    content: "\f159"
}

.fa-wordpress:before {
    content: "\f19a"
}

.fa-wordpress-simple:before {
    content: "\f411"
}

.fa-wpbeginner:before {
    content: "\f297"
}

.fa-wpexplorer:before {
    content: "\f2de"
}

.fa-wpforms:before {
    content: "\f298"
}

.fa-wpressr:before {
    content: "\f3e4"
}

.fa-wrench:before {
    content: "\f0ad"
}

.fa-x-ray:before {
    content: "\f497"
}

.fa-xbox:before {
    content: "\f412"
}

.fa-xing:before {
    content: "\f168"
}

.fa-xing-square:before {
    content: "\f169"
}

.fa-y-combinator:before {
    content: "\f23b"
}

.fa-yahoo:before {
    content: "\f19e"
}

.fa-yammer:before {
    content: "\f840"
}

.fa-yandex:before {
    content: "\f413"
}

.fa-yandex-international:before {
    content: "\f414"
}

.fa-yarn:before {
    content: "\f7e3"
}

.fa-yelp:before {
    content: "\f1e9"
}

.fa-yen-sign:before {
    content: "\f157"
}

.fa-yin-yang:before {
    content: "\f6ad"
}

.fa-yoast:before {
    content: "\f2b1"
}

.fa-youtube:before {
    content: "\f167"
}

.fa-youtube-square:before {
    content: "\f431"
}

.fa-zhihu:before {
    content: "\f63f"
}

.sr-only {
    clip: rect(0, 0, 0, 0);
    border: 0;
    height: 1px;
    margin: -1px;
    overflow: hidden;
    padding: 0;
    position: absolute;
    width: 1px
}

.sr-only-focusable:active,
.sr-only-focusable:focus {
    clip: auto;
    height: auto;
    margin: 0;
    overflow: visible;
    position: static;
    width: auto
}

/*!
 * Font Awesome Free 5.15.4 by @fontawesome - https://fontawesome.com
 * License - https://fontawesome.com/license/free (Icons: CC BY 4.0, Fonts: SIL OFL 1.1, Code: MIT License)
 */

@font-face {
    font-display: block;
    font-family: Font Awesome\ 5 Brands;
    font-style: normal;
    font-weight: 400;
    src: url(../fonts/vendor/@fortawesome/fontawesome-free/webfa-brands-400.eot?23f19bb08961f37aaf692ff943823453);
    src: url(../fonts/vendor/@fortawesome/fontawesome-free/webfa-brands-400.eot?23f19bb08961f37aaf692ff943823453) format("embedded-opentype"), url(../fonts/vendor/@fortawesome/fontawesome-free/webfa-brands-400.woff2?d878b0a6a1144760244ff0665888404c) format("woff2"), url(../fonts/vendor/@fortawesome/fontawesome-free/webfa-brands-400.woff?2285773e6b4b172f07d9b777c81b0775) format("woff"), url(../fonts/vendor/@fortawesome/fontawesome-free/webfa-brands-400.ttf?527940b104eb2ea366c8630f3f038603) format("truetype"), url(../fonts/vendor/@fortawesome/fontawesome-free/webfa-brands-400.svg?2f517e09eb2ca6650ff5bec5a95157ab) format("svg")
}

.fab {
    font-family: Font Awesome\ 5 Brands;
    font-weight: 400
}

/*!
 * Font Awesome Free 5.15.4 by @fontawesome - https://fontawesome.com
 * License - https://fontawesome.com/license/free (Icons: CC BY 4.0, Fonts: SIL OFL 1.1, Code: MIT License)
 */

@font-face {
    font-display: block;
    font-family: Font Awesome\ 5 Free;
    font-style: normal;
    font-weight: 900;
    src: url(../fonts/vendor/@fortawesome/fontawesome-free/webfa-solid-900.eot?9bbb245e67a133f6e486d8d2545e14a5);
    src: url(../fonts/vendor/@fortawesome/fontawesome-free/webfa-solid-900.eot?9bbb245e67a133f6e486d8d2545e14a5) format("embedded-opentype"), url(../fonts/vendor/@fortawesome/fontawesome-free/webfa-solid-900.woff2?1551f4f60c37af51121f106501f69b80) format("woff2"), url(../fonts/vendor/@fortawesome/fontawesome-free/webfa-solid-900.woff?eeccf4f66002c6f2ba24d3d22f2434c2) format("woff"), url(../fonts/vendor/@fortawesome/fontawesome-free/webfa-solid-900.ttf?be9ee23c0c6390141475d519c2c5fb8f) format("truetype"), url(../fonts/vendor/@fortawesome/fontawesome-free/webfa-solid-900.svg?7a8b4f130182d19a2d7c67d80c090397) format("svg")
}

.fa,
.fas {
    font-family: Font Awesome\ 5 Free;
    font-weight: 900
}

.kanban-container {
    position: relative;
    width: auto
}

.kanban-container,
.kanban-container * {
    box-sizing: border-box
}

.kanban-container:after {
    clear: both;
    content: "";
    display: block
}

.kanban-board {
    background: #e2e4e6;
    float: left;
    position: relative;
    transition: all .3s cubic-bezier(.23, 1, .32, 1)
}

.kanban-board.disabled-board {
    opacity: .3
}

.kanban-board.is-moving.gu-mirror {
    transform: rotate(3deg)
}

.kanban-board.is-moving.gu-mirror .kanban-drag {
    overflow: hidden;
    padding-right: 50px
}

.kanban-board header {
    font-size: 16px;
    padding: 15px
}

.kanban-board header .kanban-title-board {
    display: inline;
    font-weight: 700;
    margin: 0;
    padding: 0
}

.kanban-board header .kanban-title-button {
    float: right
}

.kanban-board .kanban-drag {
    min-height: 200px;
    padding: 20px
}

.kanban-board:after {
    clear: both;
    content: "";
    display: block
}

.kanban-item {
    background: #fff;
    margin-bottom: 20px;
    padding: 15px;
    transition: all .3s cubic-bezier(.23, 1, .32, 1)
}

.kanban-item:hover {
    cursor: move
}

.kanban-item:last-child {
    margin: 0
}

.kanban-item.is-moving.gu-mirror {
    height: auto !important;
    transform: rotate(3deg)
}

.gu-mirror {
    margin: 0 !important;
    position: fixed !important;
    z-index: 9999 !important
}

.gu-hide {
    display: none !important
}

.gu-unselectable {
    -webkit-user-select: none !important;
    -moz-user-select: none !important;
    user-select: none !important
}

.gu-transit {
    opacity: .2 !important;
    transform: rotate(0) !important
}

.drag_handler {
    background: #fff;
    border-radius: 50%;
    float: left;
    height: 24px;
    margin-right: 4px;
    position: relative;
    top: -3px;
    width: 24px
}

.drag_handler:hover {
    cursor: move
}

.drag_handler_icon {
    background: #000;
    display: block;
    height: 2px;
    position: relative;
    top: 12px;
    transition: .5s ease-in-out;
    width: 24px
}

.drag_handler_icon:after,
.drag_handler_icon:before {
    background: #000;
    content: "";
    display: block;
    height: 100%;
    position: absolute;
    transition: .5s ease-in-out;
    width: 100%
}

.drag_handler_icon:before {
    top: 6px
}

.drag_handler_icon:after {
    bottom: 6px
}

.ps {
    -ms-overflow-style: none;
    overflow: hidden !important;
    overflow-anchor: none;
    touch-action: auto;
    -ms-touch-action: auto
}

.ps__rail-x {
    bottom: 0;
    height: 15px
}

.ps__rail-x,
.ps__rail-y {
    display: none;
    opacity: 0;
    position: absolute;
    transition: background-color .2s linear, opacity .2s linear;
    -webkit-transition: background-color .2s linear, opacity .2s linear
}

.ps__rail-y {
    right: 0;
    width: 15px
}

.ps--active-x>.ps__rail-x,
.ps--active-y>.ps__rail-y {
    background-color: transparent;
    display: block
}

.ps--focus>.ps__rail-x,
.ps--focus>.ps__rail-y,
.ps--scrolling-x>.ps__rail-x,
.ps--scrolling-y>.ps__rail-y,
.ps:hover>.ps__rail-x,
.ps:hover>.ps__rail-y {
    opacity: .6
}

.ps .ps__rail-x.ps--clicking,
.ps .ps__rail-x:focus,
.ps .ps__rail-x:hover,
.ps .ps__rail-y.ps--clicking,
.ps .ps__rail-y:focus,
.ps .ps__rail-y:hover {
    background-color: #eee;
    opacity: .9
}

.ps__thumb-x {
    bottom: 2px;
    height: 6px;
    transition: background-color .2s linear, height .2s ease-in-out;
    -webkit-transition: background-color .2s linear, height .2s ease-in-out
}

.ps__thumb-x,
.ps__thumb-y {
    background-color: #aaa;
    border-radius: 6px;
    position: absolute
}

.ps__thumb-y {
    right: 2px;
    transition: background-color .2s linear, width .2s ease-in-out;
    -webkit-transition: background-color .2s linear, width .2s ease-in-out;
    width: 6px
}

.ps__rail-x.ps--clicking .ps__thumb-x,
.ps__rail-x:focus>.ps__thumb-x,
.ps__rail-x:hover>.ps__thumb-x {
    background-color: #999;
    height: 11px
}

.ps__rail-y.ps--clicking .ps__thumb-y,
.ps__rail-y:focus>.ps__thumb-y,
.ps__rail-y:hover>.ps__thumb-y {
    background-color: #999;
    width: 11px
}

@supports (-ms-overflow-style:none) {
    .ps {
        overflow: auto !important
    }
}

@media (-ms-high-contrast:none),
screen and (-ms-high-contrast:active) {
    .ps {
        overflow: auto !important
    }
}

.patt-holder {
    background: #3382c0;
    -ms-touch-action: none
}

.patt-wrap {
    cursor: pointer;
    position: relative
}

.patt-wrap li,
.patt-wrap ul {
    list-style: none;
    margin: 0;
    padding: 0
}

.patt-circ {
    box-sizing: border-box;
    float: left;
    position: relative
}

.patt-circ.hovered {
    border: 3px solid #090
}

.patt-error .patt-circ.hovered {
    border: 3px solid #ba1b26
}

.patt-hidden .patt-circ.hovered {
    border: 0
}

.patt-dots {
    background: #fff;
    left: 50%;
    margin-left: -5px;
    margin-top: -5px;
    top: 50%;
    width: 10px
}

.patt-dots,
.patt-lines {
    border-radius: 5px;
    height: 10px;
    position: absolute
}

.patt-lines {
    background: hsla(0, 0%, 100%, .7);
    -ms-transform-origin: 5px 5px;
    -webkit-transform-origin: 5px 5px;
    transform-origin: 5px 5px
}

.patt-hidden .patt-lines {
    display: none
}

:root {
    --tagify-dd-color-primary: #3595f6;
    --tagify-dd-bg-color: #fff
}

.tagify {
    --tags-border-color: #ddd;
    --tags-hover-border-color: #ccc;
    --tags-focus-border-color: #3595f6;
    --tag-bg: #e5e5e5;
    --tag-hover: #d3e2e2;
    --tag-text-color: #000;
    --tag-text-color--edit: #000;
    --tag-pad: 0.3em 0.5em;
    --tag-inset-shadow-size: 1.1em;
    --tag-invalid-color: #d39494;
    --tag-invalid-bg: hsla(0, 42%, 70%, .5);
    --tag-remove-bg: hsla(0, 42%, 70%, .3);
    --tag-remove-btn-color: #000;
    --tag-remove-btn-bg: none;
    --tag-remove-btn-bg--hover: #c77777;
    --input-color: inherit;
    --tag--min-width: 1ch;
    --tag--max-width: auto;
    --tag-hide-transition: 0.3s;
    --placeholder-color: rgba(0, 0, 0, .4);
    --placeholder-color-focus: rgba(0, 0, 0, .25);
    --loader-size: .8em;
    align-items: flex-start;
    border: 1px solid #ddd;
    border: 1px solid var(--tags-border-color);
    box-sizing: border-box;
    cursor: text;
    display: flex;
    flex-wrap: wrap;
    line-height: normal;
    outline: 0;
    padding: 0;
    position: relative;
    transition: .1s
}

@keyframes tags--bump {
    30% {
        transform: scale(1.2)
    }
}

@keyframes rotateLoader {
    to {
        transform: rotate(1turn)
    }
}

.tagify:hover {
    border-color: #ccc;
    border-color: var(--tags-hover-border-color)
}

.tagify.tagify--focus {
    border-color: #3595f6;
    border-color: var(--tags-focus-border-color);
    transition: 0s
}

.tagify[readonly]:not(.tagify--mix) {
    cursor: default
}

.tagify[readonly]:not(.tagify--mix)>.tagify__input {
    margin: 5px 0;
    visibility: hidden;
    width: 0
}

.tagify[readonly]:not(.tagify--mix) .tagify__tag>div {
    padding: .3em .5em;
    padding: var(--tag-pad)
}

.tagify[readonly]:not(.tagify--mix) .tagify__tag>div:before {
    background: linear-gradient(45deg, var(--tag-bg) 25%, transparent 25%, transparent 50%, var(--tag-bg) 50%, var(--tag-bg) 75%, transparent 75%, transparent) 0/5px 5px;
    box-shadow: none;
    filter: brightness(.95)
}

.tagify[readonly] .tagify__tag__removeBtn {
    display: none
}

.tagify--loading .tagify__input:before {
    content: none
}

.tagify--loading .tagify__input:after {
    animation: rotateLoader .4s linear infinite;
    border-color: #eee #bbb #888 transparent;
    border-radius: 50%;
    border-style: solid;
    border-width: 3px;
    content: "";
    height: .7em;
    height: var(--loader-size);
    margin: -2px 0 -2px .5em;
    opacity: 1;
    vertical-align: middle;
    width: .7em;
    width: var(--loader-size)
}

.tagify--loading .tagify__input:empty:after {
    margin-left: 0
}

.tagify+input,
.tagify+textarea {
    display: none !important
}

.tagify__tag {
    align-items: center;
    cursor: default;
    display: inline-flex;
    margin: 5px 0 5px 5px;
    outline: 0;
    position: relative;
    transition: .13s ease-out;
    z-index: 1
}

.tagify__tag>div {
    border-radius: 3px;
    box-sizing: border-box;
    color: #000;
    color: var(--tag-text-color, #000);
    line-height: inherit;
    max-width: 100%;
    padding: .3em .5em;
    padding: var(--tag-pad, .3em .5em);
    transition: .13s ease-out;
    vertical-align: top;
    white-space: nowrap
}

.tagify__tag>div>* {
    display: inline-block;
    max-width: auto;
    max-width: var(--tag--max-width, auto);
    min-width: 1ch;
    min-width: var(--tag--min-width, 1ch);
    overflow: hidden;
    text-overflow: ellipsis;
    transition: .8s ease, color .1s;
    vertical-align: top;
    white-space: pre-wrap
}

.tagify__tag>div>[contenteditable] {
    cursor: text;
    margin: -2px;
    max-width: 350px;
    outline: 0;
    padding: 2px;
    -webkit-user-select: text;
    -moz-user-select: text;
    user-select: text
}

.tagify__tag>div:before {
    animation: tags--bump .3s ease-out 1;
    border-radius: inherit;
    bottom: 0;
    box-shadow: inset 0 0 0 1.1em #e5e5e5;
    box-shadow: 0 0 0 var(--tag-inset-shadow-size, 1.1em) var(--tag-bg, #e5e5e5) inset;
    content: "";
    left: 0;
    pointer-events: none;
    position: absolute;
    right: 0;
    top: 0;
    transition: .12s ease;
    z-index: -1
}

.tagify__tag:hover:not([readonly]) div:before {
    bottom: -2px;
    box-shadow: inset 0 0 0 1.1em #d3e2e2;
    box-shadow: 0 0 0 var(--tag-inset-shadow-size, 1.1em) var(--tag-hover, #d3e2e2) inset;
    left: -2px;
    right: -2px;
    top: -2px
}

.tagify__tag--loading {
    pointer-events: none
}

.tagify__tag--loading .tagify__tag__removeBtn {
    display: none
}

.tagify__tag--loading:after {
    --loader-size: .4em;
    animation: rotateLoader .4s linear infinite;
    border-color: #eee #bbb #888 transparent;
    border-radius: 50%;
    border-style: solid;
    border-width: 3px;
    content: "";
    height: .7em;
    height: var(--loader-size);
    margin: 0 .5em 0 -.1em;
    opacity: 1;
    vertical-align: middle;
    width: .7em;
    width: var(--loader-size)
}

.tagify__tag--flash div:before {
    animation: none
}

.tagify__tag--hide {
    margin-left: 0;
    margin-right: 0;
    opacity: 0;
    padding-left: 0;
    padding-right: 0;
    pointer-events: none;
    transform: scale(0);
    transition: .3s;
    transition: var(--tag-hide-transition, .3s);
    width: 0 !important
}

.tagify__tag--hide>div>* {
    white-space: nowrap
}

.tagify__tag.tagify--noAnim>div:before {
    animation: none
}

.tagify__tag.tagify--notAllowed:not(.tagify__tag--editable) div>span {
    opacity: .5
}

.tagify__tag.tagify--notAllowed:not(.tagify__tag--editable) div:before {
    box-shadow: inset 0 0 0 1.1em hsla(0, 42%, 70%, .5) !important;
    box-shadow: 0 0 0 var(--tag-inset-shadow-size, 1.1em) var(--tag-invalid-bg, hsla(0, 42%, 70%, .5)) inset !important;
    transition: .2s
}

.tagify__tag[readonly] .tagify__tag__removeBtn {
    display: none
}

.tagify__tag[readonly]>div:before {
    background: linear-gradient(45deg, var(--tag-bg) 25%, transparent 25%, transparent 50%, var(--tag-bg) 50%, var(--tag-bg) 75%, transparent 75%, transparent) 0/5px 5px;
    box-shadow: none;
    filter: brightness(.95)
}

.tagify__tag--editable>div {
    color: #000;
    color: var(--tag-text-color--edit, #000)
}

.tagify__tag--editable>div:before {
    box-shadow: inset 0 0 0 2px #d3e2e2 !important;
    box-shadow: 0 0 0 2px var(--tag-hover, #d3e2e2) inset !important
}

.tagify__tag--editable>.tagify__tag__removeBtn {
    pointer-events: none
}

.tagify__tag--editable>.tagify__tag__removeBtn:after {
    opacity: 0;
    transform: translateX(100%) translateX(5px)
}

.tagify__tag--editable.tagify--invalid>div:before {
    box-shadow: inset 0 0 0 2px #d39494 !important;
    box-shadow: 0 0 0 2px var(--tag-invalid-color, #d39494) inset !important
}

.tagify__tag__removeBtn {
    align-items: center;
    background: 0 0;
    background: var(--tag-remove-btn-bg, none);
    border-radius: 50px;
    color: #000;
    color: var(--tag-remove-btn-color, #000);
    cursor: pointer;
    display: inline-flex;
    font: 14px/1 Arial;
    height: 14px;
    justify-content: center;
    margin-left: -4.66667px;
    margin-right: 4.66667px;
    order: 5;
    overflow: hidden;
    transition: .2s ease-out;
    width: 14px
}

.tagify__tag__removeBtn:after {
    content: "×";
    transition: .3s, color 0s
}

.tagify__tag__removeBtn:hover {
    background: #c77777;
    background: var(--tag-remove-btn-bg--hover, #c77777);
    color: #fff
}

.tagify__tag__removeBtn:hover+div>span {
    opacity: .5
}

.tagify__tag__removeBtn:hover+div:before {
    box-shadow: inset 0 0 0 1.1em hsla(0, 42%, 70%, .3) !important;
    box-shadow: 0 0 0 var(--tag-inset-shadow-size, 1.1em) var(--tag-remove-bg, hsla(0, 42%, 70%, .3)) inset !important;
    transition: box-shadow .2s
}

.tagify:not(.tagify--mix) .tagify__input br {
    display: none
}

.tagify:not(.tagify--mix) .tagify__input * {
    display: inline;
    white-space: nowrap
}

.tagify__input {
    box-sizing: inherit;
    color: inherit;
    color: var(--input-color, inherit);
    display: inline-block;
    flex-grow: 1;
    line-height: inherit;
    margin: 5px;
    min-width: 110px;
    padding: .3em .5em;
    padding: var(--tag-pad, .3em .5em);
    position: relative;
    white-space: pre-wrap
}

.tagify__input:empty:before {
    display: inline-block;
    opacity: 1;
    transform: none;
    transition: .2s ease-out;
    width: auto
}

.tagify--mix .tagify__input:empty:before {
    display: inline-block
}

.tagify__input:focus {
    outline: 0
}

.tagify__input:focus:before {
    opacity: 0;
    transform: translatex(6px);
    transition: .2s ease-out
}

@media (-ms-high-contrast:active),
(-ms-high-contrast:none) {
    .tagify__input:focus:before {
        display: none
    }
}

@supports (-ms-ime-align:auto) {
    .tagify__input:focus:before {
        display: none
    }
}

.tagify__input:focus:empty:before {
    color: rgba(0, 0, 0, .25);
    color: var(--placeholder-color-focus);
    opacity: 1;
    transform: none;
    transition: .2s ease-out
}

@-moz-document url-prefix() {
    .tagify__input:focus:empty:after {
        display: none
    }
}

.tagify__input:before {
    color: rgba(0, 0, 0, .4);
    color: var(--placeholder-color);
    content: attr(data-placeholder);
    height: 1em;
    line-height: 1em;
    margin: auto 0;
    opacity: 0;
    pointer-events: none;
    position: absolute;
    white-space: nowrap;
    z-index: 1
}

.tagify--mix .tagify__input:before {
    display: none;
    line-height: inherit;
    position: static
}

.tagify__input:after {
    color: #000;
    content: attr(data-suggest);
    display: inline-block;
    max-width: 100px;
    opacity: .3;
    pointer-events: none;
    white-space: pre
}

.tagify__input .tagify__tag {
    margin: 0
}

.tagify__input .tagify__tag>div {
    padding-bottom: 0;
    padding-top: 0
}

.tagify--mix {
    display: block
}

.tagify--mix .tagify__input {
    display: block;
    height: 100%;
    line-height: 1.5;
    margin: 0;
    padding: 5px;
    width: 100%
}

.tagify--mix .tagify__input:before {
    height: auto
}

.tagify--mix .tagify__input:after {
    content: none
}

.tagify--select:after {
    bottom: 0;
    content: ">";
    font: 16px monospace;
    height: 8px;
    line-height: 8px;
    opacity: .5;
    pointer-events: none;
    position: absolute;
    right: 0;
    top: 50%;
    transform: translate(-150%, -50%) scaleX(1.2) rotate(90deg);
    transition: .2s ease-in-out
}

.tagify--select[aria-expanded=true]:after {
    transform: translate(-150%, -50%) rotate(270deg) scaleY(1.2)
}

.tagify--select .tagify__tag {
    bottom: 0;
    position: absolute;
    right: 1.8em;
    top: 0
}

.tagify--select .tagify__tag div {
    display: none
}

.tagify--select .tagify__input {
    width: 100%
}

.tagify--invalid {
    --tags-border-color: #d39494
}

.tagify__dropdown {
    overflow: hidden;
    position: absolute;
    transform: translateY(1px);
    z-index: 9999
}

.tagify__dropdown[placement=top] {
    margin-top: 0;
    transform: translateY(-100%)
}

.tagify__dropdown[placement=top] .tagify__dropdown__wrapper {
    border-bottom-width: 0;
    border-top-width: 1px
}

.tagify__dropdown[position=text] {
    box-shadow: 0 0 0 3px rgba(var(--tagify-dd-color-primary), .1);
    font-size: .9em
}

.tagify__dropdown[position=text] .tagify__dropdown__wrapper {
    border-width: 1px
}

.tagify__dropdown__wrapper {
    background: #fff;
    background: var(--tagify-dd-bg-color);
    border: 1px solid #3595f6;
    border-color: var(--tagify-dd-color-primary);
    border-width: 0 1.1px 1.1px;
    box-shadow: 0 2px 4px -2px rgba(0, 0, 0, .2);
    max-height: 300px;
    overflow: hidden;
    transition: .25s cubic-bezier(0, 1, .5, 1)
}

.tagify__dropdown__wrapper:hover {
    overflow: auto
}

.tagify__dropdown--initial .tagify__dropdown__wrapper {
    max-height: 20px;
    transform: translateY(-1em)
}

.tagify__dropdown--initial[placement=top] .tagify__dropdown__wrapper {
    transform: translateY(2em)
}

.tagify__dropdown__item {
    border-radius: 2px;
    box-sizing: inherit;
    cursor: pointer;
    margin: 1px;
    outline: 0;
    padding: .3em .5em;
    position: relative
}

.tagify__dropdown__item--active {
    background: #3595f6;
    background: var(--tagify-dd-color-primary);
    color: #fff
}

.tagify__dropdown__item:active {
    filter: brightness(105%)
}

.pace {
    -webkit-pointer-events: none;
    pointer-events: none;
    -webkit-user-select: none;
    -moz-user-select: none;
    user-select: none
}

.pace-inactive {
    display: none
}

.pace .pace-progress {
    background: #fff;
    position: fixed;
    z-index: 2000;
    top: 0;
    right: 100%;
    width: 100%;
    height: 2px
}

.pace .pace-progress-inner {
    display: block;
    position: absolute;
    right: 0;
    width: 100px;
    height: 100%;
    box-shadow: 0 0 10px #fff, 0 0 5px #fff;
    opacity: 1;
    -webkit-transform: rotate(3deg) translate(0, -4px);
    -moz-transform: rotate(3deg) translate(0, -4px);
    -ms-transform: rotate(3deg) translate(0, -4px);
    -o-transform: rotate(3deg) translate(0, -4px);
    transform: rotate(3deg) translate(0, -4px)
}

.pace .pace-activity {
    display: block;
    position: fixed;
    z-index: 2000;
    top: 15px;
    right: 50%;
    width: 14px;
    height: 14px;
    border: solid 2px transparent;
    border-top-color: #fff;
    border-left-color: #fff;
    border-radius: 10px;
    -webkit-animation: pace-spinner .4s linear infinite;
    -moz-animation: pace-spinner .4s linear infinite;
    -ms-animation: pace-spinner 400ms linear infinite;
    -o-animation: pace-spinner .4s linear infinite;
    animation: pace-spinner .4s linear infinite
}

@media (max-width:767px) {
    .pace .pace-activity {
        top: 15px;
        right: 15px;
        width: 14px;
        height: 14px
    }
}

@-webkit-keyframes pace-spinner {
    0% {
        -webkit-transform: rotate(0);
        transform: rotate(0)
    }
    100% {
        -webkit-transform: rotate(360deg);
        transform: rotate(360deg)
    }
}

@-moz-keyframes pace-spinner {
    0% {
        -moz-transform: rotate(0);
        transform: rotate(0)
    }
    100% {
        -moz-transform: rotate(360deg);
        transform: rotate(360deg)
    }
}

@-o-keyframes pace-spinner {
    0% {
        -o-transform: rotate(0);
        transform: rotate(0)
    }
    100% {
        -o-transform: rotate(360deg);
        transform: rotate(360deg)
    }
}

@-ms-keyframes pace-spinner {
    0% {
        -ms-transform: rotate(0);
        transform: rotate(0)
    }
    100% {
        -ms-transform: rotate(360deg);
        transform: rotate(360deg)
    }
}

@keyframes pace-spinner {
    0% {
        transform: rotate(0);
        transform: rotate(0)
    }
    100% {
        transform: rotate(360deg);
        transform: rotate(360deg)
    }
}

/*! jQuery UI - v1.12.1 - 2018-01-21
* http://jqueryui.com
* Includes: draggable.css, core.css, resizable.css, selectable.css, sortable.css, accordion.css, autocomplete.css, menu.css, button.css, controlgroup.css, checkboxradio.css, datepicker.css, dialog.css, progressbar.css, selectmenu.css, slider.css, spinner.css, tabs.css, tooltip.css, theme.css
* To view and modify this theme, visit http://jqueryui.com/themeroller/?scope=&folderName=base&cornerRadiusShadow=8px&offsetLeftShadow=0px&offsetTopShadow=0px&thicknessShadow=5px&opacityShadow=30&bgImgOpacityShadow=0&bgTextureShadow=flat&bgColorShadow=666666&opacityOverlay=30&bgImgOpacityOverlay=0&bgTextureOverlay=flat&bgColorOverlay=aaaaaa&iconColorError=cc0000&fcError=5f3f3f&borderColorError=f1a899&bgTextureError=flat&bgColorError=fddfdf&iconColorHighlight=777620&fcHighlight=777620&borderColorHighlight=dad55e&bgTextureHighlight=flat&bgColorHighlight=fffa90&iconColorActive=ffffff&fcActive=ffffff&borderColorActive=003eff&bgTextureActive=flat&bgColorActive=007fff&iconColorHover=555555&fcHover=2b2b2b&borderColorHover=cccccc&bgTextureHover=flat&bgColorHover=ededed&iconColorDefault=777777&fcDefault=454545&borderColorDefault=c5c5c5&bgTextureDefault=flat&bgColorDefault=f6f6f6&iconColorContent=444444&fcContent=333333&borderColorContent=dddddd&bgTextureContent=flat&bgColorContent=ffffff&iconColorHeader=444444&fcHeader=333333&borderColorHeader=dddddd&bgTextureHeader=flat&bgColorHeader=e9e9e9&cornerRadius=3px&fwDefault=normal&fsDefault=1em&ffDefault=Arial%2CHelvetica%2Csans-serif
* Copyright jQuery Foundation and other contributors; Licensed MIT */

.ui-draggable-handle {
    -ms-touch-action: none;
    touch-action: none
}

.ui-helper-hidden {
    display: none
}

.ui-helper-hidden-accessible {
    border: 0;
    clip: rect(0 0 0 0);
    height: 1px;
    margin: -1px;
    overflow: hidden;
    padding: 0;
    position: absolute;
    width: 1px
}

.ui-helper-reset {
    margin: 0;
    padding: 0;
    border: 0;
    outline: 0;
    line-height: 1.3;
    text-decoration: none;
    font-size: 100%;
    list-style: none
}

.ui-helper-clearfix:after,
.ui-helper-clearfix:before {
    content: "";
    display: table;
    border-collapse: collapse
}

.ui-helper-clearfix:after {
    clear: both
}

.ui-helper-zfix {
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    position: absolute;
    opacity: 0;
    filter: Alpha(Opacity=0)
}

.ui-front {
    z-index: 100
}

.ui-state-disabled {
    cursor: default !important;
    pointer-events: none
}

.ui-icon {
    display: inline-block;
    vertical-align: middle;
    margin-top: -.25em;
    position: relative;
    text-indent: -99999px;
    overflow: hidden;
    background-repeat: no-repeat
}

.ui-widget-icon-block {
    left: 50%;
    margin-left: -8px;
    display: block
}

.ui-widget-overlay {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%
}

.ui-resizable {
    position: relative
}

.ui-resizable-handle {
    position: absolute;
    font-size: .1px;
    display: block;
    -ms-touch-action: none;
    touch-action: none
}

.ui-resizable-autohide .ui-resizable-handle,
.ui-resizable-disabled .ui-resizable-handle {
    display: none
}

.ui-resizable-n {
    cursor: n-resize;
    height: 7px;
    width: 100%;
    top: -5px;
    left: 0
}

.ui-resizable-s {
    cursor: s-resize;
    height: 7px;
    width: 100%;
    bottom: -5px;
    left: 0
}

.ui-resizable-e {
    cursor: e-resize;
    width: 7px;
    right: -5px;
    top: 0;
    height: 100%
}

.ui-resizable-w {
    cursor: w-resize;
    width: 7px;
    left: -5px;
    top: 0;
    height: 100%
}

.ui-resizable-se {
    cursor: se-resize;
    width: 12px;
    height: 12px;
    right: 1px;
    bottom: 1px
}

.ui-resizable-sw {
    cursor: sw-resize;
    width: 9px;
    height: 9px;
    left: -5px;
    bottom: -5px
}

.ui-resizable-nw {
    cursor: nw-resize;
    width: 9px;
    height: 9px;
    left: -5px;
    top: -5px
}

.ui-resizable-ne {
    cursor: ne-resize;
    width: 9px;
    height: 9px;
    right: -5px;
    top: -5px
}

.ui-selectable {
    -ms-touch-action: none;
    touch-action: none
}

.ui-selectable-helper {
    position: absolute;
    z-index: 100;
    border: 1px dotted #000
}

.ui-sortable-handle {
    -ms-touch-action: none;
    touch-action: none
}

.ui-accordion .ui-accordion-header {
    display: block;
    cursor: pointer;
    position: relative;
    margin: 2px 0 0 0;
    padding: .5em .5em .5em .7em;
    font-size: 100%
}

.ui-accordion .ui-accordion-content {
    padding: 1em 2.2em;
    border-top: 0;
    overflow: auto
}

.ui-autocomplete {
    position: absolute;
    top: 0;
    left: 0;
    cursor: default
}

.ui-menu {
    list-style: none;
    padding: 0;
    margin: 0;
    display: block;
    outline: 0
}

.ui-menu .ui-menu {
    position: absolute
}

.ui-menu .ui-menu-item {
    margin: 0;
    cursor: pointer;
    list-style-image: url("data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7")
}

.ui-menu .ui-menu-item-wrapper {
    position: relative;
    padding: 3px 1em 3px .4em
}

.ui-menu .ui-menu-divider {
    margin: 5px 0;
    height: 0;
    font-size: 0;
    line-height: 0;
    border-width: 1px 0 0 0
}

.ui-menu .ui-state-active,
.ui-menu .ui-state-focus {
    margin: -1px
}

.ui-menu-icons {
    position: relative
}

.ui-menu-icons .ui-menu-item-wrapper {
    padding-left: 2em
}

.ui-menu .ui-icon {
    position: absolute;
    top: 0;
    bottom: 0;
    left: .2em;
    margin: auto 0
}

.ui-menu .ui-menu-icon {
    left: auto;
    right: 0
}

.ui-button {
    padding: .4em 1em;
    display: inline-block;
    position: relative;
    line-height: normal;
    margin-right: .1em;
    cursor: pointer;
    vertical-align: middle;
    text-align: center;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
    overflow: visible
}

.ui-button,
.ui-button:active,
.ui-button:hover,
.ui-button:link,
.ui-button:visited {
    text-decoration: none
}

.ui-button-icon-only {
    width: 2em;
    box-sizing: border-box;
    text-indent: -9999px;
    white-space: nowrap
}

input.ui-button.ui-button-icon-only {
    text-indent: 0
}

.ui-button-icon-only .ui-icon {
    position: absolute;
    top: 50%;
    left: 50%;
    margin-top: -8px;
    margin-left: -8px
}

.ui-button.ui-icon-notext .ui-icon {
    padding: 0;
    width: 2.1em;
    height: 2.1em;
    text-indent: -9999px;
    white-space: nowrap
}

input.ui-button.ui-icon-notext .ui-icon {
    width: auto;
    height: auto;
    text-indent: 0;
    white-space: normal;
    padding: .4em 1em
}

button.ui-button::-moz-focus-inner,
input.ui-button::-moz-focus-inner {
    border: 0;
    padding: 0
}

.ui-controlgroup {
    vertical-align: middle;
    display: inline-block
}

.ui-controlgroup>.ui-controlgroup-item {
    float: left;
    margin-left: 0;
    margin-right: 0
}

.ui-controlgroup>.ui-controlgroup-item.ui-visual-focus,
.ui-controlgroup>.ui-controlgroup-item:focus {
    z-index: 9999
}

.ui-controlgroup-vertical>.ui-controlgroup-item {
    display: block;
    float: none;
    width: 100%;
    margin-top: 0;
    margin-bottom: 0;
    text-align: left
}

.ui-controlgroup-vertical .ui-controlgroup-item {
    box-sizing: border-box
}

.ui-controlgroup .ui-controlgroup-label {
    padding: .4em 1em
}

.ui-controlgroup .ui-controlgroup-label span {
    font-size: 80%
}

.ui-controlgroup-horizontal .ui-controlgroup-label+.ui-controlgroup-item {
    border-left: none
}

.ui-controlgroup-vertical .ui-controlgroup-label+.ui-controlgroup-item {
    border-top: none
}

.ui-controlgroup-horizontal .ui-controlgroup-label.ui-widget-content {
    border-right: none
}

.ui-controlgroup-vertical .ui-controlgroup-label.ui-widget-content {
    border-bottom: none
}

.ui-controlgroup-vertical .ui-spinner-input {
    width: 75%;
    width: calc(100% - 2.4em)
}

.ui-controlgroup-vertical .ui-spinner .ui-spinner-up {
    border-top-style: solid
}

.ui-checkboxradio-label .ui-icon-background {
    box-shadow: inset 1px 1px 1px #ccc;
    border-radius: .12em;
    border: none
}

.ui-checkboxradio-radio-label .ui-icon-background {
    width: 16px;
    height: 16px;
    border-radius: 1em;
    overflow: visible;
    border: none
}

.ui-checkboxradio-radio-label.ui-checkboxradio-checked .ui-icon,
.ui-checkboxradio-radio-label.ui-checkboxradio-checked:hover .ui-icon {
    background-image: none;
    width: 8px;
    height: 8px;
    border-width: 4px;
    border-style: solid
}

.ui-checkboxradio-disabled {
    pointer-events: none
}

.ui-datepicker {
    width: 17em;
    padding: .2em .2em 0;
    display: none
}

.ui-datepicker .ui-datepicker-header {
    position: relative;
    padding: .2em 0
}

.ui-datepicker .ui-datepicker-next,
.ui-datepicker .ui-datepicker-prev {
    position: absolute;
    top: 2px;
    width: 1.8em;
    height: 1.8em
}

.ui-datepicker .ui-datepicker-next-hover,
.ui-datepicker .ui-datepicker-prev-hover {
    top: 1px
}

.ui-datepicker .ui-datepicker-prev {
    left: 2px
}

.ui-datepicker .ui-datepicker-next {
    right: 2px
}

.ui-datepicker .ui-datepicker-prev-hover {
    left: 1px
}

.ui-datepicker .ui-datepicker-next-hover {
    right: 1px
}

.ui-datepicker .ui-datepicker-next span,
.ui-datepicker .ui-datepicker-prev span {
    display: block;
    position: absolute;
    left: 50%;
    margin-left: -8px;
    top: 50%;
    margin-top: -8px
}

.ui-datepicker .ui-datepicker-title {
    margin: 0 2.3em;
    line-height: 1.8em;
    text-align: center
}

.ui-datepicker .ui-datepicker-title select {
    font-size: 1em;
    margin: 1px 0
}

.ui-datepicker select.ui-datepicker-month,
.ui-datepicker select.ui-datepicker-year {
    width: 45%
}

.ui-datepicker table {
    width: 100%;
    font-size: .9em;
    border-collapse: collapse;
    margin: 0 0 .4em
}

.ui-datepicker th {
    padding: .7em .3em;
    text-align: center;
    font-weight: 700;
    border: 0
}

.ui-datepicker td {
    border: 0;
    padding: 1px
}

.ui-datepicker td a,
.ui-datepicker td span {
    display: block;
    padding: .2em;
    text-align: right;
    text-decoration: none
}

.ui-datepicker .ui-datepicker-buttonpane {
    background-image: none;
    margin: .7em 0 0 0;
    padding: 0 .2em;
    border-left: 0;
    border-right: 0;
    border-bottom: 0
}

.ui-datepicker .ui-datepicker-buttonpane button {
    float: right;
    margin: .5em .2em .4em;
    cursor: pointer;
    padding: .2em .6em .3em .6em;
    width: auto;
    overflow: visible
}

.ui-datepicker .ui-datepicker-buttonpane button.ui-datepicker-current {
    float: left
}

.ui-datepicker.ui-datepicker-multi {
    width: auto
}

.ui-datepicker-multi .ui-datepicker-group {
    float: left
}

.ui-datepicker-multi .ui-datepicker-group table {
    width: 95%;
    margin: 0 auto .4em
}

.ui-datepicker-multi-2 .ui-datepicker-group {
    width: 50%
}

.ui-datepicker-multi-3 .ui-datepicker-group {
    width: 33.3%
}

.ui-datepicker-multi-4 .ui-datepicker-group {
    width: 25%
}

.ui-datepicker-multi .ui-datepicker-group-last .ui-datepicker-header,
.ui-datepicker-multi .ui-datepicker-group-middle .ui-datepicker-header {
    border-left-width: 0
}

.ui-datepicker-multi .ui-datepicker-buttonpane {
    clear: left
}

.ui-datepicker-row-break {
    clear: both;
    width: 100%;
    font-size: 0
}

.ui-datepicker-rtl {
    direction: rtl
}

.ui-datepicker-rtl .ui-datepicker-prev {
    right: 2px;
    left: auto
}

.ui-datepicker-rtl .ui-datepicker-next {
    left: 2px;
    right: auto
}

.ui-datepicker-rtl .ui-datepicker-prev:hover {
    right: 1px;
    left: auto
}

.ui-datepicker-rtl .ui-datepicker-next:hover {
    left: 1px;
    right: auto
}

.ui-datepicker-rtl .ui-datepicker-buttonpane {
    clear: right
}

.ui-datepicker-rtl .ui-datepicker-buttonpane button {
    float: left
}

.ui-datepicker-rtl .ui-datepicker-buttonpane button.ui-datepicker-current,
.ui-datepicker-rtl .ui-datepicker-group {
    float: right
}

.ui-datepicker-rtl .ui-datepicker-group-last .ui-datepicker-header,
.ui-datepicker-rtl .ui-datepicker-group-middle .ui-datepicker-header {
    border-right-width: 0;
    border-left-width: 1px
}

.ui-datepicker .ui-icon {
    display: block;
    text-indent: -99999px;
    overflow: hidden;
    background-repeat: no-repeat;
    left: .5em;
    top: .3em
}

.ui-dialog {
    position: absolute;
    top: 0;
    left: 0;
    padding: .2em;
    outline: 0
}

.ui-dialog .ui-dialog-titlebar {
    padding: .4em 1em;
    position: relative
}

.ui-dialog .ui-dialog-title {
    float: left;
    margin: .1em 0;
    white-space: nowrap;
    width: 90%;
    overflow: hidden;
    text-overflow: ellipsis
}

.ui-dialog .ui-dialog-titlebar-close {
    position: absolute;
    right: .3em;
    top: 50%;
    width: 20px;
    margin: -10px 0 0 0;
    padding: 1px;
    height: 20px
}

.ui-dialog .ui-dialog-content {
    position: relative;
    border: 0;
    padding: .5em 1em;
    background: 0 0;
    overflow: auto
}

.ui-dialog .ui-dialog-buttonpane {
    text-align: left;
    border-width: 1px 0 0 0;
    background-image: none;
    margin-top: .5em;
    padding: .3em 1em .5em .4em
}

.ui-dialog .ui-dialog-buttonpane .ui-dialog-buttonset {
    float: right
}

.ui-dialog .ui-dialog-buttonpane button {
    margin: .5em .4em .5em 0;
    cursor: pointer
}

.ui-dialog .ui-resizable-n {
    height: 2px;
    top: 0
}

.ui-dialog .ui-resizable-e {
    width: 2px;
    right: 0
}

.ui-dialog .ui-resizable-s {
    height: 2px;
    bottom: 0
}

.ui-dialog .ui-resizable-w {
    width: 2px;
    left: 0
}

.ui-dialog .ui-resizable-ne,
.ui-dialog .ui-resizable-nw,
.ui-dialog .ui-resizable-se,
.ui-dialog .ui-resizable-sw {
    width: 7px;
    height: 7px
}

.ui-dialog .ui-resizable-se {
    right: 0;
    bottom: 0
}

.ui-dialog .ui-resizable-sw {
    left: 0;
    bottom: 0
}

.ui-dialog .ui-resizable-ne {
    right: 0;
    top: 0
}

.ui-dialog .ui-resizable-nw {
    left: 0;
    top: 0
}

.ui-draggable .ui-dialog-titlebar {
    cursor: move
}

.ui-progressbar {
    height: 2em;
    text-align: left;
    overflow: hidden
}

.ui-progressbar .ui-progressbar-value {
    margin: -1px;
    height: 100%
}

.ui-progressbar .ui-progressbar-overlay {
    background: url("data:image/gif;base64,R0lGODlhKAAoAIABAAAAAP///yH/C05FVFNDQVBFMi4wAwEAAAAh+QQJAQABACwAAAAAKAAoAAACkYwNqXrdC52DS06a7MFZI+4FHBCKoDeWKXqymPqGqxvJrXZbMx7Ttc+w9XgU2FB3lOyQRWET2IFGiU9m1frDVpxZZc6bfHwv4c1YXP6k1Vdy292Fb6UkuvFtXpvWSzA+HycXJHUXiGYIiMg2R6W459gnWGfHNdjIqDWVqemH2ekpObkpOlppWUqZiqr6edqqWQAAIfkECQEAAQAsAAAAACgAKAAAApSMgZnGfaqcg1E2uuzDmmHUBR8Qil95hiPKqWn3aqtLsS18y7G1SzNeowWBENtQd+T1JktP05nzPTdJZlR6vUxNWWjV+vUWhWNkWFwxl9VpZRedYcflIOLafaa28XdsH/ynlcc1uPVDZxQIR0K25+cICCmoqCe5mGhZOfeYSUh5yJcJyrkZWWpaR8doJ2o4NYq62lAAACH5BAkBAAEALAAAAAAoACgAAAKVDI4Yy22ZnINRNqosw0Bv7i1gyHUkFj7oSaWlu3ovC8GxNso5fluz3qLVhBVeT/Lz7ZTHyxL5dDalQWPVOsQWtRnuwXaFTj9jVVh8pma9JjZ4zYSj5ZOyma7uuolffh+IR5aW97cHuBUXKGKXlKjn+DiHWMcYJah4N0lYCMlJOXipGRr5qdgoSTrqWSq6WFl2ypoaUAAAIfkECQEAAQAsAAAAACgAKAAAApaEb6HLgd/iO7FNWtcFWe+ufODGjRfoiJ2akShbueb0wtI50zm02pbvwfWEMWBQ1zKGlLIhskiEPm9R6vRXxV4ZzWT2yHOGpWMyorblKlNp8HmHEb/lCXjcW7bmtXP8Xt229OVWR1fod2eWqNfHuMjXCPkIGNileOiImVmCOEmoSfn3yXlJWmoHGhqp6ilYuWYpmTqKUgAAIfkECQEAAQAsAAAAACgAKAAAApiEH6kb58biQ3FNWtMFWW3eNVcojuFGfqnZqSebuS06w5V80/X02pKe8zFwP6EFWOT1lDFk8rGERh1TTNOocQ61Hm4Xm2VexUHpzjymViHrFbiELsefVrn6XKfnt2Q9G/+Xdie499XHd2g4h7ioOGhXGJboGAnXSBnoBwKYyfioubZJ2Hn0RuRZaflZOil56Zp6iioKSXpUAAAh+QQJAQABACwAAAAAKAAoAAACkoQRqRvnxuI7kU1a1UU5bd5tnSeOZXhmn5lWK3qNTWvRdQxP8qvaC+/yaYQzXO7BMvaUEmJRd3TsiMAgswmNYrSgZdYrTX6tSHGZO73ezuAw2uxuQ+BbeZfMxsexY35+/Qe4J1inV0g4x3WHuMhIl2jXOKT2Q+VU5fgoSUI52VfZyfkJGkha6jmY+aaYdirq+lQAACH5BAkBAAEALAAAAAAoACgAAAKWBIKpYe0L3YNKToqswUlvznigd4wiR4KhZrKt9Upqip61i9E3vMvxRdHlbEFiEXfk9YARYxOZZD6VQ2pUunBmtRXo1Lf8hMVVcNl8JafV38aM2/Fu5V16Bn63r6xt97j09+MXSFi4BniGFae3hzbH9+hYBzkpuUh5aZmHuanZOZgIuvbGiNeomCnaxxap2upaCZsq+1kAACH5BAkBAAEALAAAAAAoACgAAAKXjI8By5zf4kOxTVrXNVlv1X0d8IGZGKLnNpYtm8Lr9cqVeuOSvfOW79D9aDHizNhDJidFZhNydEahOaDH6nomtJjp1tutKoNWkvA6JqfRVLHU/QUfau9l2x7G54d1fl995xcIGAdXqMfBNadoYrhH+Mg2KBlpVpbluCiXmMnZ2Sh4GBqJ+ckIOqqJ6LmKSllZmsoq6wpQAAAh+QQJAQABACwAAAAAKAAoAAAClYx/oLvoxuJDkU1a1YUZbJ59nSd2ZXhWqbRa2/gF8Gu2DY3iqs7yrq+xBYEkYvFSM8aSSObE+ZgRl1BHFZNr7pRCavZ5BW2142hY3AN/zWtsmf12p9XxxFl2lpLn1rseztfXZjdIWIf2s5dItwjYKBgo9yg5pHgzJXTEeGlZuenpyPmpGQoKOWkYmSpaSnqKileI2FAAACH5BAkBAAEALAAAAAAoACgAAAKVjB+gu+jG4kORTVrVhRlsnn2dJ3ZleFaptFrb+CXmO9OozeL5VfP99HvAWhpiUdcwkpBH3825AwYdU8xTqlLGhtCosArKMpvfa1mMRae9VvWZfeB2XfPkeLmm18lUcBj+p5dnN8jXZ3YIGEhYuOUn45aoCDkp16hl5IjYJvjWKcnoGQpqyPlpOhr3aElaqrq56Bq7VAAAOw==");
    height: 100%;
    opacity: .25
}

.ui-progressbar-indeterminate .ui-progressbar-value {
    background-image: none
}

.ui-selectmenu-menu {
    padding: 0;
    margin: 0;
    position: absolute;
    top: 0;
    left: 0;
    display: none
}

.ui-selectmenu-menu .ui-menu {
    overflow: auto;
    overflow-x: hidden;
    padding-bottom: 1px
}

.ui-selectmenu-menu .ui-menu .ui-selectmenu-optgroup {
    font-size: 1em;
    font-weight: 700;
    line-height: 1.5;
    padding: 2px .4em;
    margin: .5em 0 0 0;
    height: auto;
    border: 0
}

.ui-selectmenu-open {
    display: block
}

.ui-selectmenu-text {
    display: block;
    margin-right: 20px;
    overflow: hidden;
    text-overflow: ellipsis
}

.ui-selectmenu-button.ui-button {
    text-align: left;
    white-space: nowrap;
    width: 14em
}

.ui-selectmenu-icon.ui-icon {
    float: right;
    margin-top: 0
}

.ui-slider {
    position: relative;
    text-align: left
}

.ui-slider .ui-slider-handle {
    position: absolute;
    z-index: 2;
    width: 1.2em;
    height: 1.2em;
    cursor: default;
    -ms-touch-action: none;
    touch-action: none
}

.ui-slider .ui-slider-range {
    position: absolute;
    z-index: 1;
    font-size: .7em;
    display: block;
    border: 0;
    background-position: 0 0
}

.ui-slider.ui-state-disabled .ui-slider-handle,
.ui-slider.ui-state-disabled .ui-slider-range {
    filter: inherit
}

.ui-slider-horizontal {
    height: .8em
}

.ui-slider-horizontal .ui-slider-handle {
    top: -.3em;
    margin-left: -.6em
}

.ui-slider-horizontal .ui-slider-range {
    top: 0;
    height: 100%
}

.ui-slider-horizontal .ui-slider-range-min {
    left: 0
}

.ui-slider-horizontal .ui-slider-range-max {
    right: 0
}

.ui-slider-vertical {
    width: .8em;
    height: 100px
}

.ui-slider-vertical .ui-slider-handle {
    left: -.3em;
    margin-left: 0;
    margin-bottom: -.6em
}

.ui-slider-vertical .ui-slider-range {
    left: 0;
    width: 100%
}

.ui-slider-vertical .ui-slider-range-min {
    bottom: 0
}

.ui-slider-vertical .ui-slider-range-max {
    top: 0
}

.ui-spinner {
    position: relative;
    display: inline-block;
    overflow: hidden;
    padding: 0;
    vertical-align: middle
}

.ui-spinner-input {
    border: none;
    background: 0 0;
    color: inherit;
    padding: .222em 0;
    margin: .2em 0;
    vertical-align: middle;
    margin-left: .4em;
    margin-right: 2em
}

.ui-spinner-button {
    width: 1.6em;
    height: 50%;
    font-size: .5em;
    padding: 0;
    margin: 0;
    text-align: center;
    position: absolute;
    cursor: default;
    display: block;
    overflow: hidden;
    right: 0
}

.ui-spinner a.ui-spinner-button {
    border-top-style: none;
    border-bottom-style: none;
    border-right-style: none
}

.ui-spinner-up {
    top: 0
}

.ui-spinner-down {
    bottom: 0
}

.ui-tabs {
    position: relative;
    padding: .2em
}

.ui-tabs .ui-tabs-nav {
    margin: 0;
    padding: .2em .2em 0
}

.ui-tabs .ui-tabs-nav li {
    list-style: none;
    float: left;
    position: relative;
    top: 0;
    margin: 1px .2em 0 0;
    border-bottom-width: 0;
    padding: 0;
    white-space: nowrap
}

.ui-tabs .ui-tabs-nav .ui-tabs-anchor {
    float: left;
    padding: .5em 1em;
    text-decoration: none
}

.ui-tabs .ui-tabs-nav li.ui-tabs-active {
    margin-bottom: -1px;
    padding-bottom: 1px
}

.ui-tabs .ui-tabs-nav li.ui-state-disabled .ui-tabs-anchor,
.ui-tabs .ui-tabs-nav li.ui-tabs-active .ui-tabs-anchor,
.ui-tabs .ui-tabs-nav li.ui-tabs-loading .ui-tabs-anchor {
    cursor: text
}

.ui-tabs-collapsible .ui-tabs-nav li.ui-tabs-active .ui-tabs-anchor {
    cursor: pointer
}

.ui-tabs .ui-tabs-panel {
    display: block;
    border-width: 0;
    padding: 1em 1.4em;
    background: 0 0
}

.ui-tooltip {
    padding: 8px;
    position: absolute;
    z-index: 9999;
    max-width: 300px
}

body .ui-tooltip {
    border-width: 2px
}

.ui-widget {
    font-family: Arial, Helvetica, sans-serif;
    font-size: 1em
}

.ui-widget .ui-widget {
    font-size: 1em
}

.ui-widget button,
.ui-widget input,
.ui-widget select,
.ui-widget textarea {
    font-family: Arial, Helvetica, sans-serif;
    font-size: 1em
}

.ui-widget.ui-widget-content {
    border: 1px solid #c5c5c5
}

.ui-widget-content {
    border: 1px solid #ddd;
    background: #fff;
    color: #333
}

.ui-widget-content a {
    color: #333
}

.ui-widget-header {
    border: 1px solid #ddd;
    background: #e9e9e9;
    color: #333;
    font-weight: 700
}

.ui-widget-header a {
    color: #333
}

.ui-button,
.ui-state-default,
.ui-widget-content .ui-state-default,
.ui-widget-header .ui-state-default,
html .ui-button.ui-state-disabled:active,
html .ui-button.ui-state-disabled:hover {
    border: 1px solid #c5c5c5;
    background: #f6f6f6;
    font-weight: 400;
    color: #454545
}

.ui-button,
.ui-state-default a,
.ui-state-default a:link,
.ui-state-default a:visited,
a.ui-button,
a:link.ui-button,
a:visited.ui-button {
    color: #454545;
    text-decoration: none
}

.ui-button:focus,
.ui-button:hover,
.ui-state-focus,
.ui-state-hover,
.ui-widget-content .ui-state-focus,
.ui-widget-content .ui-state-hover,
.ui-widget-header .ui-state-focus,
.ui-widget-header .ui-state-hover {
    border: 1px solid #ccc;
    background: #ededed;
    font-weight: 400;
    color: #2b2b2b
}

.ui-state-focus a,
.ui-state-focus a:hover,
.ui-state-focus a:link,
.ui-state-focus a:visited,
.ui-state-hover a,
.ui-state-hover a:hover,
.ui-state-hover a:link,
.ui-state-hover a:visited,
a.ui-button:focus,
a.ui-button:hover {
    color: #2b2b2b;
    text-decoration: none
}

.ui-visual-focus {
    box-shadow: 0 0 3px 1px #5e9ed6
}

.ui-button.ui-state-active:hover,
.ui-button:active,
.ui-state-active,
.ui-widget-content .ui-state-active,
.ui-widget-header .ui-state-active,
a.ui-button:active {
    border: 1px solid #003eff;
    background: #007fff;
    font-weight: 400;
    color: #fff
}

.ui-icon-background,
.ui-state-active .ui-icon-background {
    border: #003eff;
    background-color: #fff
}

.ui-state-active a,
.ui-state-active a:link,
.ui-state-active a:visited {
    color: #fff;
    text-decoration: none
}

.ui-state-highlight,
.ui-widget-content .ui-state-highlight,
.ui-widget-header .ui-state-highlight {
    border: 1px solid #dad55e;
    background: #fffa90;
    color: #777620
}

.ui-state-checked {
    border: 1px solid #dad55e;
    background: #fffa90
}

.ui-state-highlight a,
.ui-widget-content .ui-state-highlight a,
.ui-widget-header .ui-state-highlight a {
    color: #777620
}

.ui-state-error,
.ui-widget-content .ui-state-error,
.ui-widget-header .ui-state-error {
    border: 1px solid #f1a899;
    background: #fddfdf;
    color: #5f3f3f
}

.ui-state-error a,
.ui-widget-content .ui-state-error a,
.ui-widget-header .ui-state-error a {
    color: #5f3f3f
}

.ui-state-error-text,
.ui-widget-content .ui-state-error-text,
.ui-widget-header .ui-state-error-text {
    color: #5f3f3f
}

.ui-priority-primary,
.ui-widget-content .ui-priority-primary,
.ui-widget-header .ui-priority-primary {
    font-weight: 700
}

.ui-priority-secondary,
.ui-widget-content .ui-priority-secondary,
.ui-widget-header .ui-priority-secondary {
    opacity: .7;
    filter: Alpha(Opacity=70);
    font-weight: 400
}

.ui-state-disabled,
.ui-widget-content .ui-state-disabled,
.ui-widget-header .ui-state-disabled {
    opacity: .35;
    filter: Alpha(Opacity=35);
    background-image: none
}

.ui-state-disabled .ui-icon {
    filter: Alpha(Opacity=35)
}

.ui-icon {
    width: 16px;
    height: 16px
}

.ui-icon,
.ui-widget-content .ui-icon {
    background-image: url("images/ui-icons_444444_256x240.png")
}

.ui-widget-header .ui-icon {
    background-image: url("images/ui-icons_444444_256x240.png")
}

.ui-button:focus .ui-icon,
.ui-button:hover .ui-icon,
.ui-state-focus .ui-icon,
.ui-state-hover .ui-icon {
    background-image: url("images/ui-icons_555555_256x240.png")
}

.ui-button:active .ui-icon,
.ui-state-active .ui-icon {
    background-image: url("images/ui-icons_ffffff_256x240.png")
}

.ui-button .ui-state-highlight.ui-icon,
.ui-state-highlight .ui-icon {
    background-image: url("images/ui-icons_777620_256x240.png")
}

.ui-state-error .ui-icon,
.ui-state-error-text .ui-icon {
    background-image: url("images/ui-icons_cc0000_256x240.png")
}

.ui-button .ui-icon {
    background-image: url("images/ui-icons_777777_256x240.png")
}

.ui-icon-blank {
    background-position: 16px 16px
}

.ui-icon-caret-1-n {
    background-position: 0 0
}

.ui-icon-caret-1-ne {
    background-position: -16px 0
}

.ui-icon-caret-1-e {
    background-position: -32px 0
}

.ui-icon-caret-1-se {
    background-position: -48px 0
}

.ui-icon-caret-1-s {
    background-position: -65px 0
}

.ui-icon-caret-1-sw {
    background-position: -80px 0
}

.ui-icon-caret-1-w {
    background-position: -96px 0
}

.ui-icon-caret-1-nw {
    background-position: -112px 0
}

.ui-icon-caret-2-n-s {
    background-position: -128px 0
}

.ui-icon-caret-2-e-w {
    background-position: -144px 0
}

.ui-icon-triangle-1-n {
    background-position: 0 -16px
}

.ui-icon-triangle-1-ne {
    background-position: -16px -16px
}

.ui-icon-triangle-1-e {
    background-position: -32px -16px
}

.ui-icon-triangle-1-se {
    background-position: -48px -16px
}

.ui-icon-triangle-1-s {
    background-position: -65px -16px
}

.ui-icon-triangle-1-sw {
    background-position: -80px -16px
}

.ui-icon-triangle-1-w {
    background-position: -96px -16px
}

.ui-icon-triangle-1-nw {
    background-position: -112px -16px
}

.ui-icon-triangle-2-n-s {
    background-position: -128px -16px
}

.ui-icon-triangle-2-e-w {
    background-position: -144px -16px
}

.ui-icon-arrow-1-n {
    background-position: 0 -32px
}

.ui-icon-arrow-1-ne {
    background-position: -16px -32px
}

.ui-icon-arrow-1-e {
    background-position: -32px -32px
}

.ui-icon-arrow-1-se {
    background-position: -48px -32px
}

.ui-icon-arrow-1-s {
    background-position: -65px -32px
}

.ui-icon-arrow-1-sw {
    background-position: -80px -32px
}

.ui-icon-arrow-1-w {
    background-position: -96px -32px
}

.ui-icon-arrow-1-nw {
    background-position: -112px -32px
}

.ui-icon-arrow-2-n-s {
    background-position: -128px -32px
}

.ui-icon-arrow-2-ne-sw {
    background-position: -144px -32px
}

.ui-icon-arrow-2-e-w {
    background-position: -160px -32px
}

.ui-icon-arrow-2-se-nw {
    background-position: -176px -32px
}

.ui-icon-arrowstop-1-n {
    background-position: -192px -32px
}

.ui-icon-arrowstop-1-e {
    background-position: -208px -32px
}

.ui-icon-arrowstop-1-s {
    background-position: -224px -32px
}

.ui-icon-arrowstop-1-w {
    background-position: -240px -32px
}

.ui-icon-arrowthick-1-n {
    background-position: 1px -48px
}

.ui-icon-arrowthick-1-ne {
    background-position: -16px -48px
}

.ui-icon-arrowthick-1-e {
    background-position: -32px -48px
}

.ui-icon-arrowthick-1-se {
    background-position: -48px -48px
}

.ui-icon-arrowthick-1-s {
    background-position: -64px -48px
}

.ui-icon-arrowthick-1-sw {
    background-position: -80px -48px
}

.ui-icon-arrowthick-1-w {
    background-position: -96px -48px
}

.ui-icon-arrowthick-1-nw {
    background-position: -112px -48px
}

.ui-icon-arrowthick-2-n-s {
    background-position: -128px -48px
}

.ui-icon-arrowthick-2-ne-sw {
    background-position: -144px -48px
}

.ui-icon-arrowthick-2-e-w {
    background-position: -160px -48px
}

.ui-icon-arrowthick-2-se-nw {
    background-position: -176px -48px
}

.ui-icon-arrowthickstop-1-n {
    background-position: -192px -48px
}

.ui-icon-arrowthickstop-1-e {
    background-position: -208px -48px
}

.ui-icon-arrowthickstop-1-s {
    background-position: -224px -48px
}

.ui-icon-arrowthickstop-1-w {
    background-position: -240px -48px
}

.ui-icon-arrowreturnthick-1-w {
    background-position: 0 -64px
}

.ui-icon-arrowreturnthick-1-n {
    background-position: -16px -64px
}

.ui-icon-arrowreturnthick-1-e {
    background-position: -32px -64px
}

.ui-icon-arrowreturnthick-1-s {
    background-position: -48px -64px
}

.ui-icon-arrowreturn-1-w {
    background-position: -64px -64px
}

.ui-icon-arrowreturn-1-n {
    background-position: -80px -64px
}

.ui-icon-arrowreturn-1-e {
    background-position: -96px -64px
}

.ui-icon-arrowreturn-1-s {
    background-position: -112px -64px
}

.ui-icon-arrowrefresh-1-w {
    background-position: -128px -64px
}

.ui-icon-arrowrefresh-1-n {
    background-position: -144px -64px
}

.ui-icon-arrowrefresh-1-e {
    background-position: -160px -64px
}

.ui-icon-arrowrefresh-1-s {
    background-position: -176px -64px
}

.ui-icon-arrow-4 {
    background-position: 0 -80px
}

.ui-icon-arrow-4-diag {
    background-position: -16px -80px
}

.ui-icon-extlink {
    background-position: -32px -80px
}

.ui-icon-newwin {
    background-position: -48px -80px
}

.ui-icon-refresh {
    background-position: -64px -80px
}

.ui-icon-shuffle {
    background-position: -80px -80px
}

.ui-icon-transfer-e-w {
    background-position: -96px -80px
}

.ui-icon-transferthick-e-w {
    background-position: -112px -80px
}

.ui-icon-folder-collapsed {
    background-position: 0 -96px
}

.ui-icon-folder-open {
    background-position: -16px -96px
}

.ui-icon-document {
    background-position: -32px -96px
}

.ui-icon-document-b {
    background-position: -48px -96px
}

.ui-icon-note {
    background-position: -64px -96px
}

.ui-icon-mail-closed {
    background-position: -80px -96px
}

.ui-icon-mail-open {
    background-position: -96px -96px
}

.ui-icon-suitcase {
    background-position: -112px -96px
}

.ui-icon-comment {
    background-position: -128px -96px
}

.ui-icon-person {
    background-position: -144px -96px
}

.ui-icon-print {
    background-position: -160px -96px
}

.ui-icon-trash {
    background-position: -176px -96px
}

.ui-icon-locked {
    background-position: -192px -96px
}

.ui-icon-unlocked {
    background-position: -208px -96px
}

.ui-icon-bookmark {
    background-position: -224px -96px
}

.ui-icon-tag {
    background-position: -240px -96px
}

.ui-icon-home {
    background-position: 0 -112px
}

.ui-icon-flag {
    background-position: -16px -112px
}

.ui-icon-calendar {
    background-position: -32px -112px
}

.ui-icon-cart {
    background-position: -48px -112px
}

.ui-icon-pencil {
    background-position: -64px -112px
}

.ui-icon-clock {
    background-position: -80px -112px
}

.ui-icon-disk {
    background-position: -96px -112px
}

.ui-icon-calculator {
    background-position: -112px -112px
}

.ui-icon-zoomin {
    background-position: -128px -112px
}

.ui-icon-zoomout {
    background-position: -144px -112px
}

.ui-icon-search {
    background-position: -160px -112px
}

.ui-icon-wrench {
    background-position: -176px -112px
}

.ui-icon-gear {
    background-position: -192px -112px
}

.ui-icon-heart {
    background-position: -208px -112px
}

.ui-icon-star {
    background-position: -224px -112px
}

.ui-icon-link {
    background-position: -240px -112px
}

.ui-icon-cancel {
    background-position: 0 -128px
}

.ui-icon-plus {
    background-position: -16px -128px
}

.ui-icon-plusthick {
    background-position: -32px -128px
}

.ui-icon-minus {
    background-position: -48px -128px
}

.ui-icon-minusthick {
    background-position: -64px -128px
}

.ui-icon-close {
    background-position: -80px -128px
}

.ui-icon-closethick {
    background-position: -96px -128px
}

.ui-icon-key {
    background-position: -112px -128px
}

.ui-icon-lightbulb {
    background-position: -128px -128px
}

.ui-icon-scissors {
    background-position: -144px -128px
}

.ui-icon-clipboard {
    background-position: -160px -128px
}

.ui-icon-copy {
    background-position: -176px -128px
}

.ui-icon-contact {
    background-position: -192px -128px
}

.ui-icon-image {
    background-position: -208px -128px
}

.ui-icon-video {
    background-position: -224px -128px
}

.ui-icon-script {
    background-position: -240px -128px
}

.ui-icon-alert {
    background-position: 0 -144px
}

.ui-icon-info {
    background-position: -16px -144px
}

.ui-icon-notice {
    background-position: -32px -144px
}

.ui-icon-help {
    background-position: -48px -144px
}

.ui-icon-check {
    background-position: -64px -144px
}

.ui-icon-bullet {
    background-position: -80px -144px
}

.ui-icon-radio-on {
    background-position: -96px -144px
}

.ui-icon-radio-off {
    background-position: -112px -144px
}

.ui-icon-pin-w {
    background-position: -128px -144px
}

.ui-icon-pin-s {
    background-position: -144px -144px
}

.ui-icon-play {
    background-position: 0 -160px
}

.ui-icon-pause {
    background-position: -16px -160px
}

.ui-icon-seek-next {
    background-position: -32px -160px
}

.ui-icon-seek-prev {
    background-position: -48px -160px
}

.ui-icon-seek-end {
    background-position: -64px -160px
}

.ui-icon-seek-start {
    background-position: -80px -160px
}

.ui-icon-seek-first {
    background-position: -80px -160px
}

.ui-icon-stop {
    background-position: -96px -160px
}

.ui-icon-eject {
    background-position: -112px -160px
}

.ui-icon-volume-off {
    background-position: -128px -160px
}

.ui-icon-volume-on {
    background-position: -144px -160px
}

.ui-icon-power {
    background-position: 0 -176px
}

.ui-icon-signal-diag {
    background-position: -16px -176px
}

.ui-icon-signal {
    background-position: -32px -176px
}

.ui-icon-battery-0 {
    background-position: -48px -176px
}

.ui-icon-battery-1 {
    background-position: -64px -176px
}

.ui-icon-battery-2 {
    background-position: -80px -176px
}

.ui-icon-battery-3 {
    background-position: -96px -176px
}

.ui-icon-circle-plus {
    background-position: 0 -192px
}

.ui-icon-circle-minus {
    background-position: -16px -192px
}

.ui-icon-circle-close {
    background-position: -32px -192px
}

.ui-icon-circle-triangle-e {
    background-position: -48px -192px
}

.ui-icon-circle-triangle-s {
    background-position: -64px -192px
}

.ui-icon-circle-triangle-w {
    background-position: -80px -192px
}

.ui-icon-circle-triangle-n {
    background-position: -96px -192px
}

.ui-icon-circle-arrow-e {
    background-position: -112px -192px
}

.ui-icon-circle-arrow-s {
    background-position: -128px -192px
}

.ui-icon-circle-arrow-w {
    background-position: -144px -192px
}

.ui-icon-circle-arrow-n {
    background-position: -160px -192px
}

.ui-icon-circle-zoomin {
    background-position: -176px -192px
}

.ui-icon-circle-zoomout {
    background-position: -192px -192px
}

.ui-icon-circle-check {
    background-position: -208px -192px
}

.ui-icon-circlesmall-plus {
    background-position: 0 -208px
}

.ui-icon-circlesmall-minus {
    background-position: -16px -208px
}

.ui-icon-circlesmall-close {
    background-position: -32px -208px
}

.ui-icon-squaresmall-plus {
    background-position: -48px -208px
}

.ui-icon-squaresmall-minus {
    background-position: -64px -208px
}

.ui-icon-squaresmall-close {
    background-position: -80px -208px
}

.ui-icon-grip-dotted-vertical {
    background-position: 0 -224px
}

.ui-icon-grip-dotted-horizontal {
    background-position: -16px -224px
}

.ui-icon-grip-solid-vertical {
    background-position: -32px -224px
}

.ui-icon-grip-solid-horizontal {
    background-position: -48px -224px
}

.ui-icon-gripsmall-diagonal-se {
    background-position: -64px -224px
}

.ui-icon-grip-diagonal-se {
    background-position: -80px -224px
}

.ui-corner-all,
.ui-corner-left,
.ui-corner-tl,
.ui-corner-top {
    border-top-left-radius: 3px
}

.ui-corner-all,
.ui-corner-right,
.ui-corner-top,
.ui-corner-tr {
    border-top-right-radius: 3px
}

.ui-corner-all,
.ui-corner-bl,
.ui-corner-bottom,
.ui-corner-left {
    border-bottom-left-radius: 3px
}

.ui-corner-all,
.ui-corner-bottom,
.ui-corner-br,
.ui-corner-right {
    border-bottom-right-radius: 3px
}

.ui-widget-overlay {
    background: #aaa;
    opacity: .3;
    filter: Alpha(Opacity=30)
}

.ui-widget-shadow {
    -webkit-box-shadow: 0 0 5px #666;
    box-shadow: 0 0 5px #666
}

/*!
 * Bootstrap v3.3.7 (http://getbootstrap.com)
 * Copyright 2011-2016 Twitter, Inc.
 * Licensed under MIT (https://github.com/twbs/bootstrap/blob/master/LICENSE)
 */

/*! normalize.css v3.0.3 | MIT License | github.com/necolas/normalize.css */

html {
    font-family: sans-serif;
    -webkit-text-size-adjust: 100%;
    -ms-text-size-adjust: 100%
}

body {
    margin: 0
}

article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
main,
menu,
nav,
section,
summary {
    display: block
}

audio,
canvas,
progress,
video {
    display: inline-block;
    vertical-align: baseline
}

audio:not([controls]) {
    display: none;
    height: 0
}

[hidden],
template {
    display: none
}

a {
    background-color: transparent
}

a:active,
a:hover {
    outline: 0
}

abbr[title] {
    border-bottom: 1px dotted
}

b,
strong {
    font-weight: 700
}

dfn {
    font-style: italic
}

h1 {
    margin: .67em 0;
    font-size: 2em
}

mark {
    color: #000;
    background: #ff0
}

small {
    font-size: 80%
}

sub,
sup {
    position: relative;
    font-size: 75%;
    line-height: 0;
    vertical-align: baseline
}

sup {
    top: -.5em
}

sub {
    bottom: -.25em
}

img {
    border: 0
}

svg:not(:root) {
    overflow: hidden
}

figure {
    margin: 1em 40px
}

hr {
    height: 0;
    -webkit-box-sizing: content-box;
    -moz-box-sizing: content-box;
    box-sizing: content-box
}

pre {
    overflow: auto
}

code,
kbd,
pre,
samp {
    font-family: monospace, monospace;
    font-size: 1em
}

button,
input,
optgroup,
select,
textarea {
    margin: 0;
    font: inherit;
    color: inherit
}

button {
    overflow: visible
}

button,
select {
    text-transform: none
}

button,
html input[type=button],
input[type=reset],
input[type=submit] {
    -webkit-appearance: button;
    cursor: pointer
}

button[disabled],
html input[disabled] {
    cursor: default
}

button::-moz-focus-inner,
input::-moz-focus-inner {
    padding: 0;
    border: 0
}

input {
    line-height: normal
}

input[type=checkbox],
input[type=radio] {
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box;
    padding: 0
}

input[type=number]::-webkit-inner-spin-button,
input[type=number]::-webkit-outer-spin-button {
    height: auto
}

input[type=search] {
    -webkit-box-sizing: content-box;
    -moz-box-sizing: content-box;
    box-sizing: content-box;
    -webkit-appearance: textfield
}

input[type=search]::-webkit-search-cancel-button,
input[type=search]::-webkit-search-decoration {
    -webkit-appearance: none
}

fieldset {
    padding: .35em .625em .75em;
    margin: 0 2px;
    border: 1px solid silver
}

legend {
    padding: 0;
    border: 0
}

textarea {
    overflow: auto
}

optgroup {
    font-weight: 700
}

table {
    border-spacing: 0;
    border-collapse: collapse
}

td,
th {
    padding: 0
}

/*! Source: https://github.com/h5bp/html5-boilerplate/blob/master/src/css/main.css */

@media print {
    *,
    :after,
    :before {
        color: #000 !important;
        text-shadow: none !important;
        background: 0 0 !important;
        -webkit-box-shadow: none !important;
        box-shadow: none !important
    }
    a,
    a:visited {
        text-decoration: underline
    }
    a[href]:after {
        content: " (" attr(href) ")"
    }
    abbr[title]:after {
        content: " (" attr(title) ")"
    }
    a[href^="#"]:after,
    a[href^="javascript:"]:after {
        content: ""
    }
    blockquote,
    pre {
        border: 1px solid #999;
        page-break-inside: avoid
    }
    thead {
        display: table-header-group
    }
    img,
    tr {
        page-break-inside: avoid
    }
    img {
        max-width: 100% !important
    }
    h2,
    h3,
    p {
        orphans: 3;
        widows: 3
    }
    h2,
    h3 {
        page-break-after: avoid
    }
    .navbar {
        display: none
    }
    .btn>.caret,
    .dropup>.btn>.caret {
        border-top-color: #000 !important
    }
    .label {
        border: 1px solid #000
    }
    .table {
        border-collapse: collapse !important
    }
    .table td,
    .table th {
        background-color: #fff !important
    }
    .table-bordered td,
    .table-bordered th {
        border: 1px solid #ddd !important
    }
}

@font-face {
    font-family: 'Glyphicons Halflings';
    src: url(../fonts/glyphicons-halflings-regular.eot);
    src: url(../fonts/glyphicons-halflings-regular.eot?#iefix) format('embedded-opentype'), url(../fonts/glyphicons-halflings-regular.woff2) format('woff2'), url(../fonts/glyphicons-halflings-regular.woff) format('woff'), url(../fonts/glyphicons-halflings-regular.ttf) format('truetype'), url(../fonts/glyphicons-halflings-regular.svg#glyphicons_halflingsregular) format('svg')
}

.glyphicon {
    position: relative;
    top: 1px;
    display: inline-block;
    font-family: 'Glyphicons Halflings';
    font-style: normal;
    font-weight: 400;
    line-height: 1;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale
}

.glyphicon-asterisk:before {
    content: "\002a"
}

.glyphicon-plus:before {
    content: "\002b"
}

.glyphicon-eur:before,
.glyphicon-euro:before {
    content: "\20ac"
}

.glyphicon-minus:before {
    content: "\2212"
}

.glyphicon-cloud:before {
    content: "\2601"
}

.glyphicon-envelope:before {
    content: "\2709"
}

.glyphicon-pencil:before {
    content: "\270f"
}

.glyphicon-glass:before {
    content: "\e001"
}

.glyphicon-music:before {
    content: "\e002"
}

.glyphicon-search:before {
    content: "\e003"
}

.glyphicon-heart:before {
    content: "\e005"
}

.glyphicon-star:before {
    content: "\e006"
}

.glyphicon-star-empty:before {
    content: "\e007"
}

.glyphicon-user:before {
    content: "\e008"
}

.glyphicon-film:before {
    content: "\e009"
}

.glyphicon-th-large:before {
    content: "\e010"
}

.glyphicon-th:before {
    content: "\e011"
}

.glyphicon-th-list:before {
    content: "\e012"
}

.glyphicon-ok:before {
    content: "\e013"
}

.glyphicon-remove:before {
    content: "\e014"
}

.glyphicon-zoom-in:before {
    content: "\e015"
}

.glyphicon-zoom-out:before {
    content: "\e016"
}

.glyphicon-off:before {
    content: "\e017"
}

.glyphicon-signal:before {
    content: "\e018"
}

.glyphicon-cog:before {
    content: "\e019"
}

.glyphicon-trash:before {
    content: "\e020"
}

.glyphicon-home:before {
    content: "\e021"
}

.glyphicon-file:before {
    content: "\e022"
}

.glyphicon-time:before {
    content: "\e023"
}

.glyphicon-road:before {
    content: "\e024"
}

.glyphicon-download-alt:before {
    content: "\e025"
}

.glyphicon-download:before {
    content: "\e026"
}

.glyphicon-upload:before {
    content: "\e027"
}

.glyphicon-inbox:before {
    content: "\e028"
}

.glyphicon-play-circle:before {
    content: "\e029"
}

.glyphicon-repeat:before {
    content: "\e030"
}

.glyphicon-refresh:before {
    content: "\e031"
}

.glyphicon-list-alt:before {
    content: "\e032"
}

.glyphicon-lock:before {
    content: "\e033"
}

.glyphicon-flag:before {
    content: "\e034"
}

.glyphicon-headphones:before {
    content: "\e035"
}

.glyphicon-volume-off:before {
    content: "\e036"
}

.glyphicon-volume-down:before {
    content: "\e037"
}

.glyphicon-volume-up:before {
    content: "\e038"
}

.glyphicon-qrcode:before {
    content: "\e039"
}

.glyphicon-barcode:before {
    content: "\e040"
}

.glyphicon-tag:before {
    content: "\e041"
}

.glyphicon-tags:before {
    content: "\e042"
}

.glyphicon-book:before {
    content: "\e043"
}

.glyphicon-bookmark:before {
    content: "\e044"
}

.glyphicon-print:before {
    content: "\e045"
}

.glyphicon-camera:before {
    content: "\e046"
}

.glyphicon-font:before {
    content: "\e047"
}

.glyphicon-bold:before {
    content: "\e048"
}

.glyphicon-italic:before {
    content: "\e049"
}

.glyphicon-text-height:before {
    content: "\e050"
}

.glyphicon-text-width:before {
    content: "\e051"
}

.glyphicon-align-left:before {
    content: "\e052"
}

.glyphicon-align-center:before {
    content: "\e053"
}

.glyphicon-align-right:before {
    content: "\e054"
}

.glyphicon-align-justify:before {
    content: "\e055"
}

.glyphicon-list:before {
    content: "\e056"
}

.glyphicon-indent-left:before {
    content: "\e057"
}

.glyphicon-indent-right:before {
    content: "\e058"
}

.glyphicon-facetime-video:before {
    content: "\e059"
}

.glyphicon-picture:before {
    content: "\e060"
}

.glyphicon-map-marker:before {
    content: "\e062"
}

.glyphicon-adjust:before {
    content: "\e063"
}

.glyphicon-tint:before {
    content: "\e064"
}

.glyphicon-edit:before {
    content: "\e065"
}

.glyphicon-share:before {
    content: "\e066"
}

.glyphicon-check:before {
    content: "\e067"
}

.glyphicon-move:before {
    content: "\e068"
}

.glyphicon-step-backward:before {
    content: "\e069"
}

.glyphicon-fast-backward:before {
    content: "\e070"
}

.glyphicon-backward:before {
    content: "\e071"
}

.glyphicon-play:before {
    content: "\e072"
}

.glyphicon-pause:before {
    content: "\e073"
}

.glyphicon-stop:before {
    content: "\e074"
}

.glyphicon-forward:before {
    content: "\e075"
}

.glyphicon-fast-forward:before {
    content: "\e076"
}

.glyphicon-step-forward:before {
    content: "\e077"
}

.glyphicon-eject:before {
    content: "\e078"
}

.glyphicon-chevron-left:before {
    content: "\e079"
}

.glyphicon-chevron-right:before {
    content: "\e080"
}

.glyphicon-plus-sign:before {
    content: "\e081"
}

.glyphicon-minus-sign:before {
    content: "\e082"
}

.glyphicon-remove-sign:before {
    content: "\e083"
}

.glyphicon-ok-sign:before {
    content: "\e084"
}

.glyphicon-question-sign:before {
    content: "\e085"
}

.glyphicon-info-sign:before {
    content: "\e086"
}

.glyphicon-screenshot:before {
    content: "\e087"
}

.glyphicon-remove-circle:before {
    content: "\e088"
}

.glyphicon-ok-circle:before {
    content: "\e089"
}

.glyphicon-ban-circle:before {
    content: "\e090"
}

.glyphicon-arrow-left:before {
    content: "\e091"
}

.glyphicon-arrow-right:before {
    content: "\e092"
}

.glyphicon-arrow-up:before {
    content: "\e093"
}

.glyphicon-arrow-down:before {
    content: "\e094"
}

.glyphicon-share-alt:before {
    content: "\e095"
}

.glyphicon-resize-full:before {
    content: "\e096"
}

.glyphicon-resize-small:before {
    content: "\e097"
}

.glyphicon-exclamation-sign:before {
    content: "\e101"
}

.glyphicon-gift:before {
    content: "\e102"
}

.glyphicon-leaf:before {
    content: "\e103"
}

.glyphicon-fire:before {
    content: "\e104"
}

.glyphicon-eye-open:before {
    content: "\e105"
}

.glyphicon-eye-close:before {
    content: "\e106"
}

.glyphicon-warning-sign:before {
    content: "\e107"
}

.glyphicon-plane:before {
    content: "\e108"
}

.glyphicon-calendar:before {
    content: "\e109"
}

.glyphicon-random:before {
    content: "\e110"
}

.glyphicon-comment:before {
    content: "\e111"
}

.glyphicon-magnet:before {
    content: "\e112"
}

.glyphicon-chevron-up:before {
    content: "\e113"
}

.glyphicon-chevron-down:before {
    content: "\e114"
}

.glyphicon-retweet:before {
    content: "\e115"
}

.glyphicon-shopping-cart:before {
    content: "\e116"
}

.glyphicon-folder-close:before {
    content: "\e117"
}

.glyphicon-folder-open:before {
    content: "\e118"
}

.glyphicon-resize-vertical:before {
    content: "\e119"
}

.glyphicon-resize-horizontal:before {
    content: "\e120"
}

.glyphicon-hdd:before {
    content: "\e121"
}

.glyphicon-bullhorn:before {
    content: "\e122"
}

.glyphicon-bell:before {
    content: "\e123"
}

.glyphicon-certificate:before {
    content: "\e124"
}

.glyphicon-thumbs-up:before {
    content: "\e125"
}

.glyphicon-thumbs-down:before {
    content: "\e126"
}

.glyphicon-hand-right:before {
    content: "\e127"
}

.glyphicon-hand-left:before {
    content: "\e128"
}

.glyphicon-hand-up:before {
    content: "\e129"
}

.glyphicon-hand-down:before {
    content: "\e130"
}

.glyphicon-circle-arrow-right:before {
    content: "\e131"
}

.glyphicon-circle-arrow-left:before {
    content: "\e132"
}

.glyphicon-circle-arrow-up:before {
    content: "\e133"
}

.glyphicon-circle-arrow-down:before {
    content: "\e134"
}

.glyphicon-globe:before {
    content: "\e135"
}

.glyphicon-wrench:before {
    content: "\e136"
}

.glyphicon-tasks:before {
    content: "\e137"
}

.glyphicon-filter:before {
    content: "\e138"
}

.glyphicon-briefcase:before {
    content: "\e139"
}

.glyphicon-fullscreen:before {
    content: "\e140"
}

.glyphicon-dashboard:before {
    content: "\e141"
}

.glyphicon-paperclip:before {
    content: "\e142"
}

.glyphicon-heart-empty:before {
    content: "\e143"
}

.glyphicon-link:before {
    content: "\e144"
}

.glyphicon-phone:before {
    content: "\e145"
}

.glyphicon-pushpin:before {
    content: "\e146"
}

.glyphicon-usd:before {
    content: "\e148"
}

.glyphicon-gbp:before {
    content: "\e149"
}

.glyphicon-sort:before {
    content: "\e150"
}

.glyphicon-sort-by-alphabet:before {
    content: "\e151"
}

.glyphicon-sort-by-alphabet-alt:before {
    content: "\e152"
}

.glyphicon-sort-by-order:before {
    content: "\e153"
}

.glyphicon-sort-by-order-alt:before {
    content: "\e154"
}

.glyphicon-sort-by-attributes:before {
    content: "\e155"
}

.glyphicon-sort-by-attributes-alt:before {
    content: "\e156"
}

.glyphicon-unchecked:before {
    content: "\e157"
}

.glyphicon-expand:before {
    content: "\e158"
}

.glyphicon-collapse-down:before {
    content: "\e159"
}

.glyphicon-collapse-up:before {
    content: "\e160"
}

.glyphicon-log-in:before {
    content: "\e161"
}

.glyphicon-flash:before {
    content: "\e162"
}

.glyphicon-log-out:before {
    content: "\e163"
}

.glyphicon-new-window:before {
    content: "\e164"
}

.glyphicon-record:before {
    content: "\e165"
}

.glyphicon-save:before {
    content: "\e166"
}

.glyphicon-open:before {
    content: "\e167"
}

.glyphicon-saved:before {
    content: "\e168"
}

.glyphicon-import:before {
    content: "\e169"
}

.glyphicon-export:before {
    content: "\e170"
}

.glyphicon-send:before {
    content: "\e171"
}

.glyphicon-floppy-disk:before {
    content: "\e172"
}

.glyphicon-floppy-saved:before {
    content: "\e173"
}

.glyphicon-floppy-remove:before {
    content: "\e174"
}

.glyphicon-floppy-save:before {
    content: "\e175"
}

.glyphicon-floppy-open:before {
    content: "\e176"
}

.glyphicon-credit-card:before {
    content: "\e177"
}

.glyphicon-transfer:before {
    content: "\e178"
}

.glyphicon-cutlery:before {
    content: "\e179"
}

.glyphicon-header:before {
    content: "\e180"
}

.glyphicon-compressed:before {
    content: "\e181"
}

.glyphicon-earphone:before {
    content: "\e182"
}

.glyphicon-phone-alt:before {
    content: "\e183"
}

.glyphicon-tower:before {
    content: "\e184"
}

.glyphicon-stats:before {
    content: "\e185"
}

.glyphicon-sd-video:before {
    content: "\e186"
}

.glyphicon-hd-video:before {
    content: "\e187"
}

.glyphicon-subtitles:before {
    content: "\e188"
}

.glyphicon-sound-stereo:before {
    content: "\e189"
}

.glyphicon-sound-dolby:before {
    content: "\e190"
}

.glyphicon-sound-5-1:before {
    content: "\e191"
}

.glyphicon-sound-6-1:before {
    content: "\e192"
}

.glyphicon-sound-7-1:before {
    content: "\e193"
}

.glyphicon-copyright-mark:before {
    content: "\e194"
}

.glyphicon-registration-mark:before {
    content: "\e195"
}

.glyphicon-cloud-download:before {
    content: "\e197"
}

.glyphicon-cloud-upload:before {
    content: "\e198"
}

.glyphicon-tree-conifer:before {
    content: "\e199"
}

.glyphicon-tree-deciduous:before {
    content: "\e200"
}

.glyphicon-cd:before {
    content: "\e201"
}

.glyphicon-save-file:before {
    content: "\e202"
}

.glyphicon-open-file:before {
    content: "\e203"
}

.glyphicon-level-up:before {
    content: "\e204"
}

.glyphicon-copy:before {
    content: "\e205"
}

.glyphicon-paste:before {
    content: "\e206"
}

.glyphicon-alert:before {
    content: "\e209"
}

.glyphicon-equalizer:before {
    content: "\e210"
}

.glyphicon-king:before {
    content: "\e211"
}

.glyphicon-queen:before {
    content: "\e212"
}

.glyphicon-pawn:before {
    content: "\e213"
}

.glyphicon-bishop:before {
    content: "\e214"
}

.glyphicon-knight:before {
    content: "\e215"
}

.glyphicon-baby-formula:before {
    content: "\e216"
}

.glyphicon-tent:before {
    content: "\26fa"
}

.glyphicon-blackboard:before {
    content: "\e218"
}

.glyphicon-bed:before {
    content: "\e219"
}

.glyphicon-apple:before {
    content: "\f8ff"
}

.glyphicon-erase:before {
    content: "\e221"
}

.glyphicon-hourglass:before {
    content: "\231b"
}

.glyphicon-lamp:before {
    content: "\e223"
}

.glyphicon-duplicate:before {
    content: "\e224"
}

.glyphicon-piggy-bank:before {
    content: "\e225"
}

.glyphicon-scissors:before {
    content: "\e226"
}

.glyphicon-bitcoin:before {
    content: "\e227"
}

.glyphicon-btc:before {
    content: "\e227"
}

.glyphicon-xbt:before {
    content: "\e227"
}

.glyphicon-yen:before {
    content: "\00a5"
}

.glyphicon-jpy:before {
    content: "\00a5"
}

.glyphicon-ruble:before {
    content: "\20bd"
}

.glyphicon-rub:before {
    content: "\20bd"
}

.glyphicon-scale:before {
    content: "\e230"
}

.glyphicon-ice-lolly:before {
    content: "\e231"
}

.glyphicon-ice-lolly-tasted:before {
    content: "\e232"
}

.glyphicon-education:before {
    content: "\e233"
}

.glyphicon-option-horizontal:before {
    content: "\e234"
}

.glyphicon-option-vertical:before {
    content: "\e235"
}

.glyphicon-menu-hamburger:before {
    content: "\e236"
}

.glyphicon-modal-window:before {
    content: "\e237"
}

.glyphicon-oil:before {
    content: "\e238"
}

.glyphicon-grain:before {
    content: "\e239"
}

.glyphicon-sunglasses:before {
    content: "\e240"
}

.glyphicon-text-size:before {
    content: "\e241"
}

.glyphicon-text-color:before {
    content: "\e242"
}

.glyphicon-text-background:before {
    content: "\e243"
}

.glyphicon-object-align-top:before {
    content: "\e244"
}

.glyphicon-object-align-bottom:before {
    content: "\e245"
}

.glyphicon-object-align-horizontal:before {
    content: "\e246"
}

.glyphicon-object-align-left:before {
    content: "\e247"
}

.glyphicon-object-align-vertical:before {
    content: "\e248"
}

.glyphicon-object-align-right:before {
    content: "\e249"
}

.glyphicon-triangle-right:before {
    content: "\e250"
}

.glyphicon-triangle-left:before {
    content: "\e251"
}

.glyphicon-triangle-bottom:before {
    content: "\e252"
}

.glyphicon-triangle-top:before {
    content: "\e253"
}

.glyphicon-console:before {
    content: "\e254"
}

.glyphicon-superscript:before {
    content: "\e255"
}

.glyphicon-subscript:before {
    content: "\e256"
}

.glyphicon-menu-left:before {
    content: "\e257"
}

.glyphicon-menu-right:before {
    content: "\e258"
}

.glyphicon-menu-down:before {
    content: "\e259"
}

.glyphicon-menu-up:before {
    content: "\e260"
}

* {
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box
}

:after,
:before {
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box
}

html {
    font-size: 10px;
    -webkit-tap-highlight-color: transparent
}

body {
    font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
    font-size: 14px;
    line-height: 1.42857143;
    color: #333;
    background-color: #fff
}

button,
input,
select,
textarea {
    font-family: inherit;
    font-size: inherit;
    line-height: inherit
}

a {
    color: #337ab7;
    text-decoration: none
}

a:focus,
a:hover {
    color: #23527c;
    text-decoration: underline
}

a:focus {
    outline: 5px auto -webkit-focus-ring-color;
    outline-offset: -2px
}

figure {
    margin: 0
}

img {
    vertical-align: middle
}

.carousel-inner>.item>a>img,
.carousel-inner>.item>img,
.img-responsive,
.thumbnail a>img,
.thumbnail>img {
    display: block;
    max-width: 100%;
    height: auto
}

.img-rounded {
    border-radius: 6px
}

.img-thumbnail {
    display: inline-block;
    max-width: 100%;
    height: auto;
    padding: 4px;
    line-height: 1.42857143;
    background-color: #fff;
    border: 1px solid #ddd;
    border-radius: 4px;
    -webkit-transition: all .2s ease-in-out;
    -o-transition: all .2s ease-in-out;
    transition: all .2s ease-in-out
}

.img-circle {
    border-radius: 50%
}

hr {
    margin-top: 20px;
    margin-bottom: 20px;
    border: 0;
    border-top: 1px solid #eee
}

.sr-only {
    position: absolute;
    width: 1px;
    height: 1px;
    padding: 0;
    margin: -1px;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    border: 0
}

.sr-only-focusable:active,
.sr-only-focusable:focus {
    position: static;
    width: auto;
    height: auto;
    margin: 0;
    overflow: visible;
    clip: auto
}

[role=button] {
    cursor: pointer
}

.h1,
.h2,
.h3,
.h4,
.h5,
.h6,
h1,
h2,
h3,
h4,
h5,
h6 {
    font-family: inherit;
    font-weight: 500;
    line-height: 1.1;
    color: inherit
}

.h1 .small,
.h1 small,
.h2 .small,
.h2 small,
.h3 .small,
.h3 small,
.h4 .small,
.h4 small,
.h5 .small,
.h5 small,
.h6 .small,
.h6 small,
h1 .small,
h1 small,
h2 .small,
h2 small,
h3 .small,
h3 small,
h4 .small,
h4 small,
h5 .small,
h5 small,
h6 .small,
h6 small {
    font-weight: 400;
    line-height: 1;
    color: #777
}

.h1,
.h2,
.h3,
h1,
h2,
h3 {
    margin-top: 20px;
    margin-bottom: 10px
}

.h1 .small,
.h1 small,
.h2 .small,
.h2 small,
.h3 .small,
.h3 small,
h1 .small,
h1 small,
h2 .small,
h2 small,
h3 .small,
h3 small {
    font-size: 65%
}

.h4,
.h5,
.h6,
h4,
h5,
h6 {
    margin-top: 10px;
    margin-bottom: 10px
}

.h4 .small,
.h4 small,
.h5 .small,
.h5 small,
.h6 .small,
.h6 small,
h4 .small,
h4 small,
h5 .small,
h5 small,
h6 .small,
h6 small {
    font-size: 75%
}

.h1,
h1 {
    font-size: 36px
}

.h2,
h2 {
    font-size: 30px
}

.h3,
h3 {
    font-size: 24px
}

.h4,
h4 {
    font-size: 18px
}

.h5,
h5 {
    font-size: 14px
}

.h6,
h6 {
    font-size: 12px
}

p {
    margin: 0 0 10px
}

.lead {
    margin-bottom: 20px;
    font-size: 16px;
    font-weight: 300;
    line-height: 1.4
}

@media (min-width:768px) {
    .lead {
        font-size: 21px
    }
}

.small,
small {
    font-size: 85%
}

.mark,
mark {
    padding: .2em;
    background-color: #fcf8e3
}

.text-left {
    text-align: left
}

.text-right {
    text-align: right
}

.text-center {
    text-align: center
}

.text-justify {
    text-align: justify
}

.text-nowrap {
    white-space: nowrap
}

.text-lowercase {
    text-transform: lowercase
}

.text-uppercase {
    text-transform: uppercase
}

.text-capitalize {
    text-transform: capitalize
}

.text-muted {
    color: #777
}

.text-primary {
    color: #337ab7
}

a.text-primary:focus,
a.text-primary:hover {
    color: #286090
}

.text-success {
    color: #3c763d
}

a.text-success:focus,
a.text-success:hover {
    color: #2b542c
}

.text-info {
    color: #31708f
}

a.text-info:focus,
a.text-info:hover {
    color: #245269
}

.text-warning {
    color: #8a6d3b
}

a.text-warning:focus,
a.text-warning:hover {
    color: #66512c
}

.text-danger {
    color: #a94442
}

a.text-danger:focus,
a.text-danger:hover {
    color: #843534
}

.bg-primary {
    color: #fff;
    background-color: #337ab7
}

a.bg-primary:focus,
a.bg-primary:hover {
    background-color: #286090
}

.bg-success {
    background-color: #dff0d8
}

a.bg-success:focus,
a.bg-success:hover {
    background-color: #c1e2b3
}

.bg-info {
    background-color: #d9edf7
}

a.bg-info:focus,
a.bg-info:hover {
    background-color: #afd9ee
}

.bg-warning {
    background-color: #fcf8e3
}

a.bg-warning:focus,
a.bg-warning:hover {
    background-color: #f7ecb5
}

.bg-danger {
    background-color: #f2dede
}

a.bg-danger:focus,
a.bg-danger:hover {
    background-color: #e4b9b9
}

.page-header {
    padding-bottom: 9px;
    margin: 40px 0 20px;
    border-bottom: 1px solid #eee
}

ol,
ul {
    margin-top: 0;
    margin-bottom: 10px
}

ol ol,
ol ul,
ul ol,
ul ul {
    margin-bottom: 0
}

.list-unstyled {
    padding-left: 0;
    list-style: none
}

.list-inline {
    padding-left: 0;
    margin-left: -5px;
    list-style: none
}

.list-inline>li {
    display: inline-block;
    padding-right: 5px;
    padding-left: 5px
}

dl {
    margin-top: 0;
    margin-bottom: 20px
}

dd,
dt {
    line-height: 1.42857143
}

dt {
    font-weight: 700
}

dd {
    margin-left: 0
}

@media (min-width:768px) {
    .dl-horizontal dt {
        float: left;
        width: 160px;
        overflow: hidden;
        clear: left;
        text-align: right;
        text-overflow: ellipsis;
        white-space: nowrap
    }
    .dl-horizontal dd {
        margin-left: 180px
    }
}

abbr[data-original-title],
abbr[title] {
    cursor: help;
    border-bottom: 1px dotted #777
}

.initialism {
    font-size: 90%;
    text-transform: uppercase
}

blockquote {
    padding: 10px 20px;
    margin: 0 0 20px;
    font-size: 17.5px;
    border-left: 5px solid #eee
}

blockquote ol:last-child,
blockquote p:last-child,
blockquote ul:last-child {
    margin-bottom: 0
}

blockquote .small,
blockquote footer,
blockquote small {
    display: block;
    font-size: 80%;
    line-height: 1.42857143;
    color: #777
}

blockquote .small:before,
blockquote footer:before,
blockquote small:before {
    content: '\2014 \00A0'
}

.blockquote-reverse,
blockquote.pull-right {
    padding-right: 15px;
    padding-left: 0;
    text-align: right;
    border-right: 5px solid #eee;
    border-left: 0
}

.blockquote-reverse .small:before,
.blockquote-reverse footer:before,
.blockquote-reverse small:before,
blockquote.pull-right .small:before,
blockquote.pull-right footer:before,
blockquote.pull-right small:before {
    content: ''
}

.blockquote-reverse .small:after,
.blockquote-reverse footer:after,
.blockquote-reverse small:after,
blockquote.pull-right .small:after,
blockquote.pull-right footer:after,
blockquote.pull-right small:after {
    content: '\00A0 \2014'
}

address {
    margin-bottom: 20px;
    font-style: normal;
    line-height: 1.42857143
}

code,
kbd,
pre,
samp {
    font-family: Menlo, Monaco, Consolas, "Courier New", monospace
}

code {
    padding: 2px 4px;
    font-size: 90%;
    color: #c7254e;
    background-color: #f9f2f4;
    border-radius: 4px
}

kbd {
    padding: 2px 4px;
    font-size: 90%;
    color: #fff;
    background-color: #333;
    border-radius: 3px;
    -webkit-box-shadow: inset 0 -1px 0 rgba(0, 0, 0, .25);
    box-shadow: inset 0 -1px 0 rgba(0, 0, 0, .25)
}

kbd kbd {
    padding: 0;
    font-size: 100%;
    font-weight: 700;
    -webkit-box-shadow: none;
    box-shadow: none
}

pre {
    display: block;
    padding: 9.5px;
    margin: 0 0 10px;
    font-size: 13px;
    line-height: 1.42857143;
    color: #333;
    word-break: break-all;
    word-wrap: break-word;
    background-color: #f5f5f5;
    border: 1px solid #ccc;
    border-radius: 4px
}

pre code {
    padding: 0;
    font-size: inherit;
    color: inherit;
    white-space: pre-wrap;
    background-color: transparent;
    border-radius: 0
}

.pre-scrollable {
    max-height: 340px;
    overflow-y: scroll
}

.container {
    padding-right: 15px;
    padding-left: 15px;
    margin-right: auto;
    margin-left: auto
}

@media (min-width:768px) {
    .container {
        width: 750px
    }
}

@media (min-width:992px) {
    .container {
        width: 970px
    }
}

@media (min-width:1200px) {
    .container {
        width: 1170px
    }
}

.container-fluid {
    padding-right: 15px;
    padding-left: 15px;
    margin-right: auto;
    margin-left: auto
}

.row {
    margin-right: -15px;
    margin-left: -15px
}

.col-lg-1,
.col-lg-10,
.col-lg-11,
.col-lg-12,
.col-lg-2,
.col-lg-3,
.col-lg-4,
.col-lg-5,
.col-lg-6,
.col-lg-7,
.col-lg-8,
.col-lg-9,
.col-md-1,
.col-md-10,
.col-md-11,
.col-md-12,
.col-md-2,
.col-md-3,
.col-md-4,
.col-md-5,
.col-md-6,
.col-md-7,
.col-md-8,
.col-md-9,
.col-sm-1,
.col-sm-10,
.col-sm-11,
.col-sm-12,
.col-sm-2,
.col-sm-3,
.col-sm-4,
.col-sm-5,
.col-sm-6,
.col-sm-7,
.col-sm-8,
.col-sm-9,
.col-xs-1,
.col-xs-10,
.col-xs-11,
.col-xs-12,
.col-xs-2,
.col-xs-3,
.col-xs-4,
.col-xs-5,
.col-xs-6,
.col-xs-7,
.col-xs-8,
.col-xs-9 {
    position: relative;
    min-height: 1px;
    padding-right: 15px;
    padding-left: 15px
}

.col-xs-1,
.col-xs-10,
.col-xs-11,
.col-xs-12,
.col-xs-2,
.col-xs-3,
.col-xs-4,
.col-xs-5,
.col-xs-6,
.col-xs-7,
.col-xs-8,
.col-xs-9 {
    float: left
}

.col-xs-12 {
    width: 100%
}

.col-xs-11 {
    width: 91.66666667%
}

.col-xs-10 {
    width: 83.33333333%
}

.col-xs-9 {
    width: 75%
}

.col-xs-8 {
    width: 66.66666667%
}

.col-xs-7 {
    width: 58.33333333%
}

.col-xs-6 {
    width: 50%
}

.col-xs-5 {
    width: 41.66666667%
}

.col-xs-4 {
    width: 33.33333333%
}

.col-xs-3 {
    width: 25%
}

.col-xs-2 {
    width: 16.66666667%
}

.col-xs-1 {
    width: 8.33333333%
}

.col-xs-pull-12 {
    right: 100%
}

.col-xs-pull-11 {
    right: 91.66666667%
}

.col-xs-pull-10 {
    right: 83.33333333%
}

.col-xs-pull-9 {
    right: 75%
}

.col-xs-pull-8 {
    right: 66.66666667%
}

.col-xs-pull-7 {
    right: 58.33333333%
}

.col-xs-pull-6 {
    right: 50%
}

.col-xs-pull-5 {
    right: 41.66666667%
}

.col-xs-pull-4 {
    right: 33.33333333%
}

.col-xs-pull-3 {
    right: 25%
}

.col-xs-pull-2 {
    right: 16.66666667%
}

.col-xs-pull-1 {
    right: 8.33333333%
}

.col-xs-pull-0 {
    right: auto
}

.col-xs-push-12 {
    left: 100%
}

.col-xs-push-11 {
    left: 91.66666667%
}

.col-xs-push-10 {
    left: 83.33333333%
}

.col-xs-push-9 {
    left: 75%
}

.col-xs-push-8 {
    left: 66.66666667%
}

.col-xs-push-7 {
    left: 58.33333333%
}

.col-xs-push-6 {
    left: 50%
}

.col-xs-push-5 {
    left: 41.66666667%
}

.col-xs-push-4 {
    left: 33.33333333%
}

.col-xs-push-3 {
    left: 25%
}

.col-xs-push-2 {
    left: 16.66666667%
}

.col-xs-push-1 {
    left: 8.33333333%
}

.col-xs-push-0 {
    left: auto
}

.col-xs-offset-12 {
    margin-left: 100%
}

.col-xs-offset-11 {
    margin-left: 91.66666667%
}

.col-xs-offset-10 {
    margin-left: 83.33333333%
}

.col-xs-offset-9 {
    margin-left: 75%
}

.col-xs-offset-8 {
    margin-left: 66.66666667%
}

.col-xs-offset-7 {
    margin-left: 58.33333333%
}

.col-xs-offset-6 {
    margin-left: 50%
}

.col-xs-offset-5 {
    margin-left: 41.66666667%
}

.col-xs-offset-4 {
    margin-left: 33.33333333%
}

.col-xs-offset-3 {
    margin-left: 25%
}

.col-xs-offset-2 {
    margin-left: 16.66666667%
}

.col-xs-offset-1 {
    margin-left: 8.33333333%
}

.col-xs-offset-0 {
    margin-left: 0
}

@media (min-width:768px) {
    .col-sm-1,
    .col-sm-10,
    .col-sm-11,
    .col-sm-12,
    .col-sm-2,
    .col-sm-3,
    .col-sm-4,
    .col-sm-5,
    .col-sm-6,
    .col-sm-7,
    .col-sm-8,
    .col-sm-9 {
        float: left
    }
    .col-sm-12 {
        width: 100%
    }
    .col-sm-11 {
        width: 91.66666667%
    }
    .col-sm-10 {
        width: 83.33333333%
    }
    .col-sm-9 {
        width: 75%
    }
    .col-sm-8 {
        width: 66.66666667%
    }
    .col-sm-7 {
        width: 58.33333333%
    }
    .col-sm-6 {
        width: 50%
    }
    .col-sm-5 {
        width: 41.66666667%
    }
    .col-sm-4 {
        width: 33.33333333%
    }
    .col-sm-3 {
        width: 25%
    }
    .col-sm-2 {
        width: 16.66666667%
    }
    .col-sm-1 {
        width: 8.33333333%
    }
    .col-sm-pull-12 {
        right: 100%
    }
    .col-sm-pull-11 {
        right: 91.66666667%
    }
    .col-sm-pull-10 {
        right: 83.33333333%
    }
    .col-sm-pull-9 {
        right: 75%
    }
    .col-sm-pull-8 {
        right: 66.66666667%
    }
    .col-sm-pull-7 {
        right: 58.33333333%
    }
    .col-sm-pull-6 {
        right: 50%
    }
    .col-sm-pull-5 {
        right: 41.66666667%
    }
    .col-sm-pull-4 {
        right: 33.33333333%
    }
    .col-sm-pull-3 {
        right: 25%
    }
    .col-sm-pull-2 {
        right: 16.66666667%
    }
    .col-sm-pull-1 {
        right: 8.33333333%
    }
    .col-sm-pull-0 {
        right: auto
    }
    .col-sm-push-12 {
        left: 100%
    }
    .col-sm-push-11 {
        left: 91.66666667%
    }
    .col-sm-push-10 {
        left: 83.33333333%
    }
    .col-sm-push-9 {
        left: 75%
    }
    .col-sm-push-8 {
        left: 66.66666667%
    }
    .col-sm-push-7 {
        left: 58.33333333%
    }
    .col-sm-push-6 {
        left: 50%
    }
    .col-sm-push-5 {
        left: 41.66666667%
    }
    .col-sm-push-4 {
        left: 33.33333333%
    }
    .col-sm-push-3 {
        left: 25%
    }
    .col-sm-push-2 {
        left: 16.66666667%
    }
    .col-sm-push-1 {
        left: 8.33333333%
    }
    .col-sm-push-0 {
        left: auto
    }
    .col-sm-offset-12 {
        margin-left: 100%
    }
    .col-sm-offset-11 {
        margin-left: 91.66666667%
    }
    .col-sm-offset-10 {
        margin-left: 83.33333333%
    }
    .col-sm-offset-9 {
        margin-left: 75%
    }
    .col-sm-offset-8 {
        margin-left: 66.66666667%
    }
    .col-sm-offset-7 {
        margin-left: 58.33333333%
    }
    .col-sm-offset-6 {
        margin-left: 50%
    }
    .col-sm-offset-5 {
        margin-left: 41.66666667%
    }
    .col-sm-offset-4 {
        margin-left: 33.33333333%
    }
    .col-sm-offset-3 {
        margin-left: 25%
    }
    .col-sm-offset-2 {
        margin-left: 16.66666667%
    }
    .col-sm-offset-1 {
        margin-left: 8.33333333%
    }
    .col-sm-offset-0 {
        margin-left: 0
    }
}

@media (min-width:992px) {
    .col-md-1,
    .col-md-10,
    .col-md-11,
    .col-md-12,
    .col-md-2,
    .col-md-3,
    .col-md-4,
    .col-md-5,
    .col-md-6,
    .col-md-7,
    .col-md-8,
    .col-md-9 {
        float: left
    }
    .col-md-12 {
        width: 100%
    }
    .col-md-11 {
        width: 91.66666667%
    }
    .col-md-10 {
        width: 83.33333333%
    }
    .col-md-9 {
        width: 75%
    }
    .col-md-8 {
        width: 66.66666667%
    }
    .col-md-7 {
        width: 58.33333333%
    }
    .col-md-6 {
        width: 50%
    }
    .col-md-5 {
        width: 41.66666667%
    }
    .col-md-4 {
        width: 33.33333333%
    }
    .col-md-3 {
        width: 25%
    }
    .col-md-2 {
        width: 16.66666667%
    }
    .col-md-1 {
        width: 8.33333333%
    }
    .col-md-pull-12 {
        right: 100%
    }
    .col-md-pull-11 {
        right: 91.66666667%
    }
    .col-md-pull-10 {
        right: 83.33333333%
    }
    .col-md-pull-9 {
        right: 75%
    }
    .col-md-pull-8 {
        right: 66.66666667%
    }
    .col-md-pull-7 {
        right: 58.33333333%
    }
    .col-md-pull-6 {
        right: 50%
    }
    .col-md-pull-5 {
        right: 41.66666667%
    }
    .col-md-pull-4 {
        right: 33.33333333%
    }
    .col-md-pull-3 {
        right: 25%
    }
    .col-md-pull-2 {
        right: 16.66666667%
    }
    .col-md-pull-1 {
        right: 8.33333333%
    }
    .col-md-pull-0 {
        right: auto
    }
    .col-md-push-12 {
        left: 100%
    }
    .col-md-push-11 {
        left: 91.66666667%
    }
    .col-md-push-10 {
        left: 83.33333333%
    }
    .col-md-push-9 {
        left: 75%
    }
    .col-md-push-8 {
        left: 66.66666667%
    }
    .col-md-push-7 {
        left: 58.33333333%
    }
    .col-md-push-6 {
        left: 50%
    }
    .col-md-push-5 {
        left: 41.66666667%
    }
    .col-md-push-4 {
        left: 33.33333333%
    }
    .col-md-push-3 {
        left: 25%
    }
    .col-md-push-2 {
        left: 16.66666667%
    }
    .col-md-push-1 {
        left: 8.33333333%
    }
    .col-md-push-0 {
        left: auto
    }
    .col-md-offset-12 {
        margin-left: 100%
    }
    .col-md-offset-11 {
        margin-left: 91.66666667%
    }
    .col-md-offset-10 {
        margin-left: 83.33333333%
    }
    .col-md-offset-9 {
        margin-left: 75%
    }
    .col-md-offset-8 {
        margin-left: 66.66666667%
    }
    .col-md-offset-7 {
        margin-left: 58.33333333%
    }
    .col-md-offset-6 {
        margin-left: 50%
    }
    .col-md-offset-5 {
        margin-left: 41.66666667%
    }
    .col-md-offset-4 {
        margin-left: 33.33333333%
    }
    .col-md-offset-3 {
        margin-left: 25%
    }
    .col-md-offset-2 {
        margin-left: 16.66666667%
    }
    .col-md-offset-1 {
        margin-left: 8.33333333%
    }
    .col-md-offset-0 {
        margin-left: 0
    }
}

@media (min-width:1200px) {
    .col-lg-1,
    .col-lg-10,
    .col-lg-11,
    .col-lg-12,
    .col-lg-2,
    .col-lg-3,
    .col-lg-4,
    .col-lg-5,
    .col-lg-6,
    .col-lg-7,
    .col-lg-8,
    .col-lg-9 {
        float: left
    }
    .col-lg-12 {
        width: 100%
    }
    .col-lg-11 {
        width: 91.66666667%
    }
    .col-lg-10 {
        width: 83.33333333%
    }
    .col-lg-9 {
        width: 75%
    }
    .col-lg-8 {
        width: 66.66666667%
    }
    .col-lg-7 {
        width: 58.33333333%
    }
    .col-lg-6 {
        width: 50%
    }
    .col-lg-5 {
        width: 41.66666667%
    }
    .col-lg-4 {
        width: 33.33333333%
    }
    .col-lg-3 {
        width: 25%
    }
    .col-lg-2 {
        width: 16.66666667%
    }
    .col-lg-1 {
        width: 8.33333333%
    }
    .col-lg-pull-12 {
        right: 100%
    }
    .col-lg-pull-11 {
        right: 91.66666667%
    }
    .col-lg-pull-10 {
        right: 83.33333333%
    }
    .col-lg-pull-9 {
        right: 75%
    }
    .col-lg-pull-8 {
        right: 66.66666667%
    }
    .col-lg-pull-7 {
        right: 58.33333333%
    }
    .col-lg-pull-6 {
        right: 50%
    }
    .col-lg-pull-5 {
        right: 41.66666667%
    }
    .col-lg-pull-4 {
        right: 33.33333333%
    }
    .col-lg-pull-3 {
        right: 25%
    }
    .col-lg-pull-2 {
        right: 16.66666667%
    }
    .col-lg-pull-1 {
        right: 8.33333333%
    }
    .col-lg-pull-0 {
        right: auto
    }
    .col-lg-push-12 {
        left: 100%
    }
    .col-lg-push-11 {
        left: 91.66666667%
    }
    .col-lg-push-10 {
        left: 83.33333333%
    }
    .col-lg-push-9 {
        left: 75%
    }
    .col-lg-push-8 {
        left: 66.66666667%
    }
    .col-lg-push-7 {
        left: 58.33333333%
    }
    .col-lg-push-6 {
        left: 50%
    }
    .col-lg-push-5 {
        left: 41.66666667%
    }
    .col-lg-push-4 {
        left: 33.33333333%
    }
    .col-lg-push-3 {
        left: 25%
    }
    .col-lg-push-2 {
        left: 16.66666667%
    }
    .col-lg-push-1 {
        left: 8.33333333%
    }
    .col-lg-push-0 {
        left: auto
    }
    .col-lg-offset-12 {
        margin-left: 100%
    }
    .col-lg-offset-11 {
        margin-left: 91.66666667%
    }
    .col-lg-offset-10 {
        margin-left: 83.33333333%
    }
    .col-lg-offset-9 {
        margin-left: 75%
    }
    .col-lg-offset-8 {
        margin-left: 66.66666667%
    }
    .col-lg-offset-7 {
        margin-left: 58.33333333%
    }
    .col-lg-offset-6 {
        margin-left: 50%
    }
    .col-lg-offset-5 {
        margin-left: 41.66666667%
    }
    .col-lg-offset-4 {
        margin-left: 33.33333333%
    }
    .col-lg-offset-3 {
        margin-left: 25%
    }
    .col-lg-offset-2 {
        margin-left: 16.66666667%
    }
    .col-lg-offset-1 {
        margin-left: 8.33333333%
    }
    .col-lg-offset-0 {
        margin-left: 0
    }
}

table {
    background-color: transparent
}

caption {
    padding-top: 8px;
    padding-bottom: 8px;
    color: #777;
    text-align: left
}

th {
    text-align: left
}

.table {
    width: 100%;
    max-width: 100%;
    margin-bottom: 20px
}

.table>tbody>tr>td,
.table>tbody>tr>th,
.table>tfoot>tr>td,
.table>tfoot>tr>th,
.table>thead>tr>td,
.table>thead>tr>th {
    padding: 8px;
    line-height: 1.42857143;
    vertical-align: top;
    border-top: 1px solid #ddd
}

.table>thead>tr>th {
    vertical-align: bottom;
    border-bottom: 2px solid #ddd
}

.table>caption+thead>tr:first-child>td,
.table>caption+thead>tr:first-child>th,
.table>colgroup+thead>tr:first-child>td,
.table>colgroup+thead>tr:first-child>th,
.table>thead:first-child>tr:first-child>td,
.table>thead:first-child>tr:first-child>th {
    border-top: 0
}

.table>tbody+tbody {
    border-top: 2px solid #ddd
}

.table .table {
    background-color: #fff
}

.table-condensed>tbody>tr>td,
.table-condensed>tbody>tr>th,
.table-condensed>tfoot>tr>td,
.table-condensed>tfoot>tr>th,
.table-condensed>thead>tr>td,
.table-condensed>thead>tr>th {
    padding: 5px
}

.table-bordered {
    border: 1px solid #ddd
}

.table-bordered>tbody>tr>td,
.table-bordered>tbody>tr>th,
.table-bordered>tfoot>tr>td,
.table-bordered>tfoot>tr>th,
.table-bordered>thead>tr>td,
.table-bordered>thead>tr>th {
    border: 1px solid #ddd
}

.table-bordered>thead>tr>td,
.table-bordered>thead>tr>th {
    border-bottom-width: 2px
}

.table-striped>tbody>tr:nth-of-type(odd) {
    background-color: #f9f9f9
}

.table-hover>tbody>tr:hover {
    background-color: #f5f5f5
}

table col[class*=col-] {
    position: static;
    display: table-column;
    float: none
}

table td[class*=col-],
table th[class*=col-] {
    position: static;
    display: table-cell;
    float: none
}

.table>tbody>tr.active>td,
.table>tbody>tr.active>th,
.table>tbody>tr>td.active,
.table>tbody>tr>th.active,
.table>tfoot>tr.active>td,
.table>tfoot>tr.active>th,
.table>tfoot>tr>td.active,
.table>tfoot>tr>th.active,
.table>thead>tr.active>td,
.table>thead>tr.active>th,
.table>thead>tr>td.active,
.table>thead>tr>th.active {
    background-color: #f5f5f5
}

.table-hover>tbody>tr.active:hover>td,
.table-hover>tbody>tr.active:hover>th,
.table-hover>tbody>tr:hover>.active,
.table-hover>tbody>tr>td.active:hover,
.table-hover>tbody>tr>th.active:hover {
    background-color: #e8e8e8
}

.table>tbody>tr.success>td,
.table>tbody>tr.success>th,
.table>tbody>tr>td.success,
.table>tbody>tr>th.success,
.table>tfoot>tr.success>td,
.table>tfoot>tr.success>th,
.table>tfoot>tr>td.success,
.table>tfoot>tr>th.success,
.table>thead>tr.success>td,
.table>thead>tr.success>th,
.table>thead>tr>td.success,
.table>thead>tr>th.success {
    background-color: #dff0d8
}

.table-hover>tbody>tr.success:hover>td,
.table-hover>tbody>tr.success:hover>th,
.table-hover>tbody>tr:hover>.success,
.table-hover>tbody>tr>td.success:hover,
.table-hover>tbody>tr>th.success:hover {
    background-color: #d0e9c6
}

.table>tbody>tr.info>td,
.table>tbody>tr.info>th,
.table>tbody>tr>td.info,
.table>tbody>tr>th.info,
.table>tfoot>tr.info>td,
.table>tfoot>tr.info>th,
.table>tfoot>tr>td.info,
.table>tfoot>tr>th.info,
.table>thead>tr.info>td,
.table>thead>tr.info>th,
.table>thead>tr>td.info,
.table>thead>tr>th.info {
    background-color: #d9edf7
}

.table-hover>tbody>tr.info:hover>td,
.table-hover>tbody>tr.info:hover>th,
.table-hover>tbody>tr:hover>.info,
.table-hover>tbody>tr>td.info:hover,
.table-hover>tbody>tr>th.info:hover {
    background-color: #c4e3f3
}

.table>tbody>tr.warning>td,
.table>tbody>tr.warning>th,
.table>tbody>tr>td.warning,
.table>tbody>tr>th.warning,
.table>tfoot>tr.warning>td,
.table>tfoot>tr.warning>th,
.table>tfoot>tr>td.warning,
.table>tfoot>tr>th.warning,
.table>thead>tr.warning>td,
.table>thead>tr.warning>th,
.table>thead>tr>td.warning,
.table>thead>tr>th.warning {
    background-color: #fcf8e3
}

.table-hover>tbody>tr.warning:hover>td,
.table-hover>tbody>tr.warning:hover>th,
.table-hover>tbody>tr:hover>.warning,
.table-hover>tbody>tr>td.warning:hover,
.table-hover>tbody>tr>th.warning:hover {
    background-color: #faf2cc
}

.table>tbody>tr.danger>td,
.table>tbody>tr.danger>th,
.table>tbody>tr>td.danger,
.table>tbody>tr>th.danger,
.table>tfoot>tr.danger>td,
.table>tfoot>tr.danger>th,
.table>tfoot>tr>td.danger,
.table>tfoot>tr>th.danger,
.table>thead>tr.danger>td,
.table>thead>tr.danger>th,
.table>thead>tr>td.danger,
.table>thead>tr>th.danger {
    background-color: #f2dede
}

.table-hover>tbody>tr.danger:hover>td,
.table-hover>tbody>tr.danger:hover>th,
.table-hover>tbody>tr:hover>.danger,
.table-hover>tbody>tr>td.danger:hover,
.table-hover>tbody>tr>th.danger:hover {
    background-color: #ebcccc
}

.table-responsive {
    min-height: .01%;
    overflow-x: auto
}

@media screen and (max-width:767px) {
    .table-responsive {
        width: 100%;
        margin-bottom: 15px;
        overflow-y: hidden;
        -ms-overflow-style: -ms-autohiding-scrollbar;
        border: 1px solid #ddd
    }
    .table-responsive>.table {
        margin-bottom: 0
    }
    .table-responsive>.table>tbody>tr>td,
    .table-responsive>.table>tbody>tr>th,
    .table-responsive>.table>tfoot>tr>td,
    .table-responsive>.table>tfoot>tr>th,
    .table-responsive>.table>thead>tr>td,
    .table-responsive>.table>thead>tr>th {
        white-space: nowrap
    }
    .table-responsive>.table-bordered {
        border: 0
    }
    .table-responsive>.table-bordered>tbody>tr>td:first-child,
    .table-responsive>.table-bordered>tbody>tr>th:first-child,
    .table-responsive>.table-bordered>tfoot>tr>td:first-child,
    .table-responsive>.table-bordered>tfoot>tr>th:first-child,
    .table-responsive>.table-bordered>thead>tr>td:first-child,
    .table-responsive>.table-bordered>thead>tr>th:first-child {
        border-left: 0
    }
    .table-responsive>.table-bordered>tbody>tr>td:last-child,
    .table-responsive>.table-bordered>tbody>tr>th:last-child,
    .table-responsive>.table-bordered>tfoot>tr>td:last-child,
    .table-responsive>.table-bordered>tfoot>tr>th:last-child,
    .table-responsive>.table-bordered>thead>tr>td:last-child,
    .table-responsive>.table-bordered>thead>tr>th:last-child {
        border-right: 0
    }
    .table-responsive>.table-bordered>tbody>tr:last-child>td,
    .table-responsive>.table-bordered>tbody>tr:last-child>th,
    .table-responsive>.table-bordered>tfoot>tr:last-child>td,
    .table-responsive>.table-bordered>tfoot>tr:last-child>th {
        border-bottom: 0
    }
}

fieldset {
    min-width: 0;
    padding: 0;
    margin: 0;
    border: 0
}

legend {
    display: block;
    width: 100%;
    padding: 0;
    margin-bottom: 20px;
    font-size: 21px;
    line-height: inherit;
    color: #333;
    border: 0;
    border-bottom: 1px solid #e5e5e5
}

label {
    display: inline-block;
    max-width: 100%;
    margin-bottom: 5px;
    font-weight: 700
}

input[type=search] {
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box
}

input[type=checkbox],
input[type=radio] {
    margin: 4px 0 0;
    line-height: normal
}

input[type=file] {
    display: block
}

input[type=range] {
    display: block;
    width: 100%
}

select[multiple],
select[size] {
    height: auto
}

input[type=checkbox]:focus,
input[type=file]:focus,
input[type=radio]:focus {
    outline: 5px auto -webkit-focus-ring-color;
    outline-offset: -2px
}

output {
    display: block;
    padding-top: 7px;
    font-size: 14px;
    line-height: 1.42857143;
    color: #555
}

.form-control {
    display: block;
    width: 100%;
    height: 34px;
    padding: 6px 12px;
    font-size: 14px;
    line-height: 1.42857143;
    color: #555;
    background-color: #fff;
    background-image: none;
    border: 1px solid #ccc;
    border-radius: 4px;
    -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075);
    box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075);
    -webkit-transition: border-color ease-in-out .15s, -webkit-box-shadow ease-in-out .15s;
    -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
    transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s
}

.form-control:focus {
    border-color: #66afe9;
    outline: 0;
    -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075), 0 0 8px rgba(102, 175, 233, .6);
    box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075), 0 0 8px rgba(102, 175, 233, .6)
}

.form-control::-moz-placeholder {
    color: #999;
    opacity: 1
}

.form-control:-ms-input-placeholder {
    color: #999
}

.form-control::-webkit-input-placeholder {
    color: #999
}

.form-control::-ms-expand {
    background-color: transparent;
    border: 0
}

.form-control[disabled],
.form-control[readonly],
fieldset[disabled] .form-control {
    background-color: #eee;
    opacity: 1
}

.form-control[disabled],
fieldset[disabled] .form-control {
    cursor: not-allowed
}

textarea.form-control {
    height: auto
}

input[type=search] {
    -webkit-appearance: none
}

@media screen and (-webkit-min-device-pixel-ratio:0) {
    input[type=date].form-control,
    input[type=datetime-local].form-control,
    input[type=month].form-control,
    input[type=time].form-control {
        line-height: 34px
    }
    .input-group-sm input[type=date],
    .input-group-sm input[type=datetime-local],
    .input-group-sm input[type=month],
    .input-group-sm input[type=time],
    input[type=date].input-sm,
    input[type=datetime-local].input-sm,
    input[type=month].input-sm,
    input[type=time].input-sm {
        line-height: 30px
    }
    .input-group-lg input[type=date],
    .input-group-lg input[type=datetime-local],
    .input-group-lg input[type=month],
    .input-group-lg input[type=time],
    input[type=date].input-lg,
    input[type=datetime-local].input-lg,
    input[type=month].input-lg,
    input[type=time].input-lg {
        line-height: 46px
    }
}

.form-group {
    margin-bottom: 15px
}

.checkbox,
.radio {
    position: relative;
    display: block;
    margin-top: 10px;
    margin-bottom: 10px
}

.checkbox label,
.radio label {
    min-height: 20px;
    padding-left: 20px;
    margin-bottom: 0;
    font-weight: 400;
    cursor: pointer
}

.checkbox input[type=checkbox],
.checkbox-inline input[type=checkbox],
.radio input[type=radio],
.radio-inline input[type=radio] {
    position: absolute;
    margin-left: -20px
}

.checkbox+.checkbox,
.radio+.radio {
    margin-top: -5px
}

.checkbox-inline,
.radio-inline {
    position: relative;
    display: inline-block;
    padding-left: 20px;
    margin-bottom: 0;
    font-weight: 400;
    vertical-align: middle;
    cursor: pointer
}

.checkbox-inline+.checkbox-inline,
.radio-inline+.radio-inline {
    margin-top: 0;
    margin-left: 10px
}

fieldset[disabled] input[type=checkbox],
fieldset[disabled] input[type=radio],
input[type=checkbox].disabled,
input[type=checkbox][disabled],
input[type=radio].disabled,
input[type=radio][disabled] {
    cursor: not-allowed
}

.checkbox-inline.disabled,
.radio-inline.disabled,
fieldset[disabled] .checkbox-inline,
fieldset[disabled] .radio-inline {
    cursor: not-allowed
}

.checkbox.disabled label,
.radio.disabled label,
fieldset[disabled] .checkbox label,
fieldset[disabled] .radio label {
    cursor: not-allowed
}

.form-control-static {
    min-height: 34px;
    padding-top: 7px;
    padding-bottom: 7px;
    margin-bottom: 0
}

.form-control-static.input-lg,
.form-control-static.input-sm {
    padding-right: 0;
    padding-left: 0
}

.input-sm {
    height: 30px;
    padding: 5px 10px;
    font-size: 12px;
    line-height: 1.5;
    border-radius: 3px
}

select.input-sm {
    height: 30px;
    line-height: 30px
}

select[multiple].input-sm,
textarea.input-sm {
    height: auto
}

.form-group-sm .form-control {
    height: 30px;
    padding: 5px 10px;
    font-size: 12px;
    line-height: 1.5;
    border-radius: 3px
}

.form-group-sm select.form-control {
    height: 30px;
    line-height: 30px
}

.form-group-sm select[multiple].form-control,
.form-group-sm textarea.form-control {
    height: auto
}

.form-group-sm .form-control-static {
    height: 30px;
    min-height: 32px;
    padding: 6px 10px;
    font-size: 12px;
    line-height: 1.5
}

.input-lg {
    height: 46px;
    padding: 10px 16px;
    font-size: 18px;
    line-height: 1.3333333;
    border-radius: 6px
}

select.input-lg {
    height: 46px;
    line-height: 46px
}

select[multiple].input-lg,
textarea.input-lg {
    height: auto
}

.form-group-lg .form-control {
    height: 46px;
    padding: 10px 16px;
    font-size: 18px;
    line-height: 1.3333333;
    border-radius: 6px
}

.form-group-lg select.form-control {
    height: 46px;
    line-height: 46px
}

.form-group-lg select[multiple].form-control,
.form-group-lg textarea.form-control {
    height: auto
}

.form-group-lg .form-control-static {
    height: 46px;
    min-height: 38px;
    padding: 11px 16px;
    font-size: 18px;
    line-height: 1.3333333
}

.has-feedback {
    position: relative
}

.has-feedback .form-control {
    padding-right: 42.5px
}

.form-control-feedback {
    position: absolute;
    top: 0;
    right: 0;
    z-index: 2;
    display: block;
    width: 34px;
    height: 34px;
    line-height: 34px;
    text-align: center;
    pointer-events: none
}

.form-group-lg .form-control+.form-control-feedback,
.input-group-lg+.form-control-feedback,
.input-lg+.form-control-feedback {
    width: 46px;
    height: 46px;
    line-height: 46px
}

.form-group-sm .form-control+.form-control-feedback,
.input-group-sm+.form-control-feedback,
.input-sm+.form-control-feedback {
    width: 30px;
    height: 30px;
    line-height: 30px
}

.has-success .checkbox,
.has-success .checkbox-inline,
.has-success .control-label,
.has-success .help-block,
.has-success .radio,
.has-success .radio-inline,
.has-success.checkbox label,
.has-success.checkbox-inline label,
.has-success.radio label,
.has-success.radio-inline label {
    color: #3c763d
}

.has-success .form-control {
    border-color: #3c763d;
    -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075);
    box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075)
}

.has-success .form-control:focus {
    border-color: #2b542c;
    -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075), 0 0 6px #67b168;
    box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075), 0 0 6px #67b168
}

.has-success .input-group-addon {
    color: #3c763d;
    background-color: #dff0d8;
    border-color: #3c763d
}

.has-success .form-control-feedback {
    color: #3c763d
}

.has-warning .checkbox,
.has-warning .checkbox-inline,
.has-warning .control-label,
.has-warning .help-block,
.has-warning .radio,
.has-warning .radio-inline,
.has-warning.checkbox label,
.has-warning.checkbox-inline label,
.has-warning.radio label,
.has-warning.radio-inline label {
    color: #8a6d3b
}

.has-warning .form-control {
    border-color: #8a6d3b;
    -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075);
    box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075)
}

.has-warning .form-control:focus {
    border-color: #66512c;
    -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075), 0 0 6px #c0a16b;
    box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075), 0 0 6px #c0a16b
}

.has-warning .input-group-addon {
    color: #8a6d3b;
    background-color: #fcf8e3;
    border-color: #8a6d3b
}

.has-warning .form-control-feedback {
    color: #8a6d3b
}

.has-error .checkbox,
.has-error .checkbox-inline,
.has-error .control-label,
.has-error .help-block,
.has-error .radio,
.has-error .radio-inline,
.has-error.checkbox label,
.has-error.checkbox-inline label,
.has-error.radio label,
.has-error.radio-inline label {
    color: #a94442
}

.has-error .form-control {
    border-color: #a94442;
    -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075);
    box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075)
}

.has-error .form-control:focus {
    border-color: #843534;
    -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075), 0 0 6px #ce8483;
    box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075), 0 0 6px #ce8483
}

.has-error .input-group-addon {
    color: #a94442;
    background-color: #f2dede;
    border-color: #a94442
}

.has-error .form-control-feedback {
    color: #a94442
}

.has-feedback label~.form-control-feedback {
    top: 25px
}

.has-feedback label.sr-only~.form-control-feedback {
    top: 0
}

.help-block {
    display: block;
    margin-top: 5px;
    margin-bottom: 10px;
    color: #737373
}

@media (min-width:768px) {
    .form-inline .form-group {
        display: inline-block;
        margin-bottom: 0;
        vertical-align: middle
    }
    .form-inline .form-control {
        display: inline-block;
        width: auto;
        vertical-align: middle
    }
    .form-inline .form-control-static {
        display: inline-block
    }
    .form-inline .input-group {
        display: inline-table;
        vertical-align: middle
    }
    .form-inline .input-group .form-control,
    .form-inline .input-group .input-group-addon,
    .form-inline .input-group .input-group-btn {
        width: auto
    }
    .form-inline .input-group>.form-control {
        width: 100%
    }
    .form-inline .control-label {
        margin-bottom: 0;
        vertical-align: middle
    }
    .form-inline .checkbox,
    .form-inline .radio {
        display: inline-block;
        margin-top: 0;
        margin-bottom: 0;
        vertical-align: middle
    }
    .form-inline .checkbox label,
    .form-inline .radio label {
        padding-left: 0
    }
    .form-inline .checkbox input[type=checkbox],
    .form-inline .radio input[type=radio] {
        position: relative;
        margin-left: 0
    }
    .form-inline .has-feedback .form-control-feedback {
        top: 0
    }
}

.form-horizontal .checkbox,
.form-horizontal .checkbox-inline,
.form-horizontal .radio,
.form-horizontal .radio-inline {
    padding-top: 7px;
    margin-top: 0;
    margin-bottom: 0
}

.form-horizontal .checkbox,
.form-horizontal .radio {
    min-height: 27px
}

.form-horizontal .form-group {
    margin-right: -15px;
    margin-left: -15px
}

@media (min-width:768px) {
    .form-horizontal .control-label {
        padding-top: 7px;
        margin-bottom: 0;
        text-align: right
    }
}

.form-horizontal .has-feedback .form-control-feedback {
    right: 15px
}

@media (min-width:768px) {
    .form-horizontal .form-group-lg .control-label {
        padding-top: 11px;
        font-size: 18px
    }
}

@media (min-width:768px) {
    .form-horizontal .form-group-sm .control-label {
        padding-top: 6px;
        font-size: 12px
    }
}

.btn {
    display: inline-block;
    padding: 6px 12px;
    margin-bottom: 0;
    font-size: 14px;
    font-weight: 400;
    line-height: 1.42857143;
    text-align: center;
    white-space: nowrap;
    vertical-align: middle;
    -ms-touch-action: manipulation;
    touch-action: manipulation;
    cursor: pointer;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
    background-image: none;
    border: 1px solid transparent;
    border-radius: 4px
}

.btn.active.focus,
.btn.active:focus,
.btn.focus,
.btn:active.focus,
.btn:active:focus,
.btn:focus {
    outline: 5px auto -webkit-focus-ring-color;
    outline-offset: -2px
}

.btn.focus,
.btn:focus,
.btn:hover {
    color: #333;
    text-decoration: none
}

.btn.active,
.btn:active {
    background-image: none;
    outline: 0;
    -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, .125);
    box-shadow: inset 0 3px 5px rgba(0, 0, 0, .125)
}

.btn.disabled,
.btn[disabled],
fieldset[disabled] .btn {
    cursor: not-allowed;
    -webkit-box-shadow: none;
    box-shadow: none;
    opacity: .65
}

a.btn.disabled,
fieldset[disabled] a.btn {
    pointer-events: none
}

.btn-default {
    color: #333;
    background-color: #fff;
    border-color: #ccc
}

.btn-default.focus,
.btn-default:focus {
    color: #333;
    background-color: #e6e6e6;
    border-color: #8c8c8c
}

.btn-default:hover {
    color: #333;
    background-color: #e6e6e6;
    border-color: #adadad
}

.btn-default.active,
.btn-default:active,
.open>.dropdown-toggle.btn-default {
    color: #333;
    background-color: #e6e6e6;
    border-color: #adadad
}

.btn-default.active.focus,
.btn-default.active:focus,
.btn-default.active:hover,
.btn-default:active.focus,
.btn-default:active:focus,
.btn-default:active:hover,
.open>.dropdown-toggle.btn-default.focus,
.open>.dropdown-toggle.btn-default:focus,
.open>.dropdown-toggle.btn-default:hover {
    color: #333;
    background-color: #d4d4d4;
    border-color: #8c8c8c
}

.btn-default.active,
.btn-default:active,
.open>.dropdown-toggle.btn-default {
    background-image: none
}

.btn-default.disabled.focus,
.btn-default.disabled:focus,
.btn-default.disabled:hover,
.btn-default[disabled].focus,
.btn-default[disabled]:focus,
.btn-default[disabled]:hover,
fieldset[disabled] .btn-default.focus,
fieldset[disabled] .btn-default:focus,
fieldset[disabled] .btn-default:hover {
    background-color: #fff;
    border-color: #ccc
}

.btn-default .badge {
    color: #fff;
    background-color: #333
}

.btn-primary {
    color: #fff;
    background-color: #337ab7;
    border-color: #2e6da4
}

.btn-primary.focus,
.btn-primary:focus {
    color: #fff;
    background-color: #286090;
    border-color: #122b40
}

.btn-primary:hover {
    color: #fff;
    background-color: #286090;
    border-color: #204d74
}

.btn-primary.active,
.btn-primary:active,
.open>.dropdown-toggle.btn-primary {
    color: #fff;
    background-color: #286090;
    border-color: #204d74
}

.btn-primary.active.focus,
.btn-primary.active:focus,
.btn-primary.active:hover,
.btn-primary:active.focus,
.btn-primary:active:focus,
.btn-primary:active:hover,
.open>.dropdown-toggle.btn-primary.focus,
.open>.dropdown-toggle.btn-primary:focus,
.open>.dropdown-toggle.btn-primary:hover {
    color: #fff;
    background-color: #204d74;
    border-color: #122b40
}

.btn-primary.active,
.btn-primary:active,
.open>.dropdown-toggle.btn-primary {
    background-image: none
}

.btn-primary.disabled.focus,
.btn-primary.disabled:focus,
.btn-primary.disabled:hover,
.btn-primary[disabled].focus,
.btn-primary[disabled]:focus,
.btn-primary[disabled]:hover,
fieldset[disabled] .btn-primary.focus,
fieldset[disabled] .btn-primary:focus,
fieldset[disabled] .btn-primary:hover {
    background-color: #337ab7;
    border-color: #2e6da4
}

.btn-primary .badge {
    color: #337ab7;
    background-color: #fff
}

.btn-success {
    color: #fff;
    background-color: #5cb85c;
    border-color: #4cae4c
}

.btn-success.focus,
.btn-success:focus {
    color: #fff;
    background-color: #449d44;
    border-color: #255625
}

.btn-success:hover {
    color: #fff;
    background-color: #449d44;
    border-color: #398439
}

.btn-success.active,
.btn-success:active,
.open>.dropdown-toggle.btn-success {
    color: #fff;
    background-color: #449d44;
    border-color: #398439
}

.btn-success.active.focus,
.btn-success.active:focus,
.btn-success.active:hover,
.btn-success:active.focus,
.btn-success:active:focus,
.btn-success:active:hover,
.open>.dropdown-toggle.btn-success.focus,
.open>.dropdown-toggle.btn-success:focus,
.open>.dropdown-toggle.btn-success:hover {
    color: #fff;
    background-color: #398439;
    border-color: #255625
}

.btn-success.active,
.btn-success:active,
.open>.dropdown-toggle.btn-success {
    background-image: none
}

.btn-success.disabled.focus,
.btn-success.disabled:focus,
.btn-success.disabled:hover,
.btn-success[disabled].focus,
.btn-success[disabled]:focus,
.btn-success[disabled]:hover,
fieldset[disabled] .btn-success.focus,
fieldset[disabled] .btn-success:focus,
fieldset[disabled] .btn-success:hover {
    background-color: #5cb85c;
    border-color: #4cae4c
}

.btn-success .badge {
    color: #5cb85c;
    background-color: #fff
}

.btn-info {
    color: #fff;
    background-color: #5bc0de;
    border-color: #46b8da
}

.btn-info.focus,
.btn-info:focus {
    color: #fff;
    background-color: #31b0d5;
    border-color: #1b6d85
}

.btn-info:hover {
    color: #fff;
    background-color: #31b0d5;
    border-color: #269abc
}

.btn-info.active,
.btn-info:active,
.open>.dropdown-toggle.btn-info {
    color: #fff;
    background-color: #31b0d5;
    border-color: #269abc
}

.btn-info.active.focus,
.btn-info.active:focus,
.btn-info.active:hover,
.btn-info:active.focus,
.btn-info:active:focus,
.btn-info:active:hover,
.open>.dropdown-toggle.btn-info.focus,
.open>.dropdown-toggle.btn-info:focus,
.open>.dropdown-toggle.btn-info:hover {
    color: #fff;
    background-color: #269abc;
    border-color: #1b6d85
}

.btn-info.active,
.btn-info:active,
.open>.dropdown-toggle.btn-info {
    background-image: none
}

.btn-info.disabled.focus,
.btn-info.disabled:focus,
.btn-info.disabled:hover,
.btn-info[disabled].focus,
.btn-info[disabled]:focus,
.btn-info[disabled]:hover,
fieldset[disabled] .btn-info.focus,
fieldset[disabled] .btn-info:focus,
fieldset[disabled] .btn-info:hover {
    background-color: #5bc0de;
    border-color: #46b8da
}

.btn-info .badge {
    color: #5bc0de;
    background-color: #fff
}

.btn-warning {
    color: #fff;
    background-color: #f0ad4e;
    border-color: #eea236
}

.btn-warning.focus,
.btn-warning:focus {
    color: #fff;
    background-color: #ec971f;
    border-color: #985f0d
}

.btn-warning:hover {
    color: #fff;
    background-color: #ec971f;
    border-color: #d58512
}

.btn-warning.active,
.btn-warning:active,
.open>.dropdown-toggle.btn-warning {
    color: #fff;
    background-color: #ec971f;
    border-color: #d58512
}

.btn-warning.active.focus,
.btn-warning.active:focus,
.btn-warning.active:hover,
.btn-warning:active.focus,
.btn-warning:active:focus,
.btn-warning:active:hover,
.open>.dropdown-toggle.btn-warning.focus,
.open>.dropdown-toggle.btn-warning:focus,
.open>.dropdown-toggle.btn-warning:hover {
    color: #fff;
    background-color: #d58512;
    border-color: #985f0d
}

.btn-warning.active,
.btn-warning:active,
.open>.dropdown-toggle.btn-warning {
    background-image: none
}

.btn-warning.disabled.focus,
.btn-warning.disabled:focus,
.btn-warning.disabled:hover,
.btn-warning[disabled].focus,
.btn-warning[disabled]:focus,
.btn-warning[disabled]:hover,
fieldset[disabled] .btn-warning.focus,
fieldset[disabled] .btn-warning:focus,
fieldset[disabled] .btn-warning:hover {
    background-color: #f0ad4e;
    border-color: #eea236
}

.btn-warning .badge {
    color: #f0ad4e;
    background-color: #fff
}

.btn-danger {
    color: #fff;
    background-color: #d9534f;
    border-color: #d43f3a
}

.btn-danger.focus,
.btn-danger:focus {
    color: #fff;
    background-color: #c9302c;
    border-color: #761c19
}

.btn-danger:hover {
    color: #fff;
    background-color: #c9302c;
    border-color: #ac2925
}

.btn-danger.active,
.btn-danger:active,
.open>.dropdown-toggle.btn-danger {
    color: #fff;
    background-color: #c9302c;
    border-color: #ac2925
}

.btn-danger.active.focus,
.btn-danger.active:focus,
.btn-danger.active:hover,
.btn-danger:active.focus,
.btn-danger:active:focus,
.btn-danger:active:hover,
.open>.dropdown-toggle.btn-danger.focus,
.open>.dropdown-toggle.btn-danger:focus,
.open>.dropdown-toggle.btn-danger:hover {
    color: #fff;
    background-color: #ac2925;
    border-color: #761c19
}

.btn-danger.active,
.btn-danger:active,
.open>.dropdown-toggle.btn-danger {
    background-image: none
}

.btn-danger.disabled.focus,
.btn-danger.disabled:focus,
.btn-danger.disabled:hover,
.btn-danger[disabled].focus,
.btn-danger[disabled]:focus,
.btn-danger[disabled]:hover,
fieldset[disabled] .btn-danger.focus,
fieldset[disabled] .btn-danger:focus,
fieldset[disabled] .btn-danger:hover {
    background-color: #d9534f;
    border-color: #d43f3a
}

.btn-danger .badge {
    color: #d9534f;
    background-color: #fff
}

.btn-link {
    font-weight: 400;
    color: #337ab7;
    border-radius: 0
}

.btn-link,
.btn-link.active,
.btn-link:active,
.btn-link[disabled],
fieldset[disabled] .btn-link {
    background-color: transparent;
    -webkit-box-shadow: none;
    box-shadow: none
}

.btn-link,
.btn-link:active,
.btn-link:focus,
.btn-link:hover {
    border-color: transparent
}

.btn-link:focus,
.btn-link:hover {
    color: #23527c;
    text-decoration: underline;
    background-color: transparent
}

.btn-link[disabled]:focus,
.btn-link[disabled]:hover,
fieldset[disabled] .btn-link:focus,
fieldset[disabled] .btn-link:hover {
    color: #777;
    text-decoration: none
}

.btn-group-lg>.btn,
.btn-lg {
    padding: 10px 16px;
    font-size: 18px;
    line-height: 1.3333333;
    border-radius: 6px
}

.btn-group-sm>.btn,
.btn-sm {
    padding: 5px 10px;
    font-size: 12px;
    line-height: 1.5;
    border-radius: 3px
}

.btn-group-xs>.btn,
.btn-xs {
    padding: 1px 5px;
    font-size: 12px;
    line-height: 1.5;
    border-radius: 3px
}

.btn-block {
    display: block;
    width: 100%
}

.btn-block+.btn-block {
    margin-top: 5px
}

input[type=button].btn-block,
input[type=reset].btn-block,
input[type=submit].btn-block {
    width: 100%
}

.fade {
    opacity: 0;
    -webkit-transition: opacity .15s linear;
    -o-transition: opacity .15s linear;
    transition: opacity .15s linear
}

.fade.in {
    opacity: 1
}

.collapse {
    display: none
}

.collapse.in {
    display: block
}

tr.collapse.in {
    display: table-row
}

tbody.collapse.in {
    display: table-row-group
}

.collapsing {
    position: relative;
    height: 0;
    overflow: hidden;
    -webkit-transition-timing-function: ease;
    -o-transition-timing-function: ease;
    transition-timing-function: ease;
    -webkit-transition-duration: .35s;
    -o-transition-duration: .35s;
    transition-duration: .35s;
    -webkit-transition-property: height, visibility;
    -o-transition-property: height, visibility;
    transition-property: height, visibility
}

.caret {
    display: inline-block;
    width: 0;
    height: 0;
    margin-left: 2px;
    vertical-align: middle;
    border-top: 4px dashed;
    border-right: 4px solid transparent;
    border-left: 4px solid transparent
}

.dropdown,
.dropup {
    position: relative
}

.dropdown-toggle:focus {
    outline: 0
}

.dropdown-menu {
    position: absolute;
    top: 100%;
    left: 0;
    z-index: 1000;
    display: none;
    float: left;
    min-width: 160px;
    padding: 5px 0;
    margin: 2px 0 0;
    font-size: 14px;
    text-align: left;
    list-style: none;
    background-color: #fff;
    -webkit-background-clip: padding-box;
    background-clip: padding-box;
    border: 1px solid #ccc;
    border: 1px solid rgba(0, 0, 0, .15);
    border-radius: 4px;
    -webkit-box-shadow: 0 6px 12px rgba(0, 0, 0, .175);
    box-shadow: 0 6px 12px rgba(0, 0, 0, .175)
}

.dropdown-menu.pull-right {
    right: 0;
    left: auto
}

.dropdown-menu .divider {
    height: 1px;
    margin: 9px 0;
    overflow: hidden;
    background-color: #e5e5e5
}

.dropdown-menu>li>a {
    display: block;
    padding: 3px 20px;
    clear: both;
    font-weight: 400;
    line-height: 1.42857143;
    color: #333;
    white-space: nowrap
}

.dropdown-menu>li>a:focus,
.dropdown-menu>li>a:hover {
    color: #262626;
    text-decoration: none;
    background-color: #f5f5f5
}

.dropdown-menu>.active>a,
.dropdown-menu>.active>a:focus,
.dropdown-menu>.active>a:hover {
    color: #fff;
    text-decoration: none;
    background-color: #337ab7;
    outline: 0
}

.dropdown-menu>.disabled>a,
.dropdown-menu>.disabled>a:focus,
.dropdown-menu>.disabled>a:hover {
    color: #777
}

.dropdown-menu>.disabled>a:focus,
.dropdown-menu>.disabled>a:hover {
    text-decoration: none;
    cursor: not-allowed;
    background-color: transparent;
    background-image: none
}

.open>.dropdown-menu {
    display: block
}

.open>a {
    outline: 0
}

.dropdown-menu-right {
    right: 0;
    left: auto
}

.dropdown-menu-left {
    right: auto;
    left: 0
}

.dropdown-header {
    display: block;
    padding: 3px 20px;
    font-size: 12px;
    line-height: 1.42857143;
    color: #777;
    white-space: nowrap
}

.dropdown-backdrop {
    position: fixed;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    z-index: 990
}

.pull-right>.dropdown-menu {
    right: 0;
    left: auto
}

.dropup .caret,
.navbar-fixed-bottom .dropdown .caret {
    content: "";
    border-top: 0;
    border-bottom: 4px dashed
}

.dropup .dropdown-menu,
.navbar-fixed-bottom .dropdown .dropdown-menu {
    top: auto;
    bottom: 100%;
    margin-bottom: 2px
}

@media (min-width:768px) {
    .navbar-right .dropdown-menu {
        right: 0;
        left: auto
    }
    .navbar-right .dropdown-menu-left {
        right: auto;
        left: 0
    }
}

.btn-group,
.btn-group-vertical {
    position: relative;
    display: inline-block;
    vertical-align: middle
}

.btn-group-vertical>.btn,
.btn-group>.btn {
    position: relative;
    float: left
}

.btn-group-vertical>.btn.active,
.btn-group-vertical>.btn:active,
.btn-group-vertical>.btn:focus,
.btn-group-vertical>.btn:hover,
.btn-group>.btn.active,
.btn-group>.btn:active,
.btn-group>.btn:focus,
.btn-group>.btn:hover {
    z-index: 2
}

.btn-group .btn+.btn,
.btn-group .btn+.btn-group,
.btn-group .btn-group+.btn,
.btn-group .btn-group+.btn-group {
    margin-left: -1px
}

.btn-toolbar {
    margin-left: -5px
}

.btn-toolbar .btn,
.btn-toolbar .btn-group,
.btn-toolbar .input-group {
    float: left
}

.btn-toolbar>.btn,
.btn-toolbar>.btn-group,
.btn-toolbar>.input-group {
    margin-left: 5px
}

.btn-group>.btn:not(:first-child):not(:last-child):not(.dropdown-toggle) {
    border-radius: 0
}

.btn-group>.btn:first-child {
    margin-left: 0
}

.btn-group>.btn:first-child:not(:last-child):not(.dropdown-toggle) {
    border-top-right-radius: 0;
    border-bottom-right-radius: 0
}

.btn-group>.btn:last-child:not(:first-child),
.btn-group>.dropdown-toggle:not(:first-child) {
    border-top-left-radius: 0;
    border-bottom-left-radius: 0
}

.btn-group>.btn-group {
    float: left
}

.btn-group>.btn-group:not(:first-child):not(:last-child)>.btn {
    border-radius: 0
}

.btn-group>.btn-group:first-child:not(:last-child)>.btn:last-child,
.btn-group>.btn-group:first-child:not(:last-child)>.dropdown-toggle {
    border-top-right-radius: 0;
    border-bottom-right-radius: 0
}

.btn-group>.btn-group:last-child:not(:first-child)>.btn:first-child {
    border-top-left-radius: 0;
    border-bottom-left-radius: 0
}

.btn-group .dropdown-toggle:active,
.btn-group.open .dropdown-toggle {
    outline: 0
}

.btn-group>.btn+.dropdown-toggle {
    padding-right: 8px;
    padding-left: 8px
}

.btn-group>.btn-lg+.dropdown-toggle {
    padding-right: 12px;
    padding-left: 12px
}

.btn-group.open .dropdown-toggle {
    -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, .125);
    box-shadow: inset 0 3px 5px rgba(0, 0, 0, .125)
}

.btn-group.open .dropdown-toggle.btn-link {
    -webkit-box-shadow: none;
    box-shadow: none
}

.btn .caret {
    margin-left: 0
}

.btn-lg .caret {
    border-width: 5px 5px 0;
    border-bottom-width: 0
}

.dropup .btn-lg .caret {
    border-width: 0 5px 5px
}

.btn-group-vertical>.btn,
.btn-group-vertical>.btn-group,
.btn-group-vertical>.btn-group>.btn {
    display: block;
    float: none;
    width: 100%;
    max-width: 100%
}

.btn-group-vertical>.btn-group>.btn {
    float: none
}

.btn-group-vertical>.btn+.btn,
.btn-group-vertical>.btn+.btn-group,
.btn-group-vertical>.btn-group+.btn,
.btn-group-vertical>.btn-group+.btn-group {
    margin-top: -1px;
    margin-left: 0
}

.btn-group-vertical>.btn:not(:first-child):not(:last-child) {
    border-radius: 0
}

.btn-group-vertical>.btn:first-child:not(:last-child) {
    border-top-left-radius: 4px;
    border-top-right-radius: 4px;
    border-bottom-right-radius: 0;
    border-bottom-left-radius: 0
}

.btn-group-vertical>.btn:last-child:not(:first-child) {
    border-top-left-radius: 0;
    border-top-right-radius: 0;
    border-bottom-right-radius: 4px;
    border-bottom-left-radius: 4px
}

.btn-group-vertical>.btn-group:not(:first-child):not(:last-child)>.btn {
    border-radius: 0
}

.btn-group-vertical>.btn-group:first-child:not(:last-child)>.btn:last-child,
.btn-group-vertical>.btn-group:first-child:not(:last-child)>.dropdown-toggle {
    border-bottom-right-radius: 0;
    border-bottom-left-radius: 0
}

.btn-group-vertical>.btn-group:last-child:not(:first-child)>.btn:first-child {
    border-top-left-radius: 0;
    border-top-right-radius: 0
}

.btn-group-justified {
    display: table;
    width: 100%;
    table-layout: fixed;
    border-collapse: separate
}

.btn-group-justified>.btn,
.btn-group-justified>.btn-group {
    display: table-cell;
    float: none;
    width: 1%
}

.btn-group-justified>.btn-group .btn {
    width: 100%
}

.btn-group-justified>.btn-group .dropdown-menu {
    left: auto
}

[data-toggle=buttons]>.btn input[type=checkbox],
[data-toggle=buttons]>.btn input[type=radio],
[data-toggle=buttons]>.btn-group>.btn input[type=checkbox],
[data-toggle=buttons]>.btn-group>.btn input[type=radio] {
    position: absolute;
    clip: rect(0, 0, 0, 0);
    pointer-events: none
}

.input-group {
    position: relative;
    display: table;
    border-collapse: separate
}

.input-group[class*=col-] {
    float: none;
    padding-right: 0;
    padding-left: 0
}

.input-group .form-control {
    position: relative;
    z-index: 2;
    float: left;
    width: 100%;
    margin-bottom: 0
}

.input-group .form-control:focus {
    z-index: 3
}

.input-group-lg>.form-control,
.input-group-lg>.input-group-addon,
.input-group-lg>.input-group-btn>.btn {
    height: 46px;
    padding: 10px 16px;
    font-size: 18px;
    line-height: 1.3333333;
    border-radius: 6px
}

select.input-group-lg>.form-control,
select.input-group-lg>.input-group-addon,
select.input-group-lg>.input-group-btn>.btn {
    height: 46px;
    line-height: 46px
}

select[multiple].input-group-lg>.form-control,
select[multiple].input-group-lg>.input-group-addon,
select[multiple].input-group-lg>.input-group-btn>.btn,
textarea.input-group-lg>.form-control,
textarea.input-group-lg>.input-group-addon,
textarea.input-group-lg>.input-group-btn>.btn {
    height: auto
}

.input-group-sm>.form-control,
.input-group-sm>.input-group-addon,
.input-group-sm>.input-group-btn>.btn {
    height: 30px;
    padding: 5px 10px;
    font-size: 12px;
    line-height: 1.5;
    border-radius: 3px
}

select.input-group-sm>.form-control,
select.input-group-sm>.input-group-addon,
select.input-group-sm>.input-group-btn>.btn {
    height: 30px;
    line-height: 30px
}

select[multiple].input-group-sm>.form-control,
select[multiple].input-group-sm>.input-group-addon,
select[multiple].input-group-sm>.input-group-btn>.btn,
textarea.input-group-sm>.form-control,
textarea.input-group-sm>.input-group-addon,
textarea.input-group-sm>.input-group-btn>.btn {
    height: auto
}

.input-group .form-control,
.input-group-addon,
.input-group-btn {
    display: table-cell
}

.input-group .form-control:not(:first-child):not(:last-child),
.input-group-addon:not(:first-child):not(:last-child),
.input-group-btn:not(:first-child):not(:last-child) {
    border-radius: 0
}

.input-group-addon,
.input-group-btn {
    width: 1%;
    white-space: nowrap;
    vertical-align: middle
}

.input-group-addon {
    padding: 6px 12px;
    font-size: 14px;
    font-weight: 400;
    line-height: 1;
    color: #555;
    text-align: center;
    background-color: #eee;
    border: 1px solid #ccc;
    border-radius: 4px
}

.input-group-addon.input-sm {
    padding: 5px 10px;
    font-size: 12px;
    border-radius: 3px
}

.input-group-addon.input-lg {
    padding: 10px 16px;
    font-size: 18px;
    border-radius: 6px
}

.input-group-addon input[type=checkbox],
.input-group-addon input[type=radio] {
    margin-top: 0
}

.input-group .form-control:first-child,
.input-group-addon:first-child,
.input-group-btn:first-child>.btn,
.input-group-btn:first-child>.btn-group>.btn,
.input-group-btn:first-child>.dropdown-toggle,
.input-group-btn:last-child>.btn-group:not(:last-child)>.btn,
.input-group-btn:last-child>.btn:not(:last-child):not(.dropdown-toggle) {
    border-top-right-radius: 0;
    border-bottom-right-radius: 0
}

.input-group-addon:first-child {
    border-right: 0
}

.input-group .form-control:last-child,
.input-group-addon:last-child,
.input-group-btn:first-child>.btn-group:not(:first-child)>.btn,
.input-group-btn:first-child>.btn:not(:first-child),
.input-group-btn:last-child>.btn,
.input-group-btn:last-child>.btn-group>.btn,
.input-group-btn:last-child>.dropdown-toggle {
    border-top-left-radius: 0;
    border-bottom-left-radius: 0
}

.input-group-addon:last-child {
    border-left: 0
}

.input-group-btn {
    position: relative;
    font-size: 0;
    white-space: nowrap
}

.input-group-btn>.btn {
    position: relative
}

.input-group-btn>.btn+.btn {
    margin-left: -1px
}

.input-group-btn>.btn:active,
.input-group-btn>.btn:focus,
.input-group-btn>.btn:hover {
    z-index: 2
}

.input-group-btn:first-child>.btn,
.input-group-btn:first-child>.btn-group {
    margin-right: -1px
}

.input-group-btn:last-child>.btn,
.input-group-btn:last-child>.btn-group {
    z-index: 2;
    margin-left: -1px
}

.nav {
    padding-left: 0;
    margin-bottom: 0;
    list-style: none
}

.nav>li {
    position: relative;
    display: block
}

.nav>li>a {
    position: relative;
    display: block;
    padding: 10px 15px
}

.nav>li>a:focus,
.nav>li>a:hover {
    text-decoration: none;
    background-color: #eee
}

.nav>li.disabled>a {
    color: #777
}

.nav>li.disabled>a:focus,
.nav>li.disabled>a:hover {
    color: #777;
    text-decoration: none;
    cursor: not-allowed;
    background-color: transparent
}

.nav .open>a,
.nav .open>a:focus,
.nav .open>a:hover {
    background-color: #eee;
    border-color: #337ab7
}

.nav .nav-divider {
    height: 1px;
    margin: 9px 0;
    overflow: hidden;
    background-color: #e5e5e5
}

.nav>li>a>img {
    max-width: none
}

.nav-tabs {
    border-bottom: 1px solid #ddd
}

.nav-tabs>li {
    float: left;
    margin-bottom: -1px
}

.nav-tabs>li>a {
    margin-right: 2px;
    line-height: 1.42857143;
    border: 1px solid transparent;
    border-radius: 4px 4px 0 0
}

.nav-tabs>li>a:hover {
    border-color: #eee #eee #ddd
}

.nav-tabs>li.active>a,
.nav-tabs>li.active>a:focus,
.nav-tabs>li.active>a:hover {
    color: #555;
    cursor: default;
    background-color: #fff;
    border: 1px solid #ddd;
    border-bottom-color: transparent
}

.nav-tabs.nav-justified {
    width: 100%;
    border-bottom: 0
}

.nav-tabs.nav-justified>li {
    float: none
}

.nav-tabs.nav-justified>li>a {
    margin-bottom: 5px;
    text-align: center
}

.nav-tabs.nav-justified>.dropdown .dropdown-menu {
    top: auto;
    left: auto
}

@media (min-width:768px) {
    .nav-tabs.nav-justified>li {
        display: table-cell;
        width: 1%
    }
    .nav-tabs.nav-justified>li>a {
        margin-bottom: 0
    }
}

.nav-tabs.nav-justified>li>a {
    margin-right: 0;
    border-radius: 4px
}

.nav-tabs.nav-justified>.active>a,
.nav-tabs.nav-justified>.active>a:focus,
.nav-tabs.nav-justified>.active>a:hover {
    border: 1px solid #ddd
}

@media (min-width:768px) {
    .nav-tabs.nav-justified>li>a {
        border-bottom: 1px solid #ddd;
        border-radius: 4px 4px 0 0
    }
    .nav-tabs.nav-justified>.active>a,
    .nav-tabs.nav-justified>.active>a:focus,
    .nav-tabs.nav-justified>.active>a:hover {
        border-bottom-color: #fff
    }
}

.nav-pills>li {
    float: left
}

.nav-pills>li>a {
    border-radius: 4px
}

.nav-pills>li+li {
    margin-left: 2px
}

.nav-pills>li.active>a,
.nav-pills>li.active>a:focus,
.nav-pills>li.active>a:hover {
    color: #fff;
    background-color: #337ab7
}

.nav-stacked>li {
    float: none
}

.nav-stacked>li+li {
    margin-top: 2px;
    margin-left: 0
}

.nav-justified {
    width: 100%
}

.nav-justified>li {
    float: none
}

.nav-justified>li>a {
    margin-bottom: 5px;
    text-align: center
}

.nav-justified>.dropdown .dropdown-menu {
    top: auto;
    left: auto
}

@media (min-width:768px) {
    .nav-justified>li {
        display: table-cell;
        width: 1%
    }
    .nav-justified>li>a {
        margin-bottom: 0
    }
}

.nav-tabs-justified {
    border-bottom: 0
}

.nav-tabs-justified>li>a {
    margin-right: 0;
    border-radius: 4px
}

.nav-tabs-justified>.active>a,
.nav-tabs-justified>.active>a:focus,
.nav-tabs-justified>.active>a:hover {
    border: 1px solid #ddd
}

@media (min-width:768px) {
    .nav-tabs-justified>li>a {
        border-bottom: 1px solid #ddd;
        border-radius: 4px 4px 0 0
    }
    .nav-tabs-justified>.active>a,
    .nav-tabs-justified>.active>a:focus,
    .nav-tabs-justified>.active>a:hover {
        border-bottom-color: #fff
    }
}

.tab-content>.tab-pane {
    display: none
}

.tab-content>.active {
    display: block
}

.nav-tabs .dropdown-menu {
    margin-top: -1px;
    border-top-left-radius: 0;
    border-top-right-radius: 0
}

.navbar {
    position: relative;
    min-height: 50px;
    margin-bottom: 20px;
    border: 1px solid transparent
}

@media (min-width:768px) {
    .navbar {
        border-radius: 4px
    }
}

@media (min-width:768px) {
    .navbar-header {
        float: left
    }
}

.navbar-collapse {
    padding-right: 15px;
    padding-left: 15px;
    overflow-x: visible;
    -webkit-overflow-scrolling: touch;
    border-top: 1px solid transparent;
    -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, .1);
    box-shadow: inset 0 1px 0 rgba(255, 255, 255, .1)
}

.navbar-collapse.in {
    overflow-y: auto
}

@media (min-width:768px) {
    .navbar-collapse {
        width: auto;
        border-top: 0;
        -webkit-box-shadow: none;
        box-shadow: none
    }
    .navbar-collapse.collapse {
        display: block !important;
        height: auto !important;
        padding-bottom: 0;
        overflow: visible !important
    }
    .navbar-collapse.in {
        overflow-y: visible
    }
    .navbar-fixed-bottom .navbar-collapse,
    .navbar-fixed-top .navbar-collapse,
    .navbar-static-top .navbar-collapse {
        padding-right: 0;
        padding-left: 0
    }
}

.navbar-fixed-bottom .navbar-collapse,
.navbar-fixed-top .navbar-collapse {
    max-height: 340px
}

@media (max-device-width:480px) and (orientation:landscape) {
    .navbar-fixed-bottom .navbar-collapse,
    .navbar-fixed-top .navbar-collapse {
        max-height: 200px
    }
}

.container-fluid>.navbar-collapse,
.container-fluid>.navbar-header,
.container>.navbar-collapse,
.container>.navbar-header {
    margin-right: -15px;
    margin-left: -15px
}

@media (min-width:768px) {
    .container-fluid>.navbar-collapse,
    .container-fluid>.navbar-header,
    .container>.navbar-collapse,
    .container>.navbar-header {
        margin-right: 0;
        margin-left: 0
    }
}

.navbar-static-top {
    z-index: 1000;
    border-width: 0 0 1px
}

@media (min-width:768px) {
    .navbar-static-top {
        border-radius: 0
    }
}

.navbar-fixed-bottom,
.navbar-fixed-top {
    position: fixed;
    right: 0;
    left: 0;
    z-index: 1030
}

@media (min-width:768px) {
    .navbar-fixed-bottom,
    .navbar-fixed-top {
        border-radius: 0
    }
}

.navbar-fixed-top {
    top: 0;
    border-width: 0 0 1px
}

.navbar-fixed-bottom {
    bottom: 0;
    margin-bottom: 0;
    border-width: 1px 0 0
}

.navbar-brand {
    float: left;
    height: 50px;
    padding: 15px 15px;
    font-size: 18px;
    line-height: 20px
}

.navbar-brand:focus,
.navbar-brand:hover {
    text-decoration: none
}

.navbar-brand>img {
    display: block
}

@media (min-width:768px) {
    .navbar>.container .navbar-brand,
    .navbar>.container-fluid .navbar-brand {
        margin-left: -15px
    }
}

.navbar-toggle {
    position: relative;
    float: right;
    padding: 9px 10px;
    margin-top: 8px;
    margin-right: 15px;
    margin-bottom: 8px;
    background-color: transparent;
    background-image: none;
    border: 1px solid transparent;
    border-radius: 4px
}

.navbar-toggle:focus {
    outline: 0
}

.navbar-toggle .icon-bar {
    display: block;
    width: 22px;
    height: 2px;
    border-radius: 1px
}

.navbar-toggle .icon-bar+.icon-bar {
    margin-top: 4px
}

@media (min-width:768px) {
    .navbar-toggle {
        display: none
    }
}

.navbar-nav {
    margin: 7.5px -15px
}

.navbar-nav>li>a {
    padding-top: 10px;
    padding-bottom: 10px;
    line-height: 20px
}

@media (max-width:767px) {
    .navbar-nav .open .dropdown-menu {
        position: static;
        float: none;
        width: auto;
        margin-top: 0;
        background-color: transparent;
        border: 0;
        -webkit-box-shadow: none;
        box-shadow: none
    }
    .navbar-nav .open .dropdown-menu .dropdown-header,
    .navbar-nav .open .dropdown-menu>li>a {
        padding: 5px 15px 5px 25px
    }
    .navbar-nav .open .dropdown-menu>li>a {
        line-height: 20px
    }
    .navbar-nav .open .dropdown-menu>li>a:focus,
    .navbar-nav .open .dropdown-menu>li>a:hover {
        background-image: none
    }
}

@media (min-width:768px) {
    .navbar-nav {
        float: left;
        margin: 0
    }
    .navbar-nav>li {
        float: left
    }
    .navbar-nav>li>a {
        padding-top: 15px;
        padding-bottom: 15px
    }
}

.navbar-form {
    padding: 10px 15px;
    margin-top: 8px;
    margin-right: -15px;
    margin-bottom: 8px;
    margin-left: -15px;
    border-top: 1px solid transparent;
    border-bottom: 1px solid transparent;
    -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, .1), 0 1px 0 rgba(255, 255, 255, .1);
    box-shadow: inset 0 1px 0 rgba(255, 255, 255, .1), 0 1px 0 rgba(255, 255, 255, .1)
}

@media (min-width:768px) {
    .navbar-form .form-group {
        display: inline-block;
        margin-bottom: 0;
        vertical-align: middle
    }
    .navbar-form .form-control {
        display: inline-block;
        width: auto;
        vertical-align: middle
    }
    .navbar-form .form-control-static {
        display: inline-block
    }
    .navbar-form .input-group {
        display: inline-table;
        vertical-align: middle
    }
    .navbar-form .input-group .form-control,
    .navbar-form .input-group .input-group-addon,
    .navbar-form .input-group .input-group-btn {
        width: auto
    }
    .navbar-form .input-group>.form-control {
        width: 100%
    }
    .navbar-form .control-label {
        margin-bottom: 0;
        vertical-align: middle
    }
    .navbar-form .checkbox,
    .navbar-form .radio {
        display: inline-block;
        margin-top: 0;
        margin-bottom: 0;
        vertical-align: middle
    }
    .navbar-form .checkbox label,
    .navbar-form .radio label {
        padding-left: 0
    }
    .navbar-form .checkbox input[type=checkbox],
    .navbar-form .radio input[type=radio] {
        position: relative;
        margin-left: 0
    }
    .navbar-form .has-feedback .form-control-feedback {
        top: 0
    }
}

@media (max-width:767px) {
    .navbar-form .form-group {
        margin-bottom: 5px
    }
    .navbar-form .form-group:last-child {
        margin-bottom: 0
    }
}

@media (min-width:768px) {
    .navbar-form {
        width: auto;
        padding-top: 0;
        padding-bottom: 0;
        margin-right: 0;
        margin-left: 0;
        border: 0;
        -webkit-box-shadow: none;
        box-shadow: none
    }
}

.navbar-nav>li>.dropdown-menu {
    margin-top: 0;
    border-top-left-radius: 0;
    border-top-right-radius: 0
}

.navbar-fixed-bottom .navbar-nav>li>.dropdown-menu {
    margin-bottom: 0;
    border-top-left-radius: 4px;
    border-top-right-radius: 4px;
    border-bottom-right-radius: 0;
    border-bottom-left-radius: 0
}

.navbar-btn {
    margin-top: 8px;
    margin-bottom: 8px
}

.navbar-btn.btn-sm {
    margin-top: 10px;
    margin-bottom: 10px
}

.navbar-btn.btn-xs {
    margin-top: 14px;
    margin-bottom: 14px
}

.navbar-text {
    margin-top: 15px;
    margin-bottom: 15px
}

@media (min-width:768px) {
    .navbar-text {
        float: left;
        margin-right: 15px;
        margin-left: 15px
    }
}

@media (min-width:768px) {
    .navbar-left {
        float: left !important
    }
    .navbar-right {
        float: right !important;
        margin-right: -15px
    }
    .navbar-right~.navbar-right {
        margin-right: 0
    }
}

.navbar-default {
    background-color: #f8f8f8;
    border-color: #e7e7e7
}

.navbar-default .navbar-brand {
    color: #777
}

.navbar-default .navbar-brand:focus,
.navbar-default .navbar-brand:hover {
    color: #5e5e5e;
    background-color: transparent
}

.navbar-default .navbar-text {
    color: #777
}

.navbar-default .navbar-nav>li>a {
    color: #777
}

.navbar-default .navbar-nav>li>a:focus,
.navbar-default .navbar-nav>li>a:hover {
    color: #333;
    background-color: transparent
}

.navbar-default .navbar-nav>.active>a,
.navbar-default .navbar-nav>.active>a:focus,
.navbar-default .navbar-nav>.active>a:hover {
    color: #555;
    background-color: #e7e7e7
}

.navbar-default .navbar-nav>.disabled>a,
.navbar-default .navbar-nav>.disabled>a:focus,
.navbar-default .navbar-nav>.disabled>a:hover {
    color: #ccc;
    background-color: transparent
}

.navbar-default .navbar-toggle {
    border-color: #ddd
}

.navbar-default .navbar-toggle:focus,
.navbar-default .navbar-toggle:hover {
    background-color: #ddd
}

.navbar-default .navbar-toggle .icon-bar {
    background-color: #888
}

.navbar-default .navbar-collapse,
.navbar-default .navbar-form {
    border-color: #e7e7e7
}

.navbar-default .navbar-nav>.open>a,
.navbar-default .navbar-nav>.open>a:focus,
.navbar-default .navbar-nav>.open>a:hover {
    color: #555;
    background-color: #e7e7e7
}

@media (max-width:767px) {
    .navbar-default .navbar-nav .open .dropdown-menu>li>a {
        color: #777
    }
    .navbar-default .navbar-nav .open .dropdown-menu>li>a:focus,
    .navbar-default .navbar-nav .open .dropdown-menu>li>a:hover {
        color: #333;
        background-color: transparent
    }
    .navbar-default .navbar-nav .open .dropdown-menu>.active>a,
    .navbar-default .navbar-nav .open .dropdown-menu>.active>a:focus,
    .navbar-default .navbar-nav .open .dropdown-menu>.active>a:hover {
        color: #555;
        background-color: #e7e7e7
    }
    .navbar-default .navbar-nav .open .dropdown-menu>.disabled>a,
    .navbar-default .navbar-nav .open .dropdown-menu>.disabled>a:focus,
    .navbar-default .navbar-nav .open .dropdown-menu>.disabled>a:hover {
        color: #ccc;
        background-color: transparent
    }
}

.navbar-default .navbar-link {
    color: #777
}

.navbar-default .navbar-link:hover {
    color: #333
}

.navbar-default .btn-link {
    color: #777
}

.navbar-default .btn-link:focus,
.navbar-default .btn-link:hover {
    color: #333
}

.navbar-default .btn-link[disabled]:focus,
.navbar-default .btn-link[disabled]:hover,
fieldset[disabled] .navbar-default .btn-link:focus,
fieldset[disabled] .navbar-default .btn-link:hover {
    color: #ccc
}

.navbar-inverse {
    background-color: #222;
    border-color: #080808
}

.navbar-inverse .navbar-brand {
    color: #9d9d9d
}

.navbar-inverse .navbar-brand:focus,
.navbar-inverse .navbar-brand:hover {
    color: #fff;
    background-color: transparent
}

.navbar-inverse .navbar-text {
    color: #9d9d9d
}

.navbar-inverse .navbar-nav>li>a {
    color: #9d9d9d
}

.navbar-inverse .navbar-nav>li>a:focus,
.navbar-inverse .navbar-nav>li>a:hover {
    color: #fff;
    background-color: transparent
}

.navbar-inverse .navbar-nav>.active>a,
.navbar-inverse .navbar-nav>.active>a:focus,
.navbar-inverse .navbar-nav>.active>a:hover {
    color: #fff;
    background-color: #080808
}

.navbar-inverse .navbar-nav>.disabled>a,
.navbar-inverse .navbar-nav>.disabled>a:focus,
.navbar-inverse .navbar-nav>.disabled>a:hover {
    color: #444;
    background-color: transparent
}

.navbar-inverse .navbar-toggle {
    border-color: #333
}

.navbar-inverse .navbar-toggle:focus,
.navbar-inverse .navbar-toggle:hover {
    background-color: #333
}

.navbar-inverse .navbar-toggle .icon-bar {
    background-color: #fff
}

.navbar-inverse .navbar-collapse,
.navbar-inverse .navbar-form {
    border-color: #101010
}

.navbar-inverse .navbar-nav>.open>a,
.navbar-inverse .navbar-nav>.open>a:focus,
.navbar-inverse .navbar-nav>.open>a:hover {
    color: #fff;
    background-color: #080808
}

@media (max-width:767px) {
    .navbar-inverse .navbar-nav .open .dropdown-menu>.dropdown-header {
        border-color: #080808
    }
    .navbar-inverse .navbar-nav .open .dropdown-menu .divider {
        background-color: #080808
    }
    .navbar-inverse .navbar-nav .open .dropdown-menu>li>a {
        color: #9d9d9d
    }
    .navbar-inverse .navbar-nav .open .dropdown-menu>li>a:focus,
    .navbar-inverse .navbar-nav .open .dropdown-menu>li>a:hover {
        color: #fff;
        background-color: transparent
    }
    .navbar-inverse .navbar-nav .open .dropdown-menu>.active>a,
    .navbar-inverse .navbar-nav .open .dropdown-menu>.active>a:focus,
    .navbar-inverse .navbar-nav .open .dropdown-menu>.active>a:hover {
        color: #fff;
        background-color: #080808
    }
    .navbar-inverse .navbar-nav .open .dropdown-menu>.disabled>a,
    .navbar-inverse .navbar-nav .open .dropdown-menu>.disabled>a:focus,
    .navbar-inverse .navbar-nav .open .dropdown-menu>.disabled>a:hover {
        color: #444;
        background-color: transparent
    }
}

.navbar-inverse .navbar-link {
    color: #9d9d9d
}

.navbar-inverse .navbar-link:hover {
    color: #fff
}

.navbar-inverse .btn-link {
    color: #9d9d9d
}

.navbar-inverse .btn-link:focus,
.navbar-inverse .btn-link:hover {
    color: #fff
}

.navbar-inverse .btn-link[disabled]:focus,
.navbar-inverse .btn-link[disabled]:hover,
fieldset[disabled] .navbar-inverse .btn-link:focus,
fieldset[disabled] .navbar-inverse .btn-link:hover {
    color: #444
}

.breadcrumb {
    padding: 8px 15px;
    margin-bottom: 20px;
    list-style: none;
    background-color: #f5f5f5;
    border-radius: 4px
}

.breadcrumb>li {
    display: inline-block
}

.breadcrumb>li+li:before {
    padding: 0 5px;
    color: #ccc;
    content: "/\00a0"
}

.breadcrumb>.active {
    color: #777
}

.pagination {
    display: inline-block;
    padding-left: 0;
    margin: 20px 0;
    border-radius: 4px
}

.pagination>li {
    display: inline
}

.pagination>li>a,
.pagination>li>span {
    position: relative;
    float: left;
    padding: 6px 12px;
    margin-left: -1px;
    line-height: 1.42857143;
    color: #337ab7;
    text-decoration: none;
    background-color: #fff;
    border: 1px solid #ddd
}

.pagination>li:first-child>a,
.pagination>li:first-child>span {
    margin-left: 0;
    border-top-left-radius: 4px;
    border-bottom-left-radius: 4px
}

.pagination>li:last-child>a,
.pagination>li:last-child>span {
    border-top-right-radius: 4px;
    border-bottom-right-radius: 4px
}

.pagination>li>a:focus,
.pagination>li>a:hover,
.pagination>li>span:focus,
.pagination>li>span:hover {
    z-index: 2;
    color: #23527c;
    background-color: #eee;
    border-color: #ddd
}

.pagination>.active>a,
.pagination>.active>a:focus,
.pagination>.active>a:hover,
.pagination>.active>span,
.pagination>.active>span:focus,
.pagination>.active>span:hover {
    z-index: 3;
    color: #fff;
    cursor: default;
    background-color: #337ab7;
    border-color: #337ab7
}

.pagination>.disabled>a,
.pagination>.disabled>a:focus,
.pagination>.disabled>a:hover,
.pagination>.disabled>span,
.pagination>.disabled>span:focus,
.pagination>.disabled>span:hover {
    color: #777;
    cursor: not-allowed;
    background-color: #fff;
    border-color: #ddd
}

.pagination-lg>li>a,
.pagination-lg>li>span {
    padding: 10px 16px;
    font-size: 18px;
    line-height: 1.3333333
}

.pagination-lg>li:first-child>a,
.pagination-lg>li:first-child>span {
    border-top-left-radius: 6px;
    border-bottom-left-radius: 6px
}

.pagination-lg>li:last-child>a,
.pagination-lg>li:last-child>span {
    border-top-right-radius: 6px;
    border-bottom-right-radius: 6px
}

.pagination-sm>li>a,
.pagination-sm>li>span {
    padding: 5px 10px;
    font-size: 12px;
    line-height: 1.5
}

.pagination-sm>li:first-child>a,
.pagination-sm>li:first-child>span {
    border-top-left-radius: 3px;
    border-bottom-left-radius: 3px
}

.pagination-sm>li:last-child>a,
.pagination-sm>li:last-child>span {
    border-top-right-radius: 3px;
    border-bottom-right-radius: 3px
}

.pager {
    padding-left: 0;
    margin: 20px 0;
    text-align: center;
    list-style: none
}

.pager li {
    display: inline
}

.pager li>a,
.pager li>span {
    display: inline-block;
    padding: 5px 14px;
    background-color: #fff;
    border: 1px solid #ddd;
    border-radius: 15px
}

.pager li>a:focus,
.pager li>a:hover {
    text-decoration: none;
    background-color: #eee
}

.pager .next>a,
.pager .next>span {
    float: right
}

.pager .previous>a,
.pager .previous>span {
    float: left
}

.pager .disabled>a,
.pager .disabled>a:focus,
.pager .disabled>a:hover,
.pager .disabled>span {
    color: #777;
    cursor: not-allowed;
    background-color: #fff
}

.label {
    display: inline;
    padding: .2em .6em .3em;
    font-size: 75%;
    font-weight: 700;
    line-height: 1;
    color: #fff;
    text-align: center;
    white-space: nowrap;
    vertical-align: baseline;
    border-radius: .25em
}

a.label:focus,
a.label:hover {
    color: #fff;
    text-decoration: none;
    cursor: pointer
}

.label:empty {
    display: none
}

.btn .label {
    position: relative;
    top: -1px
}

.label-default {
    background-color: #777
}

.label-default[href]:focus,
.label-default[href]:hover {
    background-color: #5e5e5e
}

.label-primary {
    background-color: #337ab7
}

.label-primary[href]:focus,
.label-primary[href]:hover {
    background-color: #286090
}

.label-success {
    background-color: #5cb85c
}

.label-success[href]:focus,
.label-success[href]:hover {
    background-color: #449d44
}

.label-info {
    background-color: #5bc0de
}

.label-info[href]:focus,
.label-info[href]:hover {
    background-color: #31b0d5
}

.label-warning {
    background-color: #f0ad4e
}

.label-warning[href]:focus,
.label-warning[href]:hover {
    background-color: #ec971f
}

.label-danger {
    background-color: #d9534f
}

.label-danger[href]:focus,
.label-danger[href]:hover {
    background-color: #c9302c
}

.badge {
    display: inline-block;
    min-width: 10px;
    padding: 3px 7px;
    font-size: 12px;
    font-weight: 700;
    line-height: 1;
    color: #fff;
    text-align: center;
    white-space: nowrap;
    vertical-align: middle;
    background-color: #777;
    border-radius: 10px
}

.badge:empty {
    display: none
}

.btn .badge {
    position: relative;
    top: -1px
}

.btn-group-xs>.btn .badge,
.btn-xs .badge {
    top: 0;
    padding: 1px 5px
}

a.badge:focus,
a.badge:hover {
    color: #fff;
    text-decoration: none;
    cursor: pointer
}

.list-group-item.active>.badge,
.nav-pills>.active>a>.badge {
    color: #337ab7;
    background-color: #fff
}

.list-group-item>.badge {
    float: right
}

.list-group-item>.badge+.badge {
    margin-right: 5px
}

.nav-pills>li>a>.badge {
    margin-left: 3px
}

.jumbotron {
    padding-top: 30px;
    padding-bottom: 30px;
    margin-bottom: 30px;
    color: inherit;
    background-color: #eee
}

.jumbotron .h1,
.jumbotron h1 {
    color: inherit
}

.jumbotron p {
    margin-bottom: 15px;
    font-size: 21px;
    font-weight: 200
}

.jumbotron>hr {
    border-top-color: #d5d5d5
}

.container .jumbotron,
.container-fluid .jumbotron {
    padding-right: 15px;
    padding-left: 15px;
    border-radius: 6px
}

.jumbotron .container {
    max-width: 100%
}

@media screen and (min-width:768px) {
    .jumbotron {
        padding-top: 48px;
        padding-bottom: 48px
    }
    .container .jumbotron,
    .container-fluid .jumbotron {
        padding-right: 60px;
        padding-left: 60px
    }
    .jumbotron .h1,
    .jumbotron h1 {
        font-size: 63px
    }
}

.thumbnail {
    display: block;
    padding: 4px;
    margin-bottom: 20px;
    line-height: 1.42857143;
    background-color: #fff;
    border: 1px solid #ddd;
    border-radius: 4px;
    -webkit-transition: border .2s ease-in-out;
    -o-transition: border .2s ease-in-out;
    transition: border .2s ease-in-out
}

.thumbnail a>img,
.thumbnail>img {
    margin-right: auto;
    margin-left: auto
}

a.thumbnail.active,
a.thumbnail:focus,
a.thumbnail:hover {
    border-color: #337ab7
}

.thumbnail .caption {
    padding: 9px;
    color: #333
}

.alert {
    padding: 15px;
    margin-bottom: 20px;
    border: 1px solid transparent;
    border-radius: 4px
}

.alert h4 {
    margin-top: 0;
    color: inherit
}

.alert .alert-link {
    font-weight: 700
}

.alert>p,
.alert>ul {
    margin-bottom: 0
}

.alert>p+p {
    margin-top: 5px
}

.alert-dismissable,
.alert-dismissible {
    padding-right: 35px
}

.alert-dismissable .close,
.alert-dismissible .close {
    position: relative;
    top: -2px;
    right: -21px;
    color: inherit
}

.alert-success {
    color: #3c763d;
    background-color: #dff0d8;
    border-color: #d6e9c6
}

.alert-success hr {
    border-top-color: #c9e2b3
}

.alert-success .alert-link {
    color: #2b542c
}

.alert-info {
    color: #31708f;
    background-color: #d9edf7;
    border-color: #bce8f1
}

.alert-info hr {
    border-top-color: #a6e1ec
}

.alert-info .alert-link {
    color: #245269
}

.alert-warning {
    color: #8a6d3b;
    background-color: #fcf8e3;
    border-color: #faebcc
}

.alert-warning hr {
    border-top-color: #f7e1b5
}

.alert-warning .alert-link {
    color: #66512c
}

.alert-danger {
    color: #a94442;
    background-color: #f2dede;
    border-color: #ebccd1
}

.alert-danger hr {
    border-top-color: #e4b9c0
}

.alert-danger .alert-link {
    color: #843534
}

@-webkit-keyframes progress-bar-stripes {
    from {
        background-position: 40px 0
    }
    to {
        background-position: 0 0
    }
}

@-o-keyframes progress-bar-stripes {
    from {
        background-position: 40px 0
    }
    to {
        background-position: 0 0
    }
}

@keyframes progress-bar-stripes {
    from {
        background-position: 40px 0
    }
    to {
        background-position: 0 0
    }
}

.progress {
    height: 20px;
    margin-bottom: 20px;
    overflow: hidden;
    background-color: #f5f5f5;
    border-radius: 4px;
    -webkit-box-shadow: inset 0 1px 2px rgba(0, 0, 0, .1);
    box-shadow: inset 0 1px 2px rgba(0, 0, 0, .1)
}

.progress-bar {
    float: left;
    width: 0;
    height: 100%;
    font-size: 12px;
    line-height: 20px;
    color: #fff;
    text-align: center;
    background-color: #337ab7;
    -webkit-box-shadow: inset 0 -1px 0 rgba(0, 0, 0, .15);
    box-shadow: inset 0 -1px 0 rgba(0, 0, 0, .15);
    -webkit-transition: width .6s ease;
    -o-transition: width .6s ease;
    transition: width .6s ease
}

.progress-bar-striped,
.progress-striped .progress-bar {
    background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, .15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .15) 50%, rgba(255, 255, 255, .15) 75%, transparent 75%, transparent);
    background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, .15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .15) 50%, rgba(255, 255, 255, .15) 75%, transparent 75%, transparent);
    background-image: linear-gradient(45deg, rgba(255, 255, 255, .15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .15) 50%, rgba(255, 255, 255, .15) 75%, transparent 75%, transparent);
    -webkit-background-size: 40px 40px;
    background-size: 40px 40px
}

.progress-bar.active,
.progress.active .progress-bar {
    -webkit-animation: progress-bar-stripes 2s linear infinite;
    -o-animation: progress-bar-stripes 2s linear infinite;
    animation: progress-bar-stripes 2s linear infinite
}

.progress-bar-success {
    background-color: #5cb85c
}

.progress-striped .progress-bar-success {
    background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, .15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .15) 50%, rgba(255, 255, 255, .15) 75%, transparent 75%, transparent);
    background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, .15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .15) 50%, rgba(255, 255, 255, .15) 75%, transparent 75%, transparent);
    background-image: linear-gradient(45deg, rgba(255, 255, 255, .15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .15) 50%, rgba(255, 255, 255, .15) 75%, transparent 75%, transparent)
}

.progress-bar-info {
    background-color: #5bc0de
}

.progress-striped .progress-bar-info {
    background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, .15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .15) 50%, rgba(255, 255, 255, .15) 75%, transparent 75%, transparent);
    background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, .15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .15) 50%, rgba(255, 255, 255, .15) 75%, transparent 75%, transparent);
    background-image: linear-gradient(45deg, rgba(255, 255, 255, .15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .15) 50%, rgba(255, 255, 255, .15) 75%, transparent 75%, transparent)
}

.progress-bar-warning {
    background-color: #f0ad4e
}

.progress-striped .progress-bar-warning {
    background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, .15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .15) 50%, rgba(255, 255, 255, .15) 75%, transparent 75%, transparent);
    background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, .15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .15) 50%, rgba(255, 255, 255, .15) 75%, transparent 75%, transparent);
    background-image: linear-gradient(45deg, rgba(255, 255, 255, .15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .15) 50%, rgba(255, 255, 255, .15) 75%, transparent 75%, transparent)
}

.progress-bar-danger {
    background-color: #d9534f
}

.progress-striped .progress-bar-danger {
    background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, .15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .15) 50%, rgba(255, 255, 255, .15) 75%, transparent 75%, transparent);
    background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, .15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .15) 50%, rgba(255, 255, 255, .15) 75%, transparent 75%, transparent);
    background-image: linear-gradient(45deg, rgba(255, 255, 255, .15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .15) 50%, rgba(255, 255, 255, .15) 75%, transparent 75%, transparent)
}

.media {
    margin-top: 15px
}

.media:first-child {
    margin-top: 0
}

.media,
.media-body {
    overflow: hidden;
    zoom: 1
}

.media-body {
    width: 10000px
}

.media-object {
    display: block
}

.media-object.img-thumbnail {
    max-width: none
}

.media-right,
.media>.pull-right {
    padding-left: 10px
}

.media-left,
.media>.pull-left {
    padding-right: 10px
}

.media-body,
.media-left,
.media-right {
    display: table-cell;
    vertical-align: top
}

.media-middle {
    vertical-align: middle
}

.media-bottom {
    vertical-align: bottom
}

.media-heading {
    margin-top: 0;
    margin-bottom: 5px
}

.media-list {
    padding-left: 0;
    list-style: none
}

.list-group {
    padding-left: 0;
    margin-bottom: 20px
}

.list-group-item {
    position: relative;
    display: block;
    padding: 10px 15px;
    margin-bottom: -1px;
    background-color: #fff;
    border: 1px solid #ddd
}

.list-group-item:first-child {
    border-top-left-radius: 4px;
    border-top-right-radius: 4px
}

.list-group-item:last-child {
    margin-bottom: 0;
    border-bottom-right-radius: 4px;
    border-bottom-left-radius: 4px
}

a.list-group-item,
button.list-group-item {
    color: #555
}

a.list-group-item .list-group-item-heading,
button.list-group-item .list-group-item-heading {
    color: #333
}

a.list-group-item:focus,
a.list-group-item:hover,
button.list-group-item:focus,
button.list-group-item:hover {
    color: #555;
    text-decoration: none;
    background-color: #f5f5f5
}

button.list-group-item {
    width: 100%;
    text-align: left
}

.list-group-item.disabled,
.list-group-item.disabled:focus,
.list-group-item.disabled:hover {
    color: #777;
    cursor: not-allowed;
    background-color: #eee
}

.list-group-item.disabled .list-group-item-heading,
.list-group-item.disabled:focus .list-group-item-heading,
.list-group-item.disabled:hover .list-group-item-heading {
    color: inherit
}

.list-group-item.disabled .list-group-item-text,
.list-group-item.disabled:focus .list-group-item-text,
.list-group-item.disabled:hover .list-group-item-text {
    color: #777
}

.list-group-item.active,
.list-group-item.active:focus,
.list-group-item.active:hover {
    z-index: 2;
    color: #fff;
    background-color: #337ab7;
    border-color: #337ab7
}

.list-group-item.active .list-group-item-heading,
.list-group-item.active .list-group-item-heading>.small,
.list-group-item.active .list-group-item-heading>small,
.list-group-item.active:focus .list-group-item-heading,
.list-group-item.active:focus .list-group-item-heading>.small,
.list-group-item.active:focus .list-group-item-heading>small,
.list-group-item.active:hover .list-group-item-heading,
.list-group-item.active:hover .list-group-item-heading>.small,
.list-group-item.active:hover .list-group-item-heading>small {
    color: inherit
}

.list-group-item.active .list-group-item-text,
.list-group-item.active:focus .list-group-item-text,
.list-group-item.active:hover .list-group-item-text {
    color: #c7ddef
}

.list-group-item-success {
    color: #3c763d;
    background-color: #dff0d8
}

a.list-group-item-success,
button.list-group-item-success {
    color: #3c763d
}

a.list-group-item-success .list-group-item-heading,
button.list-group-item-success .list-group-item-heading {
    color: inherit
}

a.list-group-item-success:focus,
a.list-group-item-success:hover,
button.list-group-item-success:focus,
button.list-group-item-success:hover {
    color: #3c763d;
    background-color: #d0e9c6
}

a.list-group-item-success.active,
a.list-group-item-success.active:focus,
a.list-group-item-success.active:hover,
button.list-group-item-success.active,
button.list-group-item-success.active:focus,
button.list-group-item-success.active:hover {
    color: #fff;
    background-color: #3c763d;
    border-color: #3c763d
}

.list-group-item-info {
    color: #31708f;
    background-color: #d9edf7
}

a.list-group-item-info,
button.list-group-item-info {
    color: #31708f
}

a.list-group-item-info .list-group-item-heading,
button.list-group-item-info .list-group-item-heading {
    color: inherit
}

a.list-group-item-info:focus,
a.list-group-item-info:hover,
button.list-group-item-info:focus,
button.list-group-item-info:hover {
    color: #31708f;
    background-color: #c4e3f3
}

a.list-group-item-info.active,
a.list-group-item-info.active:focus,
a.list-group-item-info.active:hover,
button.list-group-item-info.active,
button.list-group-item-info.active:focus,
button.list-group-item-info.active:hover {
    color: #fff;
    background-color: #31708f;
    border-color: #31708f
}

.list-group-item-warning {
    color: #8a6d3b;
    background-color: #fcf8e3
}

a.list-group-item-warning,
button.list-group-item-warning {
    color: #8a6d3b
}

a.list-group-item-warning .list-group-item-heading,
button.list-group-item-warning .list-group-item-heading {
    color: inherit
}

a.list-group-item-warning:focus,
a.list-group-item-warning:hover,
button.list-group-item-warning:focus,
button.list-group-item-warning:hover {
    color: #8a6d3b;
    background-color: #faf2cc
}

a.list-group-item-warning.active,
a.list-group-item-warning.active:focus,
a.list-group-item-warning.active:hover,
button.list-group-item-warning.active,
button.list-group-item-warning.active:focus,
button.list-group-item-warning.active:hover {
    color: #fff;
    background-color: #8a6d3b;
    border-color: #8a6d3b
}

.list-group-item-danger {
    color: #a94442;
    background-color: #f2dede
}

a.list-group-item-danger,
button.list-group-item-danger {
    color: #a94442
}

a.list-group-item-danger .list-group-item-heading,
button.list-group-item-danger .list-group-item-heading {
    color: inherit
}

a.list-group-item-danger:focus,
a.list-group-item-danger:hover,
button.list-group-item-danger:focus,
button.list-group-item-danger:hover {
    color: #a94442;
    background-color: #ebcccc
}

a.list-group-item-danger.active,
a.list-group-item-danger.active:focus,
a.list-group-item-danger.active:hover,
button.list-group-item-danger.active,
button.list-group-item-danger.active:focus,
button.list-group-item-danger.active:hover {
    color: #fff;
    background-color: #a94442;
    border-color: #a94442
}

.list-group-item-heading {
    margin-top: 0;
    margin-bottom: 5px
}

.list-group-item-text {
    margin-bottom: 0;
    line-height: 1.3
}

.panel {
    margin-bottom: 20px;
    background-color: #fff;
    border: 1px solid transparent;
    border-radius: 4px;
    -webkit-box-shadow: 0 1px 1px rgba(0, 0, 0, .05);
    box-shadow: 0 1px 1px rgba(0, 0, 0, .05)
}

.panel-body {
    padding: 15px
}

.panel-heading {
    padding: 10px 15px;
    border-bottom: 1px solid transparent;
    border-top-left-radius: 3px;
    border-top-right-radius: 3px
}

.panel-heading>.dropdown .dropdown-toggle {
    color: inherit
}

.panel-title {
    margin-top: 0;
    margin-bottom: 0;
    font-size: 16px;
    color: inherit
}

.panel-title>.small,
.panel-title>.small>a,
.panel-title>a,
.panel-title>small,
.panel-title>small>a {
    color: inherit
}

.panel-footer {
    padding: 10px 15px;
    background-color: #f5f5f5;
    border-top: 1px solid #ddd;
    border-bottom-right-radius: 3px;
    border-bottom-left-radius: 3px
}

.panel>.list-group,
.panel>.panel-collapse>.list-group {
    margin-bottom: 0
}

.panel>.list-group .list-group-item,
.panel>.panel-collapse>.list-group .list-group-item {
    border-width: 1px 0;
    border-radius: 0
}

.panel>.list-group:first-child .list-group-item:first-child,
.panel>.panel-collapse>.list-group:first-child .list-group-item:first-child {
    border-top: 0;
    border-top-left-radius: 3px;
    border-top-right-radius: 3px
}

.panel>.list-group:last-child .list-group-item:last-child,
.panel>.panel-collapse>.list-group:last-child .list-group-item:last-child {
    border-bottom: 0;
    border-bottom-right-radius: 3px;
    border-bottom-left-radius: 3px
}

.panel>.panel-heading+.panel-collapse>.list-group .list-group-item:first-child {
    border-top-left-radius: 0;
    border-top-right-radius: 0
}

.panel-heading+.list-group .list-group-item:first-child {
    border-top-width: 0
}

.list-group+.panel-footer {
    border-top-width: 0
}

.panel>.panel-collapse>.table,
.panel>.table,
.panel>.table-responsive>.table {
    margin-bottom: 0
}

.panel>.panel-collapse>.table caption,
.panel>.table caption,
.panel>.table-responsive>.table caption {
    padding-right: 15px;
    padding-left: 15px
}

.panel>.table-responsive:first-child>.table:first-child,
.panel>.table:first-child {
    border-top-left-radius: 3px;
    border-top-right-radius: 3px
}

.panel>.table-responsive:first-child>.table:first-child>tbody:first-child>tr:first-child,
.panel>.table-responsive:first-child>.table:first-child>thead:first-child>tr:first-child,
.panel>.table:first-child>tbody:first-child>tr:first-child,
.panel>.table:first-child>thead:first-child>tr:first-child {
    border-top-left-radius: 3px;
    border-top-right-radius: 3px
}

.panel>.table-responsive:first-child>.table:first-child>tbody:first-child>tr:first-child td:first-child,
.panel>.table-responsive:first-child>.table:first-child>tbody:first-child>tr:first-child th:first-child,
.panel>.table-responsive:first-child>.table:first-child>thead:first-child>tr:first-child td:first-child,
.panel>.table-responsive:first-child>.table:first-child>thead:first-child>tr:first-child th:first-child,
.panel>.table:first-child>tbody:first-child>tr:first-child td:first-child,
.panel>.table:first-child>tbody:first-child>tr:first-child th:first-child,
.panel>.table:first-child>thead:first-child>tr:first-child td:first-child,
.panel>.table:first-child>thead:first-child>tr:first-child th:first-child {
    border-top-left-radius: 3px
}

.panel>.table-responsive:first-child>.table:first-child>tbody:first-child>tr:first-child td:last-child,
.panel>.table-responsive:first-child>.table:first-child>tbody:first-child>tr:first-child th:last-child,
.panel>.table-responsive:first-child>.table:first-child>thead:first-child>tr:first-child td:last-child,
.panel>.table-responsive:first-child>.table:first-child>thead:first-child>tr:first-child th:last-child,
.panel>.table:first-child>tbody:first-child>tr:first-child td:last-child,
.panel>.table:first-child>tbody:first-child>tr:first-child th:last-child,
.panel>.table:first-child>thead:first-child>tr:first-child td:last-child,
.panel>.table:first-child>thead:first-child>tr:first-child th:last-child {
    border-top-right-radius: 3px
}

.panel>.table-responsive:last-child>.table:last-child,
.panel>.table:last-child {
    border-bottom-right-radius: 3px;
    border-bottom-left-radius: 3px
}

.panel>.table-responsive:last-child>.table:last-child>tbody:last-child>tr:last-child,
.panel>.table-responsive:last-child>.table:last-child>tfoot:last-child>tr:last-child,
.panel>.table:last-child>tbody:last-child>tr:last-child,
.panel>.table:last-child>tfoot:last-child>tr:last-child {
    border-bottom-right-radius: 3px;
    border-bottom-left-radius: 3px
}

.panel>.table-responsive:last-child>.table:last-child>tbody:last-child>tr:last-child td:first-child,
.panel>.table-responsive:last-child>.table:last-child>tbody:last-child>tr:last-child th:first-child,
.panel>.table-responsive:last-child>.table:last-child>tfoot:last-child>tr:last-child td:first-child,
.panel>.table-responsive:last-child>.table:last-child>tfoot:last-child>tr:last-child th:first-child,
.panel>.table:last-child>tbody:last-child>tr:last-child td:first-child,
.panel>.table:last-child>tbody:last-child>tr:last-child th:first-child,
.panel>.table:last-child>tfoot:last-child>tr:last-child td:first-child,
.panel>.table:last-child>tfoot:last-child>tr:last-child th:first-child {
    border-bottom-left-radius: 3px
}

.panel>.table-responsive:last-child>.table:last-child>tbody:last-child>tr:last-child td:last-child,
.panel>.table-responsive:last-child>.table:last-child>tbody:last-child>tr:last-child th:last-child,
.panel>.table-responsive:last-child>.table:last-child>tfoot:last-child>tr:last-child td:last-child,
.panel>.table-responsive:last-child>.table:last-child>tfoot:last-child>tr:last-child th:last-child,
.panel>.table:last-child>tbody:last-child>tr:last-child td:last-child,
.panel>.table:last-child>tbody:last-child>tr:last-child th:last-child,
.panel>.table:last-child>tfoot:last-child>tr:last-child td:last-child,
.panel>.table:last-child>tfoot:last-child>tr:last-child th:last-child {
    border-bottom-right-radius: 3px
}

.panel>.panel-body+.table,
.panel>.panel-body+.table-responsive,
.panel>.table+.panel-body,
.panel>.table-responsive+.panel-body {
    border-top: 1px solid #ddd
}

.panel>.table>tbody:first-child>tr:first-child td,
.panel>.table>tbody:first-child>tr:first-child th {
    border-top: 0
}

.panel>.table-bordered,
.panel>.table-responsive>.table-bordered {
    border: 0
}

.panel>.table-bordered>tbody>tr>td:first-child,
.panel>.table-bordered>tbody>tr>th:first-child,
.panel>.table-bordered>tfoot>tr>td:first-child,
.panel>.table-bordered>tfoot>tr>th:first-child,
.panel>.table-bordered>thead>tr>td:first-child,
.panel>.table-bordered>thead>tr>th:first-child,
.panel>.table-responsive>.table-bordered>tbody>tr>td:first-child,
.panel>.table-responsive>.table-bordered>tbody>tr>th:first-child,
.panel>.table-responsive>.table-bordered>tfoot>tr>td:first-child,
.panel>.table-responsive>.table-bordered>tfoot>tr>th:first-child,
.panel>.table-responsive>.table-bordered>thead>tr>td:first-child,
.panel>.table-responsive>.table-bordered>thead>tr>th:first-child {
    border-left: 0
}

.panel>.table-bordered>tbody>tr>td:last-child,
.panel>.table-bordered>tbody>tr>th:last-child,
.panel>.table-bordered>tfoot>tr>td:last-child,
.panel>.table-bordered>tfoot>tr>th:last-child,
.panel>.table-bordered>thead>tr>td:last-child,
.panel>.table-bordered>thead>tr>th:last-child,
.panel>.table-responsive>.table-bordered>tbody>tr>td:last-child,
.panel>.table-responsive>.table-bordered>tbody>tr>th:last-child,
.panel>.table-responsive>.table-bordered>tfoot>tr>td:last-child,
.panel>.table-responsive>.table-bordered>tfoot>tr>th:last-child,
.panel>.table-responsive>.table-bordered>thead>tr>td:last-child,
.panel>.table-responsive>.table-bordered>thead>tr>th:last-child {
    border-right: 0
}

.panel>.table-bordered>tbody>tr:first-child>td,
.panel>.table-bordered>tbody>tr:first-child>th,
.panel>.table-bordered>thead>tr:first-child>td,
.panel>.table-bordered>thead>tr:first-child>th,
.panel>.table-responsive>.table-bordered>tbody>tr:first-child>td,
.panel>.table-responsive>.table-bordered>tbody>tr:first-child>th,
.panel>.table-responsive>.table-bordered>thead>tr:first-child>td,
.panel>.table-responsive>.table-bordered>thead>tr:first-child>th {
    border-bottom: 0
}

.panel>.table-bordered>tbody>tr:last-child>td,
.panel>.table-bordered>tbody>tr:last-child>th,
.panel>.table-bordered>tfoot>tr:last-child>td,
.panel>.table-bordered>tfoot>tr:last-child>th,
.panel>.table-responsive>.table-bordered>tbody>tr:last-child>td,
.panel>.table-responsive>.table-bordered>tbody>tr:last-child>th,
.panel>.table-responsive>.table-bordered>tfoot>tr:last-child>td,
.panel>.table-responsive>.table-bordered>tfoot>tr:last-child>th {
    border-bottom: 0
}

.panel>.table-responsive {
    margin-bottom: 0;
    border: 0
}

.panel-group {
    margin-bottom: 20px
}

.panel-group .panel {
    margin-bottom: 0;
    border-radius: 4px
}

.panel-group .panel+.panel {
    margin-top: 5px
}

.panel-group .panel-heading {
    border-bottom: 0
}

.panel-group .panel-heading+.panel-collapse>.list-group,
.panel-group .panel-heading+.panel-collapse>.panel-body {
    border-top: 1px solid #ddd
}

.panel-group .panel-footer {
    border-top: 0
}

.panel-group .panel-footer+.panel-collapse .panel-body {
    border-bottom: 1px solid #ddd
}

.panel-default {
    border-color: #ddd
}

.panel-default>.panel-heading {
    color: #333;
    background-color: #f5f5f5;
    border-color: #ddd
}

.panel-default>.panel-heading+.panel-collapse>.panel-body {
    border-top-color: #ddd
}

.panel-default>.panel-heading .badge {
    color: #f5f5f5;
    background-color: #333
}

.panel-default>.panel-footer+.panel-collapse>.panel-body {
    border-bottom-color: #ddd
}

.panel-primary {
    border-color: #337ab7
}

.panel-primary>.panel-heading {
    color: #fff;
    background-color: #337ab7;
    border-color: #337ab7
}

.panel-primary>.panel-heading+.panel-collapse>.panel-body {
    border-top-color: #337ab7
}

.panel-primary>.panel-heading .badge {
    color: #337ab7;
    background-color: #fff
}

.panel-primary>.panel-footer+.panel-collapse>.panel-body {
    border-bottom-color: #337ab7
}

.panel-success {
    border-color: #d6e9c6
}

.panel-success>.panel-heading {
    color: #3c763d;
    background-color: #dff0d8;
    border-color: #d6e9c6
}

.panel-success>.panel-heading+.panel-collapse>.panel-body {
    border-top-color: #d6e9c6
}

.panel-success>.panel-heading .badge {
    color: #dff0d8;
    background-color: #3c763d
}

.panel-success>.panel-footer+.panel-collapse>.panel-body {
    border-bottom-color: #d6e9c6
}

.panel-info {
    border-color: #bce8f1
}

.panel-info>.panel-heading {
    color: #31708f;
    background-color: #d9edf7;
    border-color: #bce8f1
}

.panel-info>.panel-heading+.panel-collapse>.panel-body {
    border-top-color: #bce8f1
}

.panel-info>.panel-heading .badge {
    color: #d9edf7;
    background-color: #31708f
}

.panel-info>.panel-footer+.panel-collapse>.panel-body {
    border-bottom-color: #bce8f1
}

.panel-warning {
    border-color: #faebcc
}

.panel-warning>.panel-heading {
    color: #8a6d3b;
    background-color: #fcf8e3;
    border-color: #faebcc
}

.panel-warning>.panel-heading+.panel-collapse>.panel-body {
    border-top-color: #faebcc
}

.panel-warning>.panel-heading .badge {
    color: #fcf8e3;
    background-color: #8a6d3b
}

.panel-warning>.panel-footer+.panel-collapse>.panel-body {
    border-bottom-color: #faebcc
}

.panel-danger {
    border-color: #ebccd1
}

.panel-danger>.panel-heading {
    color: #a94442;
    background-color: #f2dede;
    border-color: #ebccd1
}

.panel-danger>.panel-heading+.panel-collapse>.panel-body {
    border-top-color: #ebccd1
}

.panel-danger>.panel-heading .badge {
    color: #f2dede;
    background-color: #a94442
}

.panel-danger>.panel-footer+.panel-collapse>.panel-body {
    border-bottom-color: #ebccd1
}

.embed-responsive {
    position: relative;
    display: block;
    height: 0;
    padding: 0;
    overflow: hidden
}

.embed-responsive .embed-responsive-item,
.embed-responsive embed,
.embed-responsive iframe,
.embed-responsive object,
.embed-responsive video {
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: 0
}

.embed-responsive-16by9 {
    padding-bottom: 56.25%
}

.embed-responsive-4by3 {
    padding-bottom: 75%
}

.well {
    min-height: 20px;
    padding: 19px;
    margin-bottom: 20px;
    background-color: #f5f5f5;
    border: 1px solid #e3e3e3;
    border-radius: 4px;
    -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, .05);
    box-shadow: inset 0 1px 1px rgba(0, 0, 0, .05)
}

.well blockquote {
    border-color: #ddd;
    border-color: rgba(0, 0, 0, .15)
}

.well-lg {
    padding: 24px;
    border-radius: 6px
}

.well-sm {
    padding: 9px;
    border-radius: 3px
}

.close {
    float: right;
    font-size: 21px;
    font-weight: 700;
    line-height: 1;
    color: #000;
    text-shadow: 0 1px 0 #fff;
    opacity: .2
}

.close:focus,
.close:hover {
    color: #000;
    text-decoration: none;
    cursor: pointer;
    opacity: .5
}

button.close {
    -webkit-appearance: none;
    padding: 0;
    cursor: pointer;
    background: 0 0;
    border: 0
}

.modal-open {
    overflow: hidden
}

.modal {
    position: fixed;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    z-index: 1050;
    display: none;
    overflow: hidden;
    -webkit-overflow-scrolling: touch;
    outline: 0
}

.modal.fade .modal-dialog {
    -webkit-transition: -webkit-transform .3s ease-out;
    -o-transition: -o-transform .3s ease-out;
    transition: transform .3s ease-out;
    -webkit-transform: translate(0, -25%);
    -ms-transform: translate(0, -25%);
    -o-transform: translate(0, -25%);
    transform: translate(0, -25%)
}

.modal.in .modal-dialog {
    -webkit-transform: translate(0, 0);
    -ms-transform: translate(0, 0);
    -o-transform: translate(0, 0);
    transform: translate(0, 0)
}

.modal-open .modal {
    overflow-x: hidden;
    overflow-y: auto
}

.modal-dialog {
    position: relative;
    width: auto;
    margin: 10px
}

.modal-content {
    position: relative;
    background-color: #fff;
    -webkit-background-clip: padding-box;
    background-clip: padding-box;
    border: 1px solid #999;
    border: 1px solid rgba(0, 0, 0, .2);
    border-radius: 6px;
    outline: 0;
    -webkit-box-shadow: 0 3px 9px rgba(0, 0, 0, .5);
    box-shadow: 0 3px 9px rgba(0, 0, 0, .5)
}

.modal-backdrop {
    position: fixed;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    z-index: 1040;
    background-color: #000
}

.modal-backdrop.fade {
    opacity: 0
}

.modal-backdrop.in {
    opacity: .5
}

.modal-header {
    padding: 15px;
    border-bottom: 1px solid #e5e5e5
}

.modal-header .close {
    margin-top: -2px
}

.modal-title {
    margin: 0;
    line-height: 1.42857143
}

.modal-body {
    position: relative;
    padding: 15px
}

.modal-footer {
    padding: 15px;
    text-align: right;
    border-top: 1px solid #e5e5e5
}

.modal-footer .btn+.btn {
    margin-bottom: 0;
    margin-left: 5px
}

.modal-footer .btn-group .btn+.btn {
    margin-left: -1px
}

.modal-footer .btn-block+.btn-block {
    margin-left: 0
}

.modal-scrollbar-measure {
    position: absolute;
    top: -9999px;
    width: 50px;
    height: 50px;
    overflow: scroll
}

@media (min-width:768px) {
    .modal-dialog {
        width: 600px;
        margin: 30px auto
    }
    .modal-content {
        -webkit-box-shadow: 0 5px 15px rgba(0, 0, 0, .5);
        box-shadow: 0 5px 15px rgba(0, 0, 0, .5)
    }
    .modal-sm {
        width: 300px
    }
}

@media (min-width:992px) {
    .modal-lg {
        width: 900px
    }
}

.tooltip {
    position: absolute;
    z-index: 1070;
    display: block;
    font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
    font-size: 12px;
    font-style: normal;
    font-weight: 400;
    line-height: 1.42857143;
    text-align: left;
    text-align: start;
    text-decoration: none;
    text-shadow: none;
    text-transform: none;
    letter-spacing: normal;
    word-break: normal;
    word-spacing: normal;
    word-wrap: normal;
    white-space: normal;
    opacity: 0;
    line-break: auto
}

.tooltip.in {
    opacity: .9
}

.tooltip.top {
    padding: 5px 0;
    margin-top: -3px
}

.tooltip.right {
    padding: 0 5px;
    margin-left: 3px
}

.tooltip.bottom {
    padding: 5px 0;
    margin-top: 3px
}

.tooltip.left {
    padding: 0 5px;
    margin-left: -3px
}

.tooltip-inner {
    max-width: 200px;
    padding: 3px 8px;
    color: #fff;
    text-align: center;
    background-color: #000;
    border-radius: 4px
}

.tooltip-arrow {
    position: absolute;
    width: 0;
    height: 0;
    border-color: transparent;
    border-style: solid
}

.tooltip.top .tooltip-arrow {
    bottom: 0;
    left: 50%;
    margin-left: -5px;
    border-width: 5px 5px 0;
    border-top-color: #000
}

.tooltip.top-left .tooltip-arrow {
    right: 5px;
    bottom: 0;
    margin-bottom: -5px;
    border-width: 5px 5px 0;
    border-top-color: #000
}

.tooltip.top-right .tooltip-arrow {
    bottom: 0;
    left: 5px;
    margin-bottom: -5px;
    border-width: 5px 5px 0;
    border-top-color: #000
}

.tooltip.right .tooltip-arrow {
    top: 50%;
    left: 0;
    margin-top: -5px;
    border-width: 5px 5px 5px 0;
    border-right-color: #000
}

.tooltip.left .tooltip-arrow {
    top: 50%;
    right: 0;
    margin-top: -5px;
    border-width: 5px 0 5px 5px;
    border-left-color: #000
}

.tooltip.bottom .tooltip-arrow {
    top: 0;
    left: 50%;
    margin-left: -5px;
    border-width: 0 5px 5px;
    border-bottom-color: #000
}

.tooltip.bottom-left .tooltip-arrow {
    top: 0;
    right: 5px;
    margin-top: -5px;
    border-width: 0 5px 5px;
    border-bottom-color: #000
}

.tooltip.bottom-right .tooltip-arrow {
    top: 0;
    left: 5px;
    margin-top: -5px;
    border-width: 0 5px 5px;
    border-bottom-color: #000
}

.popover {
    position: absolute;
    top: 0;
    left: 0;
    z-index: 1060;
    display: none;
    max-width: 276px;
    padding: 1px;
    font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
    font-size: 14px;
    font-style: normal;
    font-weight: 400;
    line-height: 1.42857143;
    text-align: left;
    text-align: start;
    text-decoration: none;
    text-shadow: none;
    text-transform: none;
    letter-spacing: normal;
    word-break: normal;
    word-spacing: normal;
    word-wrap: normal;
    white-space: normal;
    background-color: #fff;
    -webkit-background-clip: padding-box;
    background-clip: padding-box;
    border: 1px solid #ccc;
    border: 1px solid rgba(0, 0, 0, .2);
    border-radius: 6px;
    -webkit-box-shadow: 0 5px 10px rgba(0, 0, 0, .2);
    box-shadow: 0 5px 10px rgba(0, 0, 0, .2);
    line-break: auto
}

.popover.top {
    margin-top: -10px
}

.popover.right {
    margin-left: 10px
}

.popover.bottom {
    margin-top: 10px
}

.popover.left {
    margin-left: -10px
}

.popover-title {
    padding: 8px 14px;
    margin: 0;
    font-size: 14px;
    background-color: #f7f7f7;
    border-bottom: 1px solid #ebebeb;
    border-radius: 5px 5px 0 0
}

.popover-content {
    padding: 9px 14px
}

.popover>.arrow,
.popover>.arrow:after {
    position: absolute;
    display: block;
    width: 0;
    height: 0;
    border-color: transparent;
    border-style: solid
}

.popover>.arrow {
    border-width: 11px
}

.popover>.arrow:after {
    content: "";
    border-width: 10px
}

.popover.top>.arrow {
    bottom: -11px;
    left: 50%;
    margin-left: -11px;
    border-top-color: #999;
    border-top-color: rgba(0, 0, 0, .25);
    border-bottom-width: 0
}

.popover.top>.arrow:after {
    bottom: 1px;
    margin-left: -10px;
    content: " ";
    border-top-color: #fff;
    border-bottom-width: 0
}

.popover.right>.arrow {
    top: 50%;
    left: -11px;
    margin-top: -11px;
    border-right-color: #999;
    border-right-color: rgba(0, 0, 0, .25);
    border-left-width: 0
}

.popover.right>.arrow:after {
    bottom: -10px;
    left: 1px;
    content: " ";
    border-right-color: #fff;
    border-left-width: 0
}

.popover.bottom>.arrow {
    top: -11px;
    left: 50%;
    margin-left: -11px;
    border-top-width: 0;
    border-bottom-color: #999;
    border-bottom-color: rgba(0, 0, 0, .25)
}

.popover.bottom>.arrow:after {
    top: 1px;
    margin-left: -10px;
    content: " ";
    border-top-width: 0;
    border-bottom-color: #fff
}

.popover.left>.arrow {
    top: 50%;
    right: -11px;
    margin-top: -11px;
    border-right-width: 0;
    border-left-color: #999;
    border-left-color: rgba(0, 0, 0, .25)
}

.popover.left>.arrow:after {
    right: 1px;
    bottom: -10px;
    content: " ";
    border-right-width: 0;
    border-left-color: #fff
}

.carousel {
    position: relative
}

.carousel-inner {
    position: relative;
    width: 100%;
    overflow: hidden
}

.carousel-inner>.item {
    position: relative;
    display: none;
    -webkit-transition: .6s ease-in-out left;
    -o-transition: .6s ease-in-out left;
    transition: .6s ease-in-out left
}

.carousel-inner>.item>a>img,
.carousel-inner>.item>img {
    line-height: 1
}

@media all and (transform-3d),
(-webkit-transform-3d) {
    .carousel-inner>.item {
        -webkit-transition: -webkit-transform .6s ease-in-out;
        -o-transition: -o-transform .6s ease-in-out;
        transition: transform .6s ease-in-out;
        -webkit-backface-visibility: hidden;
        backface-visibility: hidden;
        -webkit-perspective: 1000px;
        perspective: 1000px
    }
    .carousel-inner>.item.active.right,
    .carousel-inner>.item.next {
        left: 0;
        -webkit-transform: translate3d(100%, 0, 0);
        transform: translate3d(100%, 0, 0)
    }
    .carousel-inner>.item.active.left,
    .carousel-inner>.item.prev {
        left: 0;
        -webkit-transform: translate3d(-100%, 0, 0);
        transform: translate3d(-100%, 0, 0)
    }
    .carousel-inner>.item.active,
    .carousel-inner>.item.next.left,
    .carousel-inner>.item.prev.right {
        left: 0;
        -webkit-transform: translate3d(0, 0, 0);
        transform: translate3d(0, 0, 0)
    }
}

.carousel-inner>.active,
.carousel-inner>.next,
.carousel-inner>.prev {
    display: block
}

.carousel-inner>.active {
    left: 0
}

.carousel-inner>.next,
.carousel-inner>.prev {
    position: absolute;
    top: 0;
    width: 100%
}

.carousel-inner>.next {
    left: 100%
}

.carousel-inner>.prev {
    left: -100%
}

.carousel-inner>.next.left,
.carousel-inner>.prev.right {
    left: 0
}

.carousel-inner>.active.left {
    left: -100%
}

.carousel-inner>.active.right {
    left: 100%
}

.carousel-control {
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    width: 15%;
    font-size: 20px;
    color: #fff;
    text-align: center;
    text-shadow: 0 1px 2px rgba(0, 0, 0, .6);
    background-color: rgba(0, 0, 0, 0);
    opacity: .5
}

.carousel-control.left {
    background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, .5) 0, rgba(0, 0, 0, .0001) 100%);
    background-image: -o-linear-gradient(left, rgba(0, 0, 0, .5) 0, rgba(0, 0, 0, .0001) 100%);
    background-image: -webkit-gradient(linear, left top, right top, from(rgba(0, 0, 0, .5)), to(rgba(0, 0, 0, .0001)));
    background-image: linear-gradient(to right, rgba(0, 0, 0, .5) 0, rgba(0, 0, 0, .0001) 100%);
    background-repeat: repeat-x
}

.carousel-control.right {
    right: 0;
    left: auto;
    background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, .0001) 0, rgba(0, 0, 0, .5) 100%);
    background-image: -o-linear-gradient(left, rgba(0, 0, 0, .0001) 0, rgba(0, 0, 0, .5) 100%);
    background-image: -webkit-gradient(linear, left top, right top, from(rgba(0, 0, 0, .0001)), to(rgba(0, 0, 0, .5)));
    background-image: linear-gradient(to right, rgba(0, 0, 0, .0001) 0, rgba(0, 0, 0, .5) 100%);
    background-repeat: repeat-x
}

.carousel-control:focus,
.carousel-control:hover {
    color: #fff;
    text-decoration: none;
    outline: 0;
    opacity: .9
}

.carousel-control .glyphicon-chevron-left,
.carousel-control .glyphicon-chevron-right,
.carousel-control .icon-next,
.carousel-control .icon-prev {
    position: absolute;
    top: 50%;
    z-index: 5;
    display: inline-block;
    margin-top: -10px
}

.carousel-control .glyphicon-chevron-left,
.carousel-control .icon-prev {
    left: 50%;
    margin-left: -10px
}

.carousel-control .glyphicon-chevron-right,
.carousel-control .icon-next {
    right: 50%;
    margin-right: -10px
}

.carousel-control .icon-next,
.carousel-control .icon-prev {
    width: 20px;
    height: 20px;
    font-family: serif;
    line-height: 1
}

.carousel-control .icon-prev:before {
    content: '\2039'
}

.carousel-control .icon-next:before {
    content: '\203a'
}

.carousel-indicators {
    position: absolute;
    bottom: 10px;
    left: 50%;
    z-index: 15;
    width: 60%;
    padding-left: 0;
    margin-left: -30%;
    text-align: center;
    list-style: none
}

.carousel-indicators li {
    display: inline-block;
    width: 10px;
    height: 10px;
    margin: 1px;
    text-indent: -999px;
    cursor: pointer;
    background-color: rgba(0, 0, 0, 0);
    border: 1px solid #fff;
    border-radius: 10px
}

.carousel-indicators .active {
    width: 12px;
    height: 12px;
    margin: 0;
    background-color: #fff
}

.carousel-caption {
    position: absolute;
    right: 15%;
    bottom: 20px;
    left: 15%;
    z-index: 10;
    padding-top: 20px;
    padding-bottom: 20px;
    color: #fff;
    text-align: center;
    text-shadow: 0 1px 2px rgba(0, 0, 0, .6)
}

.carousel-caption .btn {
    text-shadow: none
}

@media screen and (min-width:768px) {
    .carousel-control .glyphicon-chevron-left,
    .carousel-control .glyphicon-chevron-right,
    .carousel-control .icon-next,
    .carousel-control .icon-prev {
        width: 30px;
        height: 30px;
        margin-top: -10px;
        font-size: 30px
    }
    .carousel-control .glyphicon-chevron-left,
    .carousel-control .icon-prev {
        margin-left: -10px
    }
    .carousel-control .glyphicon-chevron-right,
    .carousel-control .icon-next {
        margin-right: -10px
    }
    .carousel-caption {
        right: 20%;
        left: 20%;
        padding-bottom: 30px
    }
    .carousel-indicators {
        bottom: 20px
    }
}

.btn-group-vertical>.btn-group:after,
.btn-group-vertical>.btn-group:before,
.btn-toolbar:after,
.btn-toolbar:before,
.clearfix:after,
.clearfix:before,
.container-fluid:after,
.container-fluid:before,
.container:after,
.container:before,
.dl-horizontal dd:after,
.dl-horizontal dd:before,
.form-horizontal .form-group:after,
.form-horizontal .form-group:before,
.modal-footer:after,
.modal-footer:before,
.modal-header:after,
.modal-header:before,
.nav:after,
.nav:before,
.navbar-collapse:after,
.navbar-collapse:before,
.navbar-header:after,
.navbar-header:before,
.navbar:after,
.navbar:before,
.pager:after,
.pager:before,
.panel-body:after,
.panel-body:before,
.row:after,
.row:before {
    display: table;
    content: " "
}

.btn-group-vertical>.btn-group:after,
.btn-toolbar:after,
.clearfix:after,
.container-fluid:after,
.container:after,
.dl-horizontal dd:after,
.form-horizontal .form-group:after,
.modal-footer:after,
.modal-header:after,
.nav:after,
.navbar-collapse:after,
.navbar-header:after,
.navbar:after,
.pager:after,
.panel-body:after,
.row:after {
    clear: both
}

.center-block {
    display: block;
    margin-right: auto;
    margin-left: auto
}

.pull-right {
    float: right !important
}

.pull-left {
    float: left !important
}

.hide {
    display: none !important
}

.show {
    display: block !important
}

.invisible {
    visibility: hidden
}

.text-hide {
    font: 0/0 a;
    color: transparent;
    text-shadow: none;
    background-color: transparent;
    border: 0
}

.hidden {
    display: none !important
}

.affix {
    position: fixed
}

@-ms-viewport {
    width: device-width
}

.visible-lg,
.visible-md,
.visible-sm,
.visible-xs {
    display: none !important
}

.visible-lg-block,
.visible-lg-inline,
.visible-lg-inline-block,
.visible-md-block,
.visible-md-inline,
.visible-md-inline-block,
.visible-sm-block,
.visible-sm-inline,
.visible-sm-inline-block,
.visible-xs-block,
.visible-xs-inline,
.visible-xs-inline-block {
    display: none !important
}

@media (max-width:767px) {
    .visible-xs {
        display: block !important
    }
    table.visible-xs {
        display: table !important
    }
    tr.visible-xs {
        display: table-row !important
    }
    td.visible-xs,
    th.visible-xs {
        display: table-cell !important
    }
}

@media (max-width:767px) {
    .visible-xs-block {
        display: block !important
    }
}

@media (max-width:767px) {
    .visible-xs-inline {
        display: inline !important
    }
}

@media (max-width:767px) {
    .visible-xs-inline-block {
        display: inline-block !important
    }
}

@media (min-width:768px) and (max-width:991px) {
    .visible-sm {
        display: block !important
    }
    table.visible-sm {
        display: table !important
    }
    tr.visible-sm {
        display: table-row !important
    }
    td.visible-sm,
    th.visible-sm {
        display: table-cell !important
    }
}

@media (min-width:768px) and (max-width:991px) {
    .visible-sm-block {
        display: block !important
    }
}

@media (min-width:768px) and (max-width:991px) {
    .visible-sm-inline {
        display: inline !important
    }
}

@media (min-width:768px) and (max-width:991px) {
    .visible-sm-inline-block {
        display: inline-block !important
    }
}

@media (min-width:992px) and (max-width:1199px) {
    .visible-md {
        display: block !important
    }
    table.visible-md {
        display: table !important
    }
    tr.visible-md {
        display: table-row !important
    }
    td.visible-md,
    th.visible-md {
        display: table-cell !important
    }
}

@media (min-width:992px) and (max-width:1199px) {
    .visible-md-block {
        display: block !important
    }
}

@media (min-width:992px) and (max-width:1199px) {
    .visible-md-inline {
        display: inline !important
    }
}

@media (min-width:992px) and (max-width:1199px) {
    .visible-md-inline-block {
        display: inline-block !important
    }
}

@media (min-width:1200px) {
    .visible-lg {
        display: block !important
    }
    table.visible-lg {
        display: table !important
    }
    tr.visible-lg {
        display: table-row !important
    }
    td.visible-lg,
    th.visible-lg {
        display: table-cell !important
    }
}

@media (min-width:1200px) {
    .visible-lg-block {
        display: block !important
    }
}

@media (min-width:1200px) {
    .visible-lg-inline {
        display: inline !important
    }
}

@media (min-width:1200px) {
    .visible-lg-inline-block {
        display: inline-block !important
    }
}

@media (max-width:767px) {
    .hidden-xs {
        display: none !important
    }
}

@media (min-width:768px) and (max-width:991px) {
    .hidden-sm {
        display: none !important
    }
}

@media (min-width:992px) and (max-width:1199px) {
    .hidden-md {
        display: none !important
    }
}

@media (min-width:1200px) {
    .hidden-lg {
        display: none !important
    }
}

.visible-print {
    display: none !important
}

@media print {
    .visible-print {
        display: block !important
    }
    table.visible-print {
        display: table !important
    }
    tr.visible-print {
        display: table-row !important
    }
    td.visible-print,
    th.visible-print {
        display: table-cell !important
    }
}

.visible-print-block {
    display: none !important
}

@media print {
    .visible-print-block {
        display: block !important
    }
}

.visible-print-inline {
    display: none !important
}

@media print {
    .visible-print-inline {
        display: inline !important
    }
}

.visible-print-inline-block {
    display: none !important
}

@media print {
    .visible-print-inline-block {
        display: inline-block !important
    }
}

@media print {
    .hidden-print {
        display: none !important
    }
}

/*!
  Ionicons, v2.0.0
  Created by Ben Sperry for the Ionic Framework, http://ionicons.com/
  https://twitter.com/benjsperry  https://twitter.com/ionicframework
  MIT License: https://github.com/driftyco/ionicons

  Android-style icons originally built by Google’s
  Material Design Icons: https://github.com/google/material-design-icons
  used under CC BY http://creativecommons.org/licenses/by/4.0/
  Modified icons to fit ionicon’s grid from original.
*/

@font-face {
    font-family: Ionicons;
    src: url("../fonts/ionicons.eot?v=2.0.0");
    src: url("../fonts/ionicons.eot?v=2.0.0#iefix") format("embedded-opentype"), url("../fonts/ionicons.ttf?v=2.0.0") format("truetype"), url("../fonts/ionicons.woff?v=2.0.0") format("woff"), url("../fonts/ionicons.svg?v=2.0.0#Ionicons") format("svg");
    font-weight: 400;
    font-style: normal
}

.ion,
.ion-alert-circled:before,
.ion-alert:before,
.ion-android-add-circle:before,
.ion-android-add:before,
.ion-android-alarm-clock:before,
.ion-android-alert:before,
.ion-android-apps:before,
.ion-android-archive:before,
.ion-android-arrow-back:before,
.ion-android-arrow-down:before,
.ion-android-arrow-dropdown-circle:before,
.ion-android-arrow-dropdown:before,
.ion-android-arrow-dropleft-circle:before,
.ion-android-arrow-dropleft:before,
.ion-android-arrow-dropright-circle:before,
.ion-android-arrow-dropright:before,
.ion-android-arrow-dropup-circle:before,
.ion-android-arrow-dropup:before,
.ion-android-arrow-forward:before,
.ion-android-arrow-up:before,
.ion-android-attach:before,
.ion-android-bar:before,
.ion-android-bicycle:before,
.ion-android-boat:before,
.ion-android-bookmark:before,
.ion-android-bulb:before,
.ion-android-bus:before,
.ion-android-calendar:before,
.ion-android-call:before,
.ion-android-camera:before,
.ion-android-cancel:before,
.ion-android-car:before,
.ion-android-cart:before,
.ion-android-chat:before,
.ion-android-checkbox-blank:before,
.ion-android-checkbox-outline-blank:before,
.ion-android-checkbox-outline:before,
.ion-android-checkbox:before,
.ion-android-checkmark-circle:before,
.ion-android-clipboard:before,
.ion-android-close:before,
.ion-android-cloud-circle:before,
.ion-android-cloud-done:before,
.ion-android-cloud-outline:before,
.ion-android-cloud:before,
.ion-android-color-palette:before,
.ion-android-compass:before,
.ion-android-contact:before,
.ion-android-contacts:before,
.ion-android-contract:before,
.ion-android-create:before,
.ion-android-delete:before,
.ion-android-desktop:before,
.ion-android-document:before,
.ion-android-done-all:before,
.ion-android-done:before,
.ion-android-download:before,
.ion-android-drafts:before,
.ion-android-exit:before,
.ion-android-expand:before,
.ion-android-favorite-outline:before,
.ion-android-favorite:before,
.ion-android-film:before,
.ion-android-folder-open:before,
.ion-android-folder:before,
.ion-android-funnel:before,
.ion-android-globe:before,
.ion-android-hand:before,
.ion-android-hangout:before,
.ion-android-happy:before,
.ion-android-home:before,
.ion-android-image:before,
.ion-android-laptop:before,
.ion-android-list:before,
.ion-android-locate:before,
.ion-android-lock:before,
.ion-android-mail:before,
.ion-android-map:before,
.ion-android-menu:before,
.ion-android-microphone-off:before,
.ion-android-microphone:before,
.ion-android-more-horizontal:before,
.ion-android-more-vertical:before,
.ion-android-navigate:before,
.ion-android-notifications-none:before,
.ion-android-notifications-off:before,
.ion-android-notifications:before,
.ion-android-open:before,
.ion-android-options:before,
.ion-android-people:before,
.ion-android-person-add:before,
.ion-android-person:before,
.ion-android-phone-landscape:before,
.ion-android-phone-portrait:before,
.ion-android-pin:before,
.ion-android-plane:before,
.ion-android-playstore:before,
.ion-android-print:before,
.ion-android-radio-button-off:before,
.ion-android-radio-button-on:before,
.ion-android-refresh:before,
.ion-android-remove-circle:before,
.ion-android-remove:before,
.ion-android-restaurant:before,
.ion-android-sad:before,
.ion-android-search:before,
.ion-android-send:before,
.ion-android-settings:before,
.ion-android-share-alt:before,
.ion-android-share:before,
.ion-android-star-half:before,
.ion-android-star-outline:before,
.ion-android-star:before,
.ion-android-stopwatch:before,
.ion-android-subway:before,
.ion-android-sunny:before,
.ion-android-sync:before,
.ion-android-textsms:before,
.ion-android-time:before,
.ion-android-train:before,
.ion-android-unlock:before,
.ion-android-upload:before,
.ion-android-volume-down:before,
.ion-android-volume-mute:before,
.ion-android-volume-off:before,
.ion-android-volume-up:before,
.ion-android-walk:before,
.ion-android-warning:before,
.ion-android-watch:before,
.ion-android-wifi:before,
.ion-aperture:before,
.ion-archive:before,
.ion-arrow-down-a:before,
.ion-arrow-down-b:before,
.ion-arrow-down-c:before,
.ion-arrow-expand:before,
.ion-arrow-graph-down-left:before,
.ion-arrow-graph-down-right:before,
.ion-arrow-graph-up-left:before,
.ion-arrow-graph-up-right:before,
.ion-arrow-left-a:before,
.ion-arrow-left-b:before,
.ion-arrow-left-c:before,
.ion-arrow-move:before,
.ion-arrow-resize:before,
.ion-arrow-return-left:before,
.ion-arrow-return-right:before,
.ion-arrow-right-a:before,
.ion-arrow-right-b:before,
.ion-arrow-right-c:before,
.ion-arrow-shrink:before,
.ion-arrow-swap:before,
.ion-arrow-up-a:before,
.ion-arrow-up-b:before,
.ion-arrow-up-c:before,
.ion-asterisk:before,
.ion-at:before,
.ion-backspace-outline:before,
.ion-backspace:before,
.ion-bag:before,
.ion-battery-charging:before,
.ion-battery-empty:before,
.ion-battery-full:before,
.ion-battery-half:before,
.ion-battery-low:before,
.ion-beaker:before,
.ion-beer:before,
.ion-bluetooth:before,
.ion-bonfire:before,
.ion-bookmark:before,
.ion-bowtie:before,
.ion-briefcase:before,
.ion-bug:before,
.ion-calculator:before,
.ion-calendar:before,
.ion-camera:before,
.ion-card:before,
.ion-cash:before,
.ion-chatbox-working:before,
.ion-chatbox:before,
.ion-chatboxes:before,
.ion-chatbubble-working:before,
.ion-chatbubble:before,
.ion-chatbubbles:before,
.ion-checkmark-circled:before,
.ion-checkmark-round:before,
.ion-checkmark:before,
.ion-chevron-down:before,
.ion-chevron-left:before,
.ion-chevron-right:before,
.ion-chevron-up:before,
.ion-clipboard:before,
.ion-clock:before,
.ion-close-circled:before,
.ion-close-round:before,
.ion-close:before,
.ion-closed-captioning:before,
.ion-cloud:before,
.ion-code-download:before,
.ion-code-working:before,
.ion-code:before,
.ion-coffee:before,
.ion-compass:before,
.ion-compose:before,
.ion-connection-bars:before,
.ion-contrast:before,
.ion-crop:before,
.ion-cube:before,
.ion-disc:before,
.ion-document-text:before,
.ion-document:before,
.ion-drag:before,
.ion-earth:before,
.ion-easel:before,
.ion-edit:before,
.ion-egg:before,
.ion-eject:before,
.ion-email-unread:before,
.ion-email:before,
.ion-erlenmeyer-flask-bubbles:before,
.ion-erlenmeyer-flask:before,
.ion-eye-disabled:before,
.ion-eye:before,
.ion-female:before,
.ion-filing:before,
.ion-film-marker:before,
.ion-fireball:before,
.ion-flag:before,
.ion-flame:before,
.ion-flash-off:before,
.ion-flash:before,
.ion-folder:before,
.ion-fork-repo:before,
.ion-fork:before,
.ion-forward:before,
.ion-funnel:before,
.ion-gear-a:before,
.ion-gear-b:before,
.ion-grid:before,
.ion-hammer:before,
.ion-happy-outline:before,
.ion-happy:before,
.ion-headphone:before,
.ion-heart-broken:before,
.ion-heart:before,
.ion-help-buoy:before,
.ion-help-circled:before,
.ion-help:before,
.ion-home:before,
.ion-icecream:before,
.ion-image:before,
.ion-images:before,
.ion-information-circled:before,
.ion-information:before,
.ion-ionic:before,
.ion-ios-alarm-outline:before,
.ion-ios-alarm:before,
.ion-ios-albums-outline:before,
.ion-ios-albums:before,
.ion-ios-americanfootball-outline:before,
.ion-ios-americanfootball:before,
.ion-ios-analytics-outline:before,
.ion-ios-analytics:before,
.ion-ios-arrow-back:before,
.ion-ios-arrow-down:before,
.ion-ios-arrow-forward:before,
.ion-ios-arrow-left:before,
.ion-ios-arrow-right:before,
.ion-ios-arrow-thin-down:before,
.ion-ios-arrow-thin-left:before,
.ion-ios-arrow-thin-right:before,
.ion-ios-arrow-thin-up:before,
.ion-ios-arrow-up:before,
.ion-ios-at-outline:before,
.ion-ios-at:before,
.ion-ios-barcode-outline:before,
.ion-ios-barcode:before,
.ion-ios-baseball-outline:before,
.ion-ios-baseball:before,
.ion-ios-basketball-outline:before,
.ion-ios-basketball:before,
.ion-ios-bell-outline:before,
.ion-ios-bell:before,
.ion-ios-body-outline:before,
.ion-ios-body:before,
.ion-ios-bolt-outline:before,
.ion-ios-bolt:before,
.ion-ios-book-outline:before,
.ion-ios-book:before,
.ion-ios-bookmarks-outline:before,
.ion-ios-bookmarks:before,
.ion-ios-box-outline:before,
.ion-ios-box:before,
.ion-ios-briefcase-outline:before,
.ion-ios-briefcase:before,
.ion-ios-browsers-outline:before,
.ion-ios-browsers:before,
.ion-ios-calculator-outline:before,
.ion-ios-calculator:before,
.ion-ios-calendar-outline:before,
.ion-ios-calendar:before,
.ion-ios-camera-outline:before,
.ion-ios-camera:before,
.ion-ios-cart-outline:before,
.ion-ios-cart:before,
.ion-ios-chatboxes-outline:before,
.ion-ios-chatboxes:before,
.ion-ios-chatbubble-outline:before,
.ion-ios-chatbubble:before,
.ion-ios-checkmark-empty:before,
.ion-ios-checkmark-outline:before,
.ion-ios-checkmark:before,
.ion-ios-circle-filled:before,
.ion-ios-circle-outline:before,
.ion-ios-clock-outline:before,
.ion-ios-clock:before,
.ion-ios-close-empty:before,
.ion-ios-close-outline:before,
.ion-ios-close:before,
.ion-ios-cloud-download-outline:before,
.ion-ios-cloud-download:before,
.ion-ios-cloud-outline:before,
.ion-ios-cloud-upload-outline:before,
.ion-ios-cloud-upload:before,
.ion-ios-cloud:before,
.ion-ios-cloudy-night-outline:before,
.ion-ios-cloudy-night:before,
.ion-ios-cloudy-outline:before,
.ion-ios-cloudy:before,
.ion-ios-cog-outline:before,
.ion-ios-cog:before,
.ion-ios-color-filter-outline:before,
.ion-ios-color-filter:before,
.ion-ios-color-wand-outline:before,
.ion-ios-color-wand:before,
.ion-ios-compose-outline:before,
.ion-ios-compose:before,
.ion-ios-contact-outline:before,
.ion-ios-contact:before,
.ion-ios-copy-outline:before,
.ion-ios-copy:before,
.ion-ios-crop-strong:before,
.ion-ios-crop:before,
.ion-ios-download-outline:before,
.ion-ios-download:before,
.ion-ios-drag:before,
.ion-ios-email-outline:before,
.ion-ios-email:before,
.ion-ios-eye-outline:before,
.ion-ios-eye:before,
.ion-ios-fastforward-outline:before,
.ion-ios-fastforward:before,
.ion-ios-filing-outline:before,
.ion-ios-filing:before,
.ion-ios-film-outline:before,
.ion-ios-film:before,
.ion-ios-flag-outline:before,
.ion-ios-flag:before,
.ion-ios-flame-outline:before,
.ion-ios-flame:before,
.ion-ios-flask-outline:before,
.ion-ios-flask:before,
.ion-ios-flower-outline:before,
.ion-ios-flower:before,
.ion-ios-folder-outline:before,
.ion-ios-folder:before,
.ion-ios-football-outline:before,
.ion-ios-football:before,
.ion-ios-game-controller-a-outline:before,
.ion-ios-game-controller-a:before,
.ion-ios-game-controller-b-outline:before,
.ion-ios-game-controller-b:before,
.ion-ios-gear-outline:before,
.ion-ios-gear:before,
.ion-ios-glasses-outline:before,
.ion-ios-glasses:before,
.ion-ios-grid-view-outline:before,
.ion-ios-grid-view:before,
.ion-ios-heart-outline:before,
.ion-ios-heart:before,
.ion-ios-help-empty:before,
.ion-ios-help-outline:before,
.ion-ios-help:before,
.ion-ios-home-outline:before,
.ion-ios-home:before,
.ion-ios-infinite-outline:before,
.ion-ios-infinite:before,
.ion-ios-information-empty:before,
.ion-ios-information-outline:before,
.ion-ios-information:before,
.ion-ios-ionic-outline:before,
.ion-ios-keypad-outline:before,
.ion-ios-keypad:before,
.ion-ios-lightbulb-outline:before,
.ion-ios-lightbulb:before,
.ion-ios-list-outline:before,
.ion-ios-list:before,
.ion-ios-location-outline:before,
.ion-ios-location:before,
.ion-ios-locked-outline:before,
.ion-ios-locked:before,
.ion-ios-loop-strong:before,
.ion-ios-loop:before,
.ion-ios-medical-outline:before,
.ion-ios-medical:before,
.ion-ios-medkit-outline:before,
.ion-ios-medkit:before,
.ion-ios-mic-off:before,
.ion-ios-mic-outline:before,
.ion-ios-mic:before,
.ion-ios-minus-empty:before,
.ion-ios-minus-outline:before,
.ion-ios-minus:before,
.ion-ios-monitor-outline:before,
.ion-ios-monitor:before,
.ion-ios-moon-outline:before,
.ion-ios-moon:before,
.ion-ios-more-outline:before,
.ion-ios-more:before,
.ion-ios-musical-note:before,
.ion-ios-musical-notes:before,
.ion-ios-navigate-outline:before,
.ion-ios-navigate:before,
.ion-ios-nutrition-outline:before,
.ion-ios-nutrition:before,
.ion-ios-paper-outline:before,
.ion-ios-paper:before,
.ion-ios-paperplane-outline:before,
.ion-ios-paperplane:before,
.ion-ios-partlysunny-outline:before,
.ion-ios-partlysunny:before,
.ion-ios-pause-outline:before,
.ion-ios-pause:before,
.ion-ios-paw-outline:before,
.ion-ios-paw:before,
.ion-ios-people-outline:before,
.ion-ios-people:before,
.ion-ios-person-outline:before,
.ion-ios-person:before,
.ion-ios-personadd-outline:before,
.ion-ios-personadd:before,
.ion-ios-photos-outline:before,
.ion-ios-photos:before,
.ion-ios-pie-outline:before,
.ion-ios-pie:before,
.ion-ios-pint-outline:before,
.ion-ios-pint:before,
.ion-ios-play-outline:before,
.ion-ios-play:before,
.ion-ios-plus-empty:before,
.ion-ios-plus-outline:before,
.ion-ios-plus:before,
.ion-ios-pricetag-outline:before,
.ion-ios-pricetag:before,
.ion-ios-pricetags-outline:before,
.ion-ios-pricetags:before,
.ion-ios-printer-outline:before,
.ion-ios-printer:before,
.ion-ios-pulse-strong:before,
.ion-ios-pulse:before,
.ion-ios-rainy-outline:before,
.ion-ios-rainy:before,
.ion-ios-recording-outline:before,
.ion-ios-recording:before,
.ion-ios-redo-outline:before,
.ion-ios-redo:before,
.ion-ios-refresh-empty:before,
.ion-ios-refresh-outline:before,
.ion-ios-refresh:before,
.ion-ios-reload:before,
.ion-ios-reverse-camera-outline:before,
.ion-ios-reverse-camera:before,
.ion-ios-rewind-outline:before,
.ion-ios-rewind:before,
.ion-ios-rose-outline:before,
.ion-ios-rose:before,
.ion-ios-search-strong:before,
.ion-ios-search:before,
.ion-ios-settings-strong:before,
.ion-ios-settings:before,
.ion-ios-shuffle-strong:before,
.ion-ios-shuffle:before,
.ion-ios-skipbackward-outline:before,
.ion-ios-skipbackward:before,
.ion-ios-skipforward-outline:before,
.ion-ios-skipforward:before,
.ion-ios-snowy:before,
.ion-ios-speedometer-outline:before,
.ion-ios-speedometer:before,
.ion-ios-star-half:before,
.ion-ios-star-outline:before,
.ion-ios-star:before,
.ion-ios-stopwatch-outline:before,
.ion-ios-stopwatch:before,
.ion-ios-sunny-outline:before,
.ion-ios-sunny:before,
.ion-ios-telephone-outline:before,
.ion-ios-telephone:before,
.ion-ios-tennisball-outline:before,
.ion-ios-tennisball:before,
.ion-ios-thunderstorm-outline:before,
.ion-ios-thunderstorm:before,
.ion-ios-time-outline:before,
.ion-ios-time:before,
.ion-ios-timer-outline:before,
.ion-ios-timer:before,
.ion-ios-toggle-outline:before,
.ion-ios-toggle:before,
.ion-ios-trash-outline:before,
.ion-ios-trash:before,
.ion-ios-undo-outline:before,
.ion-ios-undo:before,
.ion-ios-unlocked-outline:before,
.ion-ios-unlocked:before,
.ion-ios-upload-outline:before,
.ion-ios-upload:before,
.ion-ios-videocam-outline:before,
.ion-ios-videocam:before,
.ion-ios-volume-high:before,
.ion-ios-volume-low:before,
.ion-ios-wineglass-outline:before,
.ion-ios-wineglass:before,
.ion-ios-world-outline:before,
.ion-ios-world:before,
.ion-ipad:before,
.ion-iphone:before,
.ion-ipod:before,
.ion-jet:before,
.ion-key:before,
.ion-knife:before,
.ion-laptop:before,
.ion-leaf:before,
.ion-levels:before,
.ion-lightbulb:before,
.ion-link:before,
.ion-load-a:before,
.ion-load-b:before,
.ion-load-c:before,
.ion-load-d:before,
.ion-location:before,
.ion-lock-combination:before,
.ion-locked:before,
.ion-log-in:before,
.ion-log-out:before,
.ion-loop:before,
.ion-magnet:before,
.ion-male:before,
.ion-man:before,
.ion-map:before,
.ion-medkit:before,
.ion-merge:before,
.ion-mic-a:before,
.ion-mic-b:before,
.ion-mic-c:before,
.ion-minus-circled:before,
.ion-minus-round:before,
.ion-minus:before,
.ion-model-s:before,
.ion-monitor:before,
.ion-more:before,
.ion-mouse:before,
.ion-music-note:before,
.ion-navicon-round:before,
.ion-navicon:before,
.ion-navigate:before,
.ion-network:before,
.ion-no-smoking:before,
.ion-nuclear:before,
.ion-outlet:before,
.ion-paintbrush:before,
.ion-paintbucket:before,
.ion-paper-airplane:before,
.ion-paperclip:before,
.ion-pause:before,
.ion-person-add:before,
.ion-person-stalker:before,
.ion-person:before,
.ion-pie-graph:before,
.ion-pin:before,
.ion-pinpoint:before,
.ion-pizza:before,
.ion-plane:before,
.ion-planet:before,
.ion-play:before,
.ion-playstation:before,
.ion-plus-circled:before,
.ion-plus-round:before,
.ion-plus:before,
.ion-podium:before,
.ion-pound:before,
.ion-power:before,
.ion-pricetag:before,
.ion-pricetags:before,
.ion-printer:before,
.ion-pull-request:before,
.ion-qr-scanner:before,
.ion-quote:before,
.ion-radio-waves:before,
.ion-record:before,
.ion-refresh:before,
.ion-reply-all:before,
.ion-reply:before,
.ion-ribbon-a:before,
.ion-ribbon-b:before,
.ion-sad-outline:before,
.ion-sad:before,
.ion-scissors:before,
.ion-search:before,
.ion-settings:before,
.ion-share:before,
.ion-shuffle:before,
.ion-skip-backward:before,
.ion-skip-forward:before,
.ion-social-android-outline:before,
.ion-social-android:before,
.ion-social-angular-outline:before,
.ion-social-angular:before,
.ion-social-apple-outline:before,
.ion-social-apple:before,
.ion-social-bitcoin-outline:before,
.ion-social-bitcoin:before,
.ion-social-buffer-outline:before,
.ion-social-buffer:before,
.ion-social-chrome-outline:before,
.ion-social-chrome:before,
.ion-social-codepen-outline:before,
.ion-social-codepen:before,
.ion-social-css3-outline:before,
.ion-social-css3:before,
.ion-social-designernews-outline:before,
.ion-social-designernews:before,
.ion-social-dribbble-outline:before,
.ion-social-dribbble:before,
.ion-social-dropbox-outline:before,
.ion-social-dropbox:before,
.ion-social-euro-outline:before,
.ion-social-euro:before,
.ion-social-facebook-outline:before,
.ion-social-facebook:before,
.ion-social-foursquare-outline:before,
.ion-social-foursquare:before,
.ion-social-freebsd-devil:before,
.ion-social-github-outline:before,
.ion-social-github:before,
.ion-social-google-outline:before,
.ion-social-google:before,
.ion-social-googleplus-outline:before,
.ion-social-googleplus:before,
.ion-social-hackernews-outline:before,
.ion-social-hackernews:before,
.ion-social-html5-outline:before,
.ion-social-html5:before,
.ion-social-instagram-outline:before,
.ion-social-instagram:before,
.ion-social-javascript-outline:before,
.ion-social-javascript:before,
.ion-social-linkedin-outline:before,
.ion-social-linkedin:before,
.ion-social-markdown:before,
.ion-social-nodejs:before,
.ion-social-octocat:before,
.ion-social-pinterest-outline:before,
.ion-social-pinterest:before,
.ion-social-python:before,
.ion-social-reddit-outline:before,
.ion-social-reddit:before,
.ion-social-rss-outline:before,
.ion-social-rss:before,
.ion-social-sass:before,
.ion-social-skype-outline:before,
.ion-social-skype:before,
.ion-social-snapchat-outline:before,
.ion-social-snapchat:before,
.ion-social-tumblr-outline:before,
.ion-social-tumblr:before,
.ion-social-tux:before,
.ion-social-twitch-outline:before,
.ion-social-twitch:before,
.ion-social-twitter-outline:before,
.ion-social-twitter:before,
.ion-social-usd-outline:before,
.ion-social-usd:before,
.ion-social-vimeo-outline:before,
.ion-social-vimeo:before,
.ion-social-whatsapp-outline:before,
.ion-social-whatsapp:before,
.ion-social-windows-outline:before,
.ion-social-windows:before,
.ion-social-wordpress-outline:before,
.ion-social-wordpress:before,
.ion-social-yahoo-outline:before,
.ion-social-yahoo:before,
.ion-social-yen-outline:before,
.ion-social-yen:before,
.ion-social-youtube-outline:before,
.ion-social-youtube:before,
.ion-soup-can-outline:before,
.ion-soup-can:before,
.ion-speakerphone:before,
.ion-speedometer:before,
.ion-spoon:before,
.ion-star:before,
.ion-stats-bars:before,
.ion-steam:before,
.ion-stop:before,
.ion-thermometer:before,
.ion-thumbsdown:before,
.ion-thumbsup:before,
.ion-toggle-filled:before,
.ion-toggle:before,
.ion-transgender:before,
.ion-trash-a:before,
.ion-trash-b:before,
.ion-trophy:before,
.ion-tshirt-outline:before,
.ion-tshirt:before,
.ion-umbrella:before,
.ion-university:before,
.ion-unlocked:before,
.ion-upload:before,
.ion-usb:before,
.ion-videocamera:before,
.ion-volume-high:before,
.ion-volume-low:before,
.ion-volume-medium:before,
.ion-volume-mute:before,
.ion-wand:before,
.ion-waterdrop:before,
.ion-wifi:before,
.ion-wineglass:before,
.ion-woman:before,
.ion-wrench:before,
.ion-xbox:before,
.ionicons {
    display: inline-block;
    font-family: Ionicons;
    speak: none;
    font-style: normal;
    font-weight: 400;
    font-variant: normal;
    text-transform: none;
    text-rendering: auto;
    line-height: 1;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale
}

.ion-alert:before {
    content: "\f101"
}

.ion-alert-circled:before {
    content: "\f100"
}

.ion-android-add:before {
    content: "\f2c7"
}

.ion-android-add-circle:before {
    content: "\f359"
}

.ion-android-alarm-clock:before {
    content: "\f35a"
}

.ion-android-alert:before {
    content: "\f35b"
}

.ion-android-apps:before {
    content: "\f35c"
}

.ion-android-archive:before {
    content: "\f2c9"
}

.ion-android-arrow-back:before {
    content: "\f2ca"
}

.ion-android-arrow-down:before {
    content: "\f35d"
}

.ion-android-arrow-dropdown:before {
    content: "\f35f"
}

.ion-android-arrow-dropdown-circle:before {
    content: "\f35e"
}

.ion-android-arrow-dropleft:before {
    content: "\f361"
}

.ion-android-arrow-dropleft-circle:before {
    content: "\f360"
}

.ion-android-arrow-dropright:before {
    content: "\f363"
}

.ion-android-arrow-dropright-circle:before {
    content: "\f362"
}

.ion-android-arrow-dropup:before {
    content: "\f365"
}

.ion-android-arrow-dropup-circle:before {
    content: "\f364"
}

.ion-android-arrow-forward:before {
    content: "\f30f"
}

.ion-android-arrow-up:before {
    content: "\f366"
}

.ion-android-attach:before {
    content: "\f367"
}

.ion-android-bar:before {
    content: "\f368"
}

.ion-android-bicycle:before {
    content: "\f369"
}

.ion-android-boat:before {
    content: "\f36a"
}

.ion-android-bookmark:before {
    content: "\f36b"
}

.ion-android-bulb:before {
    content: "\f36c"
}

.ion-android-bus:before {
    content: "\f36d"
}

.ion-android-calendar:before {
    content: "\f2d1"
}

.ion-android-call:before {
    content: "\f2d2"
}

.ion-android-camera:before {
    content: "\f2d3"
}

.ion-android-cancel:before {
    content: "\f36e"
}

.ion-android-car:before {
    content: "\f36f"
}

.ion-android-cart:before {
    content: "\f370"
}

.ion-android-chat:before {
    content: "\f2d4"
}

.ion-android-checkbox:before {
    content: "\f374"
}

.ion-android-checkbox-blank:before {
    content: "\f371"
}

.ion-android-checkbox-outline:before {
    content: "\f373"
}

.ion-android-checkbox-outline-blank:before {
    content: "\f372"
}

.ion-android-checkmark-circle:before {
    content: "\f375"
}

.ion-android-clipboard:before {
    content: "\f376"
}

.ion-android-close:before {
    content: "\f2d7"
}

.ion-android-cloud:before {
    content: "\f37a"
}

.ion-android-cloud-circle:before {
    content: "\f377"
}

.ion-android-cloud-done:before {
    content: "\f378"
}

.ion-android-cloud-outline:before {
    content: "\f379"
}

.ion-android-color-palette:before {
    content: "\f37b"
}

.ion-android-compass:before {
    content: "\f37c"
}

.ion-android-contact:before {
    content: "\f2d8"
}

.ion-android-contacts:before {
    content: "\f2d9"
}

.ion-android-contract:before {
    content: "\f37d"
}

.ion-android-create:before {
    content: "\f37e"
}

.ion-android-delete:before {
    content: "\f37f"
}

.ion-android-desktop:before {
    content: "\f380"
}

.ion-android-document:before {
    content: "\f381"
}

.ion-android-done:before {
    content: "\f383"
}

.ion-android-done-all:before {
    content: "\f382"
}

.ion-android-download:before {
    content: "\f2dd"
}

.ion-android-drafts:before {
    content: "\f384"
}

.ion-android-exit:before {
    content: "\f385"
}

.ion-android-expand:before {
    content: "\f386"
}

.ion-android-favorite:before {
    content: "\f388"
}

.ion-android-favorite-outline:before {
    content: "\f387"
}

.ion-android-film:before {
    content: "\f389"
}

.ion-android-folder:before {
    content: "\f2e0"
}

.ion-android-folder-open:before {
    content: "\f38a"
}

.ion-android-funnel:before {
    content: "\f38b"
}

.ion-android-globe:before {
    content: "\f38c"
}

.ion-android-hand:before {
    content: "\f2e3"
}

.ion-android-hangout:before {
    content: "\f38d"
}

.ion-android-happy:before {
    content: "\f38e"
}

.ion-android-home:before {
    content: "\f38f"
}

.ion-android-image:before {
    content: "\f2e4"
}

.ion-android-laptop:before {
    content: "\f390"
}

.ion-android-list:before {
    content: "\f391"
}

.ion-android-locate:before {
    content: "\f2e9"
}

.ion-android-lock:before {
    content: "\f392"
}

.ion-android-mail:before {
    content: "\f2eb"
}

.ion-android-map:before {
    content: "\f393"
}

.ion-android-menu:before {
    content: "\f394"
}

.ion-android-microphone:before {
    content: "\f2ec"
}

.ion-android-microphone-off:before {
    content: "\f395"
}

.ion-android-more-horizontal:before {
    content: "\f396"
}

.ion-android-more-vertical:before {
    content: "\f397"
}

.ion-android-navigate:before {
    content: "\f398"
}

.ion-android-notifications:before {
    content: "\f39b"
}

.ion-android-notifications-none:before {
    content: "\f399"
}

.ion-android-notifications-off:before {
    content: "\f39a"
}

.ion-android-open:before {
    content: "\f39c"
}

.ion-android-options:before {
    content: "\f39d"
}

.ion-android-people:before {
    content: "\f39e"
}

.ion-android-person:before {
    content: "\f3a0"
}

.ion-android-person-add:before {
    content: "\f39f"
}

.ion-android-phone-landscape:before {
    content: "\f3a1"
}

.ion-android-phone-portrait:before {
    content: "\f3a2"
}

.ion-android-pin:before {
    content: "\f3a3"
}

.ion-android-plane:before {
    content: "\f3a4"
}

.ion-android-playstore:before {
    content: "\f2f0"
}

.ion-android-print:before {
    content: "\f3a5"
}

.ion-android-radio-button-off:before {
    content: "\f3a6"
}

.ion-android-radio-button-on:before {
    content: "\f3a7"
}

.ion-android-refresh:before {
    content: "\f3a8"
}

.ion-android-remove:before {
    content: "\f2f4"
}

.ion-android-remove-circle:before {
    content: "\f3a9"
}

.ion-android-restaurant:before {
    content: "\f3aa"
}

.ion-android-sad:before {
    content: "\f3ab"
}

.ion-android-search:before {
    content: "\f2f5"
}

.ion-android-send:before {
    content: "\f2f6"
}

.ion-android-settings:before {
    content: "\f2f7"
}

.ion-android-share:before {
    content: "\f2f8"
}

.ion-android-share-alt:before {
    content: "\f3ac"
}

.ion-android-star:before {
    content: "\f2fc"
}

.ion-android-star-half:before {
    content: "\f3ad"
}

.ion-android-star-outline:before {
    content: "\f3ae"
}

.ion-android-stopwatch:before {
    content: "\f2fd"
}

.ion-android-subway:before {
    content: "\f3af"
}

.ion-android-sunny:before {
    content: "\f3b0"
}

.ion-android-sync:before {
    content: "\f3b1"
}

.ion-android-textsms:before {
    content: "\f3b2"
}

.ion-android-time:before {
    content: "\f3b3"
}

.ion-android-train:before {
    content: "\f3b4"
}

.ion-android-unlock:before {
    content: "\f3b5"
}

.ion-android-upload:before {
    content: "\f3b6"
}

.ion-android-volume-down:before {
    content: "\f3b7"
}

.ion-android-volume-mute:before {
    content: "\f3b8"
}

.ion-android-volume-off:before {
    content: "\f3b9"
}

.ion-android-volume-up:before {
    content: "\f3ba"
}

.ion-android-walk:before {
    content: "\f3bb"
}

.ion-android-warning:before {
    content: "\f3bc"
}

.ion-android-watch:before {
    content: "\f3bd"
}

.ion-android-wifi:before {
    content: "\f305"
}

.ion-aperture:before {
    content: "\f313"
}

.ion-archive:before {
    content: "\f102"
}

.ion-arrow-down-a:before {
    content: "\f103"
}

.ion-arrow-down-b:before {
    content: "\f104"
}

.ion-arrow-down-c:before {
    content: "\f105"
}

.ion-arrow-expand:before {
    content: "\f25e"
}

.ion-arrow-graph-down-left:before {
    content: "\f25f"
}

.ion-arrow-graph-down-right:before {
    content: "\f260"
}

.ion-arrow-graph-up-left:before {
    content: "\f261"
}

.ion-arrow-graph-up-right:before {
    content: "\f262"
}

.ion-arrow-left-a:before {
    content: "\f106"
}

.ion-arrow-left-b:before {
    content: "\f107"
}

.ion-arrow-left-c:before {
    content: "\f108"
}

.ion-arrow-move:before {
    content: "\f263"
}

.ion-arrow-resize:before {
    content: "\f264"
}

.ion-arrow-return-left:before {
    content: "\f265"
}

.ion-arrow-return-right:before {
    content: "\f266"
}

.ion-arrow-right-a:before {
    content: "\f109"
}

.ion-arrow-right-b:before {
    content: "\f10a"
}

.ion-arrow-right-c:before {
    content: "\f10b"
}

.ion-arrow-shrink:before {
    content: "\f267"
}

.ion-arrow-swap:before {
    content: "\f268"
}

.ion-arrow-up-a:before {
    content: "\f10c"
}

.ion-arrow-up-b:before {
    content: "\f10d"
}

.ion-arrow-up-c:before {
    content: "\f10e"
}

.ion-asterisk:before {
    content: "\f314"
}

.ion-at:before {
    content: "\f10f"
}

.ion-backspace:before {
    content: "\f3bf"
}

.ion-backspace-outline:before {
    content: "\f3be"
}

.ion-bag:before {
    content: "\f110"
}

.ion-battery-charging:before {
    content: "\f111"
}

.ion-battery-empty:before {
    content: "\f112"
}

.ion-battery-full:before {
    content: "\f113"
}

.ion-battery-half:before {
    content: "\f114"
}

.ion-battery-low:before {
    content: "\f115"
}

.ion-beaker:before {
    content: "\f269"
}

.ion-beer:before {
    content: "\f26a"
}

.ion-bluetooth:before {
    content: "\f116"
}

.ion-bonfire:before {
    content: "\f315"
}

.ion-bookmark:before {
    content: "\f26b"
}

.ion-bowtie:before {
    content: "\f3c0"
}

.ion-briefcase:before {
    content: "\f26c"
}

.ion-bug:before {
    content: "\f2be"
}

.ion-calculator:before {
    content: "\f26d"
}

.ion-calendar:before {
    content: "\f117"
}

.ion-camera:before {
    content: "\f118"
}

.ion-card:before {
    content: "\f119"
}

.ion-cash:before {
    content: "\f316"
}

.ion-chatbox:before {
    content: "\f11b"
}

.ion-chatbox-working:before {
    content: "\f11a"
}

.ion-chatboxes:before {
    content: "\f11c"
}

.ion-chatbubble:before {
    content: "\f11e"
}

.ion-chatbubble-working:before {
    content: "\f11d"
}

.ion-chatbubbles:before {
    content: "\f11f"
}

.ion-checkmark:before {
    content: "\f122"
}

.ion-checkmark-circled:before {
    content: "\f120"
}

.ion-checkmark-round:before {
    content: "\f121"
}

.ion-chevron-down:before {
    content: "\f123"
}

.ion-chevron-left:before {
    content: "\f124"
}

.ion-chevron-right:before {
    content: "\f125"
}

.ion-chevron-up:before {
    content: "\f126"
}

.ion-clipboard:before {
    content: "\f127"
}

.ion-clock:before {
    content: "\f26e"
}

.ion-close:before {
    content: "\f12a"
}

.ion-close-circled:before {
    content: "\f128"
}

.ion-close-round:before {
    content: "\f129"
}

.ion-closed-captioning:before {
    content: "\f317"
}

.ion-cloud:before {
    content: "\f12b"
}

.ion-code:before {
    content: "\f271"
}

.ion-code-download:before {
    content: "\f26f"
}

.ion-code-working:before {
    content: "\f270"
}

.ion-coffee:before {
    content: "\f272"
}

.ion-compass:before {
    content: "\f273"
}

.ion-compose:before {
    content: "\f12c"
}

.ion-connection-bars:before {
    content: "\f274"
}

.ion-contrast:before {
    content: "\f275"
}

.ion-crop:before {
    content: "\f3c1"
}

.ion-cube:before {
    content: "\f318"
}

.ion-disc:before {
    content: "\f12d"
}

.ion-document:before {
    content: "\f12f"
}

.ion-document-text:before {
    content: "\f12e"
}

.ion-drag:before {
    content: "\f130"
}

.ion-earth:before {
    content: "\f276"
}

.ion-easel:before {
    content: "\f3c2"
}

.ion-edit:before {
    content: "\f2bf"
}

.ion-egg:before {
    content: "\f277"
}

.ion-eject:before {
    content: "\f131"
}

.ion-email:before {
    content: "\f132"
}

.ion-email-unread:before {
    content: "\f3c3"
}

.ion-erlenmeyer-flask:before {
    content: "\f3c5"
}

.ion-erlenmeyer-flask-bubbles:before {
    content: "\f3c4"
}

.ion-eye:before {
    content: "\f133"
}

.ion-eye-disabled:before {
    content: "\f306"
}

.ion-female:before {
    content: "\f278"
}

.ion-filing:before {
    content: "\f134"
}

.ion-film-marker:before {
    content: "\f135"
}

.ion-fireball:before {
    content: "\f319"
}

.ion-flag:before {
    content: "\f279"
}

.ion-flame:before {
    content: "\f31a"
}

.ion-flash:before {
    content: "\f137"
}

.ion-flash-off:before {
    content: "\f136"
}

.ion-folder:before {
    content: "\f139"
}

.ion-fork:before {
    content: "\f27a"
}

.ion-fork-repo:before {
    content: "\f2c0"
}

.ion-forward:before {
    content: "\f13a"
}

.ion-funnel:before {
    content: "\f31b"
}

.ion-gear-a:before {
    content: "\f13d"
}

.ion-gear-b:before {
    content: "\f13e"
}

.ion-grid:before {
    content: "\f13f"
}

.ion-hammer:before {
    content: "\f27b"
}

.ion-happy:before {
    content: "\f31c"
}

.ion-happy-outline:before {
    content: "\f3c6"
}

.ion-headphone:before {
    content: "\f140"
}

.ion-heart:before {
    content: "\f141"
}

.ion-heart-broken:before {
    content: "\f31d"
}

.ion-help:before {
    content: "\f143"
}

.ion-help-buoy:before {
    content: "\f27c"
}

.ion-help-circled:before {
    content: "\f142"
}

.ion-home:before {
    content: "\f144"
}

.ion-icecream:before {
    content: "\f27d"
}

.ion-image:before {
    content: "\f147"
}

.ion-images:before {
    content: "\f148"
}

.ion-information:before {
    content: "\f14a"
}

.ion-information-circled:before {
    content: "\f149"
}

.ion-ionic:before {
    content: "\f14b"
}

.ion-ios-alarm:before {
    content: "\f3c8"
}

.ion-ios-alarm-outline:before {
    content: "\f3c7"
}

.ion-ios-albums:before {
    content: "\f3ca"
}

.ion-ios-albums-outline:before {
    content: "\f3c9"
}

.ion-ios-americanfootball:before {
    content: "\f3cc"
}

.ion-ios-americanfootball-outline:before {
    content: "\f3cb"
}

.ion-ios-analytics:before {
    content: "\f3ce"
}

.ion-ios-analytics-outline:before {
    content: "\f3cd"
}

.ion-ios-arrow-back:before {
    content: "\f3cf"
}

.ion-ios-arrow-down:before {
    content: "\f3d0"
}

.ion-ios-arrow-forward:before {
    content: "\f3d1"
}

.ion-ios-arrow-left:before {
    content: "\f3d2"
}

.ion-ios-arrow-right:before {
    content: "\f3d3"
}

.ion-ios-arrow-thin-down:before {
    content: "\f3d4"
}

.ion-ios-arrow-thin-left:before {
    content: "\f3d5"
}

.ion-ios-arrow-thin-right:before {
    content: "\f3d6"
}

.ion-ios-arrow-thin-up:before {
    content: "\f3d7"
}

.ion-ios-arrow-up:before {
    content: "\f3d8"
}

.ion-ios-at:before {
    content: "\f3da"
}

.ion-ios-at-outline:before {
    content: "\f3d9"
}

.ion-ios-barcode:before {
    content: "\f3dc"
}

.ion-ios-barcode-outline:before {
    content: "\f3db"
}

.ion-ios-baseball:before {
    content: "\f3de"
}

.ion-ios-baseball-outline:before {
    content: "\f3dd"
}

.ion-ios-basketball:before {
    content: "\f3e0"
}

.ion-ios-basketball-outline:before {
    content: "\f3df"
}

.ion-ios-bell:before {
    content: "\f3e2"
}

.ion-ios-bell-outline:before {
    content: "\f3e1"
}

.ion-ios-body:before {
    content: "\f3e4"
}

.ion-ios-body-outline:before {
    content: "\f3e3"
}

.ion-ios-bolt:before {
    content: "\f3e6"
}

.ion-ios-bolt-outline:before {
    content: "\f3e5"
}

.ion-ios-book:before {
    content: "\f3e8"
}

.ion-ios-book-outline:before {
    content: "\f3e7"
}

.ion-ios-bookmarks:before {
    content: "\f3ea"
}

.ion-ios-bookmarks-outline:before {
    content: "\f3e9"
}

.ion-ios-box:before {
    content: "\f3ec"
}

.ion-ios-box-outline:before {
    content: "\f3eb"
}

.ion-ios-briefcase:before {
    content: "\f3ee"
}

.ion-ios-briefcase-outline:before {
    content: "\f3ed"
}

.ion-ios-browsers:before {
    content: "\f3f0"
}

.ion-ios-browsers-outline:before {
    content: "\f3ef"
}

.ion-ios-calculator:before {
    content: "\f3f2"
}

.ion-ios-calculator-outline:before {
    content: "\f3f1"
}

.ion-ios-calendar:before {
    content: "\f3f4"
}

.ion-ios-calendar-outline:before {
    content: "\f3f3"
}

.ion-ios-camera:before {
    content: "\f3f6"
}

.ion-ios-camera-outline:before {
    content: "\f3f5"
}

.ion-ios-cart:before {
    content: "\f3f8"
}

.ion-ios-cart-outline:before {
    content: "\f3f7"
}

.ion-ios-chatboxes:before {
    content: "\f3fa"
}

.ion-ios-chatboxes-outline:before {
    content: "\f3f9"
}

.ion-ios-chatbubble:before {
    content: "\f3fc"
}

.ion-ios-chatbubble-outline:before {
    content: "\f3fb"
}

.ion-ios-checkmark:before {
    content: "\f3ff"
}

.ion-ios-checkmark-empty:before {
    content: "\f3fd"
}

.ion-ios-checkmark-outline:before {
    content: "\f3fe"
}

.ion-ios-circle-filled:before {
    content: "\f400"
}

.ion-ios-circle-outline:before {
    content: "\f401"
}

.ion-ios-clock:before {
    content: "\f403"
}

.ion-ios-clock-outline:before {
    content: "\f402"
}

.ion-ios-close:before {
    content: "\f406"
}

.ion-ios-close-empty:before {
    content: "\f404"
}

.ion-ios-close-outline:before {
    content: "\f405"
}

.ion-ios-cloud:before {
    content: "\f40c"
}

.ion-ios-cloud-download:before {
    content: "\f408"
}

.ion-ios-cloud-download-outline:before {
    content: "\f407"
}

.ion-ios-cloud-outline:before {
    content: "\f409"
}

.ion-ios-cloud-upload:before {
    content: "\f40b"
}

.ion-ios-cloud-upload-outline:before {
    content: "\f40a"
}

.ion-ios-cloudy:before {
    content: "\f410"
}

.ion-ios-cloudy-night:before {
    content: "\f40e"
}

.ion-ios-cloudy-night-outline:before {
    content: "\f40d"
}

.ion-ios-cloudy-outline:before {
    content: "\f40f"
}

.ion-ios-cog:before {
    content: "\f412"
}

.ion-ios-cog-outline:before {
    content: "\f411"
}

.ion-ios-color-filter:before {
    content: "\f414"
}

.ion-ios-color-filter-outline:before {
    content: "\f413"
}

.ion-ios-color-wand:before {
    content: "\f416"
}

.ion-ios-color-wand-outline:before {
    content: "\f415"
}

.ion-ios-compose:before {
    content: "\f418"
}

.ion-ios-compose-outline:before {
    content: "\f417"
}

.ion-ios-contact:before {
    content: "\f41a"
}

.ion-ios-contact-outline:before {
    content: "\f419"
}

.ion-ios-copy:before {
    content: "\f41c"
}

.ion-ios-copy-outline:before {
    content: "\f41b"
}

.ion-ios-crop:before {
    content: "\f41e"
}

.ion-ios-crop-strong:before {
    content: "\f41d"
}

.ion-ios-download:before {
    content: "\f420"
}

.ion-ios-download-outline:before {
    content: "\f41f"
}

.ion-ios-drag:before {
    content: "\f421"
}

.ion-ios-email:before {
    content: "\f423"
}

.ion-ios-email-outline:before {
    content: "\f422"
}

.ion-ios-eye:before {
    content: "\f425"
}

.ion-ios-eye-outline:before {
    content: "\f424"
}

.ion-ios-fastforward:before {
    content: "\f427"
}

.ion-ios-fastforward-outline:before {
    content: "\f426"
}

.ion-ios-filing:before {
    content: "\f429"
}

.ion-ios-filing-outline:before {
    content: "\f428"
}

.ion-ios-film:before {
    content: "\f42b"
}

.ion-ios-film-outline:before {
    content: "\f42a"
}

.ion-ios-flag:before {
    content: "\f42d"
}

.ion-ios-flag-outline:before {
    content: "\f42c"
}

.ion-ios-flame:before {
    content: "\f42f"
}

.ion-ios-flame-outline:before {
    content: "\f42e"
}

.ion-ios-flask:before {
    content: "\f431"
}

.ion-ios-flask-outline:before {
    content: "\f430"
}

.ion-ios-flower:before {
    content: "\f433"
}

.ion-ios-flower-outline:before {
    content: "\f432"
}

.ion-ios-folder:before {
    content: "\f435"
}

.ion-ios-folder-outline:before {
    content: "\f434"
}

.ion-ios-football:before {
    content: "\f437"
}

.ion-ios-football-outline:before {
    content: "\f436"
}

.ion-ios-game-controller-a:before {
    content: "\f439"
}

.ion-ios-game-controller-a-outline:before {
    content: "\f438"
}

.ion-ios-game-controller-b:before {
    content: "\f43b"
}

.ion-ios-game-controller-b-outline:before {
    content: "\f43a"
}

.ion-ios-gear:before {
    content: "\f43d"
}

.ion-ios-gear-outline:before {
    content: "\f43c"
}

.ion-ios-glasses:before {
    content: "\f43f"
}

.ion-ios-glasses-outline:before {
    content: "\f43e"
}

.ion-ios-grid-view:before {
    content: "\f441"
}

.ion-ios-grid-view-outline:before {
    content: "\f440"
}

.ion-ios-heart:before {
    content: "\f443"
}

.ion-ios-heart-outline:before {
    content: "\f442"
}

.ion-ios-help:before {
    content: "\f446"
}

.ion-ios-help-empty:before {
    content: "\f444"
}

.ion-ios-help-outline:before {
    content: "\f445"
}

.ion-ios-home:before {
    content: "\f448"
}

.ion-ios-home-outline:before {
    content: "\f447"
}

.ion-ios-infinite:before {
    content: "\f44a"
}

.ion-ios-infinite-outline:before {
    content: "\f449"
}

.ion-ios-information:before {
    content: "\f44d"
}

.ion-ios-information-empty:before {
    content: "\f44b"
}

.ion-ios-information-outline:before {
    content: "\f44c"
}

.ion-ios-ionic-outline:before {
    content: "\f44e"
}

.ion-ios-keypad:before {
    content: "\f450"
}

.ion-ios-keypad-outline:before {
    content: "\f44f"
}

.ion-ios-lightbulb:before {
    content: "\f452"
}

.ion-ios-lightbulb-outline:before {
    content: "\f451"
}

.ion-ios-list:before {
    content: "\f454"
}

.ion-ios-list-outline:before {
    content: "\f453"
}

.ion-ios-location:before {
    content: "\f456"
}

.ion-ios-location-outline:before {
    content: "\f455"
}

.ion-ios-locked:before {
    content: "\f458"
}

.ion-ios-locked-outline:before {
    content: "\f457"
}

.ion-ios-loop:before {
    content: "\f45a"
}

.ion-ios-loop-strong:before {
    content: "\f459"
}

.ion-ios-medical:before {
    content: "\f45c"
}

.ion-ios-medical-outline:before {
    content: "\f45b"
}

.ion-ios-medkit:before {
    content: "\f45e"
}

.ion-ios-medkit-outline:before {
    content: "\f45d"
}

.ion-ios-mic:before {
    content: "\f461"
}

.ion-ios-mic-off:before {
    content: "\f45f"
}

.ion-ios-mic-outline:before {
    content: "\f460"
}

.ion-ios-minus:before {
    content: "\f464"
}

.ion-ios-minus-empty:before {
    content: "\f462"
}

.ion-ios-minus-outline:before {
    content: "\f463"
}

.ion-ios-monitor:before {
    content: "\f466"
}

.ion-ios-monitor-outline:before {
    content: "\f465"
}

.ion-ios-moon:before {
    content: "\f468"
}

.ion-ios-moon-outline:before {
    content: "\f467"
}

.ion-ios-more:before {
    content: "\f46a"
}

.ion-ios-more-outline:before {
    content: "\f469"
}

.ion-ios-musical-note:before {
    content: "\f46b"
}

.ion-ios-musical-notes:before {
    content: "\f46c"
}

.ion-ios-navigate:before {
    content: "\f46e"
}

.ion-ios-navigate-outline:before {
    content: "\f46d"
}

.ion-ios-nutrition:before {
    content: "\f470"
}

.ion-ios-nutrition-outline:before {
    content: "\f46f"
}

.ion-ios-paper:before {
    content: "\f472"
}

.ion-ios-paper-outline:before {
    content: "\f471"
}

.ion-ios-paperplane:before {
    content: "\f474"
}

.ion-ios-paperplane-outline:before {
    content: "\f473"
}

.ion-ios-partlysunny:before {
    content: "\f476"
}

.ion-ios-partlysunny-outline:before {
    content: "\f475"
}

.ion-ios-pause:before {
    content: "\f478"
}

.ion-ios-pause-outline:before {
    content: "\f477"
}

.ion-ios-paw:before {
    content: "\f47a"
}

.ion-ios-paw-outline:before {
    content: "\f479"
}

.ion-ios-people:before {
    content: "\f47c"
}

.ion-ios-people-outline:before {
    content: "\f47b"
}

.ion-ios-person:before {
    content: "\f47e"
}

.ion-ios-person-outline:before {
    content: "\f47d"
}

.ion-ios-personadd:before {
    content: "\f480"
}

.ion-ios-personadd-outline:before {
    content: "\f47f"
}

.ion-ios-photos:before {
    content: "\f482"
}

.ion-ios-photos-outline:before {
    content: "\f481"
}

.ion-ios-pie:before {
    content: "\f484"
}

.ion-ios-pie-outline:before {
    content: "\f483"
}

.ion-ios-pint:before {
    content: "\f486"
}

.ion-ios-pint-outline:before {
    content: "\f485"
}

.ion-ios-play:before {
    content: "\f488"
}

.ion-ios-play-outline:before {
    content: "\f487"
}

.ion-ios-plus:before {
    content: "\f48b"
}

.ion-ios-plus-empty:before {
    content: "\f489"
}

.ion-ios-plus-outline:before {
    content: "\f48a"
}

.ion-ios-pricetag:before {
    content: "\f48d"
}

.ion-ios-pricetag-outline:before {
    content: "\f48c"
}

.ion-ios-pricetags:before {
    content: "\f48f"
}

.ion-ios-pricetags-outline:before {
    content: "\f48e"
}

.ion-ios-printer:before {
    content: "\f491"
}

.ion-ios-printer-outline:before {
    content: "\f490"
}

.ion-ios-pulse:before {
    content: "\f493"
}

.ion-ios-pulse-strong:before {
    content: "\f492"
}

.ion-ios-rainy:before {
    content: "\f495"
}

.ion-ios-rainy-outline:before {
    content: "\f494"
}

.ion-ios-recording:before {
    content: "\f497"
}

.ion-ios-recording-outline:before {
    content: "\f496"
}

.ion-ios-redo:before {
    content: "\f499"
}

.ion-ios-redo-outline:before {
    content: "\f498"
}

.ion-ios-refresh:before {
    content: "\f49c"
}

.ion-ios-refresh-empty:before {
    content: "\f49a"
}

.ion-ios-refresh-outline:before {
    content: "\f49b"
}

.ion-ios-reload:before {
    content: "\f49d"
}

.ion-ios-reverse-camera:before {
    content: "\f49f"
}

.ion-ios-reverse-camera-outline:before {
    content: "\f49e"
}

.ion-ios-rewind:before {
    content: "\f4a1"
}

.ion-ios-rewind-outline:before {
    content: "\f4a0"
}

.ion-ios-rose:before {
    content: "\f4a3"
}

.ion-ios-rose-outline:before {
    content: "\f4a2"
}

.ion-ios-search:before {
    content: "\f4a5"
}

.ion-ios-search-strong:before {
    content: "\f4a4"
}

.ion-ios-settings:before {
    content: "\f4a7"
}

.ion-ios-settings-strong:before {
    content: "\f4a6"
}

.ion-ios-shuffle:before {
    content: "\f4a9"
}

.ion-ios-shuffle-strong:before {
    content: "\f4a8"
}

.ion-ios-skipbackward:before {
    content: "\f4ab"
}

.ion-ios-skipbackward-outline:before {
    content: "\f4aa"
}

.ion-ios-skipforward:before {
    content: "\f4ad"
}

.ion-ios-skipforward-outline:before {
    content: "\f4ac"
}

.ion-ios-snowy:before {
    content: "\f4ae"
}

.ion-ios-speedometer:before {
    content: "\f4b0"
}

.ion-ios-speedometer-outline:before {
    content: "\f4af"
}

.ion-ios-star:before {
    content: "\f4b3"
}

.ion-ios-star-half:before {
    content: "\f4b1"
}

.ion-ios-star-outline:before {
    content: "\f4b2"
}

.ion-ios-stopwatch:before {
    content: "\f4b5"
}

.ion-ios-stopwatch-outline:before {
    content: "\f4b4"
}

.ion-ios-sunny:before {
    content: "\f4b7"
}

.ion-ios-sunny-outline:before {
    content: "\f4b6"
}

.ion-ios-telephone:before {
    content: "\f4b9"
}

.ion-ios-telephone-outline:before {
    content: "\f4b8"
}

.ion-ios-tennisball:before {
    content: "\f4bb"
}

.ion-ios-tennisball-outline:before {
    content: "\f4ba"
}

.ion-ios-thunderstorm:before {
    content: "\f4bd"
}

.ion-ios-thunderstorm-outline:before {
    content: "\f4bc"
}

.ion-ios-time:before {
    content: "\f4bf"
}

.ion-ios-time-outline:before {
    content: "\f4be"
}

.ion-ios-timer:before {
    content: "\f4c1"
}

.ion-ios-timer-outline:before {
    content: "\f4c0"
}

.ion-ios-toggle:before {
    content: "\f4c3"
}

.ion-ios-toggle-outline:before {
    content: "\f4c2"
}

.ion-ios-trash:before {
    content: "\f4c5"
}

.ion-ios-trash-outline:before {
    content: "\f4c4"
}

.ion-ios-undo:before {
    content: "\f4c7"
}

.ion-ios-undo-outline:before {
    content: "\f4c6"
}

.ion-ios-unlocked:before {
    content: "\f4c9"
}

.ion-ios-unlocked-outline:before {
    content: "\f4c8"
}

.ion-ios-upload:before {
    content: "\f4cb"
}

.ion-ios-upload-outline:before {
    content: "\f4ca"
}

.ion-ios-videocam:before {
    content: "\f4cd"
}

.ion-ios-videocam-outline:before {
    content: "\f4cc"
}

.ion-ios-volume-high:before {
    content: "\f4ce"
}

.ion-ios-volume-low:before {
    content: "\f4cf"
}

.ion-ios-wineglass:before {
    content: "\f4d1"
}

.ion-ios-wineglass-outline:before {
    content: "\f4d0"
}

.ion-ios-world:before {
    content: "\f4d3"
}

.ion-ios-world-outline:before {
    content: "\f4d2"
}

.ion-ipad:before {
    content: "\f1f9"
}

.ion-iphone:before {
    content: "\f1fa"
}

.ion-ipod:before {
    content: "\f1fb"
}

.ion-jet:before {
    content: "\f295"
}

.ion-key:before {
    content: "\f296"
}

.ion-knife:before {
    content: "\f297"
}

.ion-laptop:before {
    content: "\f1fc"
}

.ion-leaf:before {
    content: "\f1fd"
}

.ion-levels:before {
    content: "\f298"
}

.ion-lightbulb:before {
    content: "\f299"
}

.ion-link:before {
    content: "\f1fe"
}

.ion-load-a:before {
    content: "\f29a"
}

.ion-load-b:before {
    content: "\f29b"
}

.ion-load-c:before {
    content: "\f29c"
}

.ion-load-d:before {
    content: "\f29d"
}

.ion-location:before {
    content: "\f1ff"
}

.ion-lock-combination:before {
    content: "\f4d4"
}

.ion-locked:before {
    content: "\f200"
}

.ion-log-in:before {
    content: "\f29e"
}

.ion-log-out:before {
    content: "\f29f"
}

.ion-loop:before {
    content: "\f201"
}

.ion-magnet:before {
    content: "\f2a0"
}

.ion-male:before {
    content: "\f2a1"
}

.ion-man:before {
    content: "\f202"
}

.ion-map:before {
    content: "\f203"
}

.ion-medkit:before {
    content: "\f2a2"
}

.ion-merge:before {
    content: "\f33f"
}

.ion-mic-a:before {
    content: "\f204"
}

.ion-mic-b:before {
    content: "\f205"
}

.ion-mic-c:before {
    content: "\f206"
}

.ion-minus:before {
    content: "\f209"
}

.ion-minus-circled:before {
    content: "\f207"
}

.ion-minus-round:before {
    content: "\f208"
}

.ion-model-s:before {
    content: "\f2c1"
}

.ion-monitor:before {
    content: "\f20a"
}

.ion-more:before {
    content: "\f20b"
}

.ion-mouse:before {
    content: "\f340"
}

.ion-music-note:before {
    content: "\f20c"
}

.ion-navicon:before {
    content: "\f20e"
}

.ion-navicon-round:before {
    content: "\f20d"
}

.ion-navigate:before {
    content: "\f2a3"
}

.ion-network:before {
    content: "\f341"
}

.ion-no-smoking:before {
    content: "\f2c2"
}

.ion-nuclear:before {
    content: "\f2a4"
}

.ion-outlet:before {
    content: "\f342"
}

.ion-paintbrush:before {
    content: "\f4d5"
}

.ion-paintbucket:before {
    content: "\f4d6"
}

.ion-paper-airplane:before {
    content: "\f2c3"
}

.ion-paperclip:before {
    content: "\f20f"
}

.ion-pause:before {
    content: "\f210"
}

.ion-person:before {
    content: "\f213"
}

.ion-person-add:before {
    content: "\f211"
}

.ion-person-stalker:before {
    content: "\f212"
}

.ion-pie-graph:before {
    content: "\f2a5"
}

.ion-pin:before {
    content: "\f2a6"
}

.ion-pinpoint:before {
    content: "\f2a7"
}

.ion-pizza:before {
    content: "\f2a8"
}

.ion-plane:before {
    content: "\f214"
}

.ion-planet:before {
    content: "\f343"
}

.ion-play:before {
    content: "\f215"
}

.ion-playstation:before {
    content: "\f30a"
}

.ion-plus:before {
    content: "\f218"
}

.ion-plus-circled:before {
    content: "\f216"
}

.ion-plus-round:before {
    content: "\f217"
}

.ion-podium:before {
    content: "\f344"
}

.ion-pound:before {
    content: "\f219"
}

.ion-power:before {
    content: "\f2a9"
}

.ion-pricetag:before {
    content: "\f2aa"
}

.ion-pricetags:before {
    content: "\f2ab"
}

.ion-printer:before {
    content: "\f21a"
}

.ion-pull-request:before {
    content: "\f345"
}

.ion-qr-scanner:before {
    content: "\f346"
}

.ion-quote:before {
    content: "\f347"
}

.ion-radio-waves:before {
    content: "\f2ac"
}

.ion-record:before {
    content: "\f21b"
}

.ion-refresh:before {
    content: "\f21c"
}

.ion-reply:before {
    content: "\f21e"
}

.ion-reply-all:before {
    content: "\f21d"
}

.ion-ribbon-a:before {
    content: "\f348"
}

.ion-ribbon-b:before {
    content: "\f349"
}

.ion-sad:before {
    content: "\f34a"
}

.ion-sad-outline:before {
    content: "\f4d7"
}

.ion-scissors:before {
    content: "\f34b"
}

.ion-search:before {
    content: "\f21f"
}

.ion-settings:before {
    content: "\f2ad"
}

.ion-share:before {
    content: "\f220"
}

.ion-shuffle:before {
    content: "\f221"
}

.ion-skip-backward:before {
    content: "\f222"
}

.ion-skip-forward:before {
    content: "\f223"
}

.ion-social-android:before {
    content: "\f225"
}

.ion-social-android-outline:before {
    content: "\f224"
}

.ion-social-angular:before {
    content: "\f4d9"
}

.ion-social-angular-outline:before {
    content: "\f4d8"
}

.ion-social-apple:before {
    content: "\f227"
}

.ion-social-apple-outline:before {
    content: "\f226"
}

.ion-social-bitcoin:before {
    content: "\f2af"
}

.ion-social-bitcoin-outline:before {
    content: "\f2ae"
}

.ion-social-buffer:before {
    content: "\f229"
}

.ion-social-buffer-outline:before {
    content: "\f228"
}

.ion-social-chrome:before {
    content: "\f4db"
}

.ion-social-chrome-outline:before {
    content: "\f4da"
}

.ion-social-codepen:before {
    content: "\f4dd"
}

.ion-social-codepen-outline:before {
    content: "\f4dc"
}

.ion-social-css3:before {
    content: "\f4df"
}

.ion-social-css3-outline:before {
    content: "\f4de"
}

.ion-social-designernews:before {
    content: "\f22b"
}

.ion-social-designernews-outline:before {
    content: "\f22a"
}

.ion-social-dribbble:before {
    content: "\f22d"
}

.ion-social-dribbble-outline:before {
    content: "\f22c"
}

.ion-social-dropbox:before {
    content: "\f22f"
}

.ion-social-dropbox-outline:before {
    content: "\f22e"
}

.ion-social-euro:before {
    content: "\f4e1"
}

.ion-social-euro-outline:before {
    content: "\f4e0"
}

.ion-social-facebook:before {
    content: "\f231"
}

.ion-social-facebook-outline:before {
    content: "\f230"
}

.ion-social-foursquare:before {
    content: "\f34d"
}

.ion-social-foursquare-outline:before {
    content: "\f34c"
}

.ion-social-freebsd-devil:before {
    content: "\f2c4"
}

.ion-social-github:before {
    content: "\f233"
}

.ion-social-github-outline:before {
    content: "\f232"
}

.ion-social-google:before {
    content: "\f34f"
}

.ion-social-google-outline:before {
    content: "\f34e"
}

.ion-social-googleplus:before {
    content: "\f235"
}

.ion-social-googleplus-outline:before {
    content: "\f234"
}

.ion-social-hackernews:before {
    content: "\f237"
}

.ion-social-hackernews-outline:before {
    content: "\f236"
}

.ion-social-html5:before {
    content: "\f4e3"
}

.ion-social-html5-outline:before {
    content: "\f4e2"
}

.ion-social-instagram:before {
    content: "\f351"
}

.ion-social-instagram-outline:before {
    content: "\f350"
}

.ion-social-javascript:before {
    content: "\f4e5"
}

.ion-social-javascript-outline:before {
    content: "\f4e4"
}

.ion-social-linkedin:before {
    content: "\f239"
}

.ion-social-linkedin-outline:before {
    content: "\f238"
}

.ion-social-markdown:before {
    content: "\f4e6"
}

.ion-social-nodejs:before {
    content: "\f4e7"
}

.ion-social-octocat:before {
    content: "\f4e8"
}

.ion-social-pinterest:before {
    content: "\f2b1"
}

.ion-social-pinterest-outline:before {
    content: "\f2b0"
}

.ion-social-python:before {
    content: "\f4e9"
}

.ion-social-reddit:before {
    content: "\f23b"
}

.ion-social-reddit-outline:before {
    content: "\f23a"
}

.ion-social-rss:before {
    content: "\f23d"
}

.ion-social-rss-outline:before {
    content: "\f23c"
}

.ion-social-sass:before {
    content: "\f4ea"
}

.ion-social-skype:before {
    content: "\f23f"
}

.ion-social-skype-outline:before {
    content: "\f23e"
}

.ion-social-snapchat:before {
    content: "\f4ec"
}

.ion-social-snapchat-outline:before {
    content: "\f4eb"
}

.ion-social-tumblr:before {
    content: "\f241"
}

.ion-social-tumblr-outline:before {
    content: "\f240"
}

.ion-social-tux:before {
    content: "\f2c5"
}

.ion-social-twitch:before {
    content: "\f4ee"
}

.ion-social-twitch-outline:before {
    content: "\f4ed"
}

.ion-social-twitter:before {
    content: "\f243"
}

.ion-social-twitter-outline:before {
    content: "\f242"
}

.ion-social-usd:before {
    content: "\f353"
}

.ion-social-usd-outline:before {
    content: "\f352"
}

.ion-social-vimeo:before {
    content: "\f245"
}

.ion-social-vimeo-outline:before {
    content: "\f244"
}

.ion-social-whatsapp:before {
    content: "\f4f0"
}

.ion-social-whatsapp-outline:before {
    content: "\f4ef"
}

.ion-social-windows:before {
    content: "\f247"
}

.ion-social-windows-outline:before {
    content: "\f246"
}

.ion-social-wordpress:before {
    content: "\f249"
}

.ion-social-wordpress-outline:before {
    content: "\f248"
}

.ion-social-yahoo:before {
    content: "\f24b"
}

.ion-social-yahoo-outline:before {
    content: "\f24a"
}

.ion-social-yen:before {
    content: "\f4f2"
}

.ion-social-yen-outline:before {
    content: "\f4f1"
}

.ion-social-youtube:before {
    content: "\f24d"
}

.ion-social-youtube-outline:before {
    content: "\f24c"
}

.ion-soup-can:before {
    content: "\f4f4"
}

.ion-soup-can-outline:before {
    content: "\f4f3"
}

.ion-speakerphone:before {
    content: "\f2b2"
}

.ion-speedometer:before {
    content: "\f2b3"
}

.ion-spoon:before {
    content: "\f2b4"
}

.ion-star:before {
    content: "\f24e"
}

.ion-stats-bars:before {
    content: "\f2b5"
}

.ion-steam:before {
    content: "\f30b"
}

.ion-stop:before {
    content: "\f24f"
}

.ion-thermometer:before {
    content: "\f2b6"
}

.ion-thumbsdown:before {
    content: "\f250"
}

.ion-thumbsup:before {
    content: "\f251"
}

.ion-toggle:before {
    content: "\f355"
}

.ion-toggle-filled:before {
    content: "\f354"
}

.ion-transgender:before {
    content: "\f4f5"
}

.ion-trash-a:before {
    content: "\f252"
}

.ion-trash-b:before {
    content: "\f253"
}

.ion-trophy:before {
    content: "\f356"
}

.ion-tshirt:before {
    content: "\f4f7"
}

.ion-tshirt-outline:before {
    content: "\f4f6"
}

.ion-umbrella:before {
    content: "\f2b7"
}

.ion-university:before {
    content: "\f357"
}

.ion-unlocked:before {
    content: "\f254"
}

.ion-upload:before {
    content: "\f255"
}

.ion-usb:before {
    content: "\f2b8"
}

.ion-videocamera:before {
    content: "\f256"
}

.ion-volume-high:before {
    content: "\f257"
}

.ion-volume-low:before {
    content: "\f258"
}

.ion-volume-medium:before {
    content: "\f259"
}

.ion-volume-mute:before {
    content: "\f25a"
}

.ion-wand:before {
    content: "\f358"
}

.ion-waterdrop:before {
    content: "\f25b"
}

.ion-wifi:before {
    content: "\f25c"
}

.ion-wineglass:before {
    content: "\f2b9"
}

.ion-woman:before {
    content: "\f25d"
}

.ion-wrench:before {
    content: "\f2ba"
}

.ion-xbox:before {
    content: "\f30c"
}

.select2-container {
    box-sizing: border-box;
    display: inline-block;
    margin: 0;
    position: relative;
    vertical-align: middle
}

.select2-container .select2-selection--single {
    box-sizing: border-box;
    cursor: pointer;
    display: block;
    height: 28px;
    user-select: none;
    -webkit-user-select: none
}

.select2-container .select2-selection--single .select2-selection__rendered {
    display: block;
    padding-left: 8px;
    padding-right: 20px;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap
}

.select2-container .select2-selection--single .select2-selection__clear {
    position: relative
}

.select2-container[dir=rtl] .select2-selection--single .select2-selection__rendered {
    padding-right: 8px;
    padding-left: 20px
}

.select2-container .select2-selection--multiple {
    box-sizing: border-box;
    cursor: pointer;
    display: block;
    min-height: 32px;
    user-select: none;
    -webkit-user-select: none
}

.select2-container .select2-selection--multiple .select2-selection__rendered {
    display: inline-block;
    overflow: hidden;
    padding-left: 8px;
    text-overflow: ellipsis;
    white-space: nowrap
}

.select2-container .select2-search--inline {
    float: left
}

.select2-container .select2-search--inline .select2-search__field {
    box-sizing: border-box;
    border: none;
    font-size: 100%;
    margin-top: 5px;
    padding: 0
}

.select2-container .select2-search--inline .select2-search__field::-webkit-search-cancel-button {
    -webkit-appearance: none
}

.select2-dropdown {
    background-color: #fff;
    border: 1px solid #aaa;
    border-radius: 4px;
    box-sizing: border-box;
    display: block;
    position: absolute;
    left: -100000px;
    width: 100%;
    z-index: 1051
}

.select2-results {
    display: block
}

.select2-results__options {
    list-style: none;
    margin: 0;
    padding: 0
}

.select2-results__option {
    padding: 6px;
    user-select: none;
    -webkit-user-select: none
}

.select2-results__option[aria-selected] {
    cursor: pointer
}

.select2-container--open .select2-dropdown {
    left: 0
}

.select2-container--open .select2-dropdown--above {
    border-bottom: none;
    border-bottom-left-radius: 0;
    border-bottom-right-radius: 0
}

.select2-container--open .select2-dropdown--below {
    border-top: none;
    border-top-left-radius: 0;
    border-top-right-radius: 0
}

.select2-search--dropdown {
    display: block;
    padding: 4px
}

.select2-search--dropdown .select2-search__field {
    padding: 4px;
    width: 100%;
    box-sizing: border-box
}

.select2-search--dropdown .select2-search__field::-webkit-search-cancel-button {
    -webkit-appearance: none
}

.select2-search--dropdown.select2-search--hide {
    display: none
}

.select2-close-mask {
    border: 0;
    margin: 0;
    padding: 0;
    display: block;
    position: fixed;
    left: 0;
    top: 0;
    min-height: 100%;
    min-width: 100%;
    height: auto;
    width: auto;
    opacity: 0;
    z-index: 99;
    background-color: #fff
}

.select2-hidden-accessible {
    border: 0 !important;
    clip: rect(0 0 0 0) !important;
    height: 1px !important;
    margin: -1px !important;
    overflow: hidden !important;
    padding: 0 !important;
    position: absolute !important;
    width: 1px !important
}

.select2-container--default .select2-selection--single {
    background-color: #fff;
    border: 1px solid #aaa;
    border-radius: 4px
}

.select2-container--default .select2-selection--single .select2-selection__rendered {
    color: #444;
    line-height: 28px
}

.select2-container--default .select2-selection--single .select2-selection__clear {
    cursor: pointer;
    float: right;
    font-weight: 700
}

.select2-container--default .select2-selection--single .select2-selection__placeholder {
    color: #999
}

.select2-container--default .select2-selection--single .select2-selection__arrow {
    height: 26px;
    position: absolute;
    top: 1px;
    right: 1px;
    width: 20px
}

.select2-container--default .select2-selection--single .select2-selection__arrow b {
    border-color: #888 transparent transparent transparent;
    border-style: solid;
    border-width: 5px 4px 0 4px;
    height: 0;
    left: 50%;
    margin-left: -4px;
    margin-top: -2px;
    position: absolute;
    top: 50%;
    width: 0
}

.select2-container--default[dir=rtl] .select2-selection--single .select2-selection__clear {
    float: left
}

.select2-container--default[dir=rtl] .select2-selection--single .select2-selection__arrow {
    left: 1px;
    right: auto
}

.select2-container--default.select2-container--disabled .select2-selection--single {
    background-color: #eee;
    cursor: default
}

.select2-container--default.select2-container--disabled .select2-selection--single .select2-selection__clear {
    display: none
}

.select2-container--default.select2-container--open .select2-selection--single .select2-selection__arrow b {
    border-color: transparent transparent #888 transparent;
    border-width: 0 4px 5px 4px
}

.select2-container--default .select2-selection--multiple {
    background-color: #fff;
    border: 1px solid #aaa;
    border-radius: 4px;
    cursor: text
}

.select2-container--default .select2-selection--multiple .select2-selection__rendered {
    box-sizing: border-box;
    list-style: none;
    margin: 0;
    padding: 0 5px;
    width: 100%
}

.select2-container--default .select2-selection--multiple .select2-selection__rendered li {
    list-style: none
}

.select2-container--default .select2-selection--multiple .select2-selection__placeholder {
    color: #999;
    margin-top: 5px;
    float: left
}

.select2-container--default .select2-selection--multiple .select2-selection__clear {
    cursor: pointer;
    float: right;
    font-weight: 700;
    margin-top: 5px;
    margin-right: 10px
}

.select2-container--default .select2-selection--multiple .select2-selection__choice {
    background-color: #e4e4e4;
    border: 1px solid #aaa;
    border-radius: 4px;
    cursor: default;
    float: left;
    margin-right: 5px;
    margin-top: 5px;
    padding: 0 5px
}

.select2-container--default .select2-selection--multiple .select2-selection__choice__remove {
    color: #999;
    cursor: pointer;
    display: inline-block;
    font-weight: 700;
    margin-right: 2px
}

.select2-container--default .select2-selection--multiple .select2-selection__choice__remove:hover {
    color: #333
}

.select2-container--default[dir=rtl] .select2-selection--multiple .select2-search--inline,
.select2-container--default[dir=rtl] .select2-selection--multiple .select2-selection__choice,
.select2-container--default[dir=rtl] .select2-selection--multiple .select2-selection__placeholder {
    float: right
}

.select2-container--default[dir=rtl] .select2-selection--multiple .select2-selection__choice {
    margin-left: 5px;
    margin-right: auto
}

.select2-container--default[dir=rtl] .select2-selection--multiple .select2-selection__choice__remove {
    margin-left: 2px;
    margin-right: auto
}

.select2-container--default.select2-container--focus .select2-selection--multiple {
    border: solid #000 1px;
    outline: 0
}

.select2-container--default.select2-container--disabled .select2-selection--multiple {
    background-color: #eee;
    cursor: default
}

.select2-container--default.select2-container--disabled .select2-selection__choice__remove {
    display: none
}

.select2-container--default.select2-container--open.select2-container--above .select2-selection--multiple,
.select2-container--default.select2-container--open.select2-container--above .select2-selection--single {
    border-top-left-radius: 0;
    border-top-right-radius: 0
}

.select2-container--default.select2-container--open.select2-container--below .select2-selection--multiple,
.select2-container--default.select2-container--open.select2-container--below .select2-selection--single {
    border-bottom-left-radius: 0;
    border-bottom-right-radius: 0
}

.select2-container--default .select2-search--dropdown .select2-search__field {
    border: 1px solid #aaa
}

.select2-container--default .select2-search--inline .select2-search__field {
    background: 0 0;
    border: none;
    outline: 0;
    box-shadow: none;
    -webkit-appearance: textfield
}

.select2-container--default .select2-results>.select2-results__options {
    max-height: 200px;
    overflow-y: auto
}

.select2-container--default .select2-results__option[role=group] {
    padding: 0
}

.select2-container--default .select2-results__option[aria-disabled=true] {
    color: #999
}

.select2-container--default .select2-results__option[aria-selected=true] {
    background-color: #ddd
}

.select2-container--default .select2-results__option .select2-results__option {
    padding-left: 1em
}

.select2-container--default .select2-results__option .select2-results__option .select2-results__group {
    padding-left: 0
}

.select2-container--default .select2-results__option .select2-results__option .select2-results__option {
    margin-left: -1em;
    padding-left: 2em
}

.select2-container--default .select2-results__option .select2-results__option .select2-results__option .select2-results__option {
    margin-left: -2em;
    padding-left: 3em
}

.select2-container--default .select2-results__option .select2-results__option .select2-results__option .select2-results__option .select2-results__option {
    margin-left: -3em;
    padding-left: 4em
}

.select2-container--default .select2-results__option .select2-results__option .select2-results__option .select2-results__option .select2-results__option .select2-results__option {
    margin-left: -4em;
    padding-left: 5em
}

.select2-container--default .select2-results__option .select2-results__option .select2-results__option .select2-results__option .select2-results__option .select2-results__option .select2-results__option {
    margin-left: -5em;
    padding-left: 6em
}

.select2-container--default .select2-results__option--highlighted[aria-selected] {
    background-color: #5897fb;
    color: #fff
}

.select2-container--default .select2-results__group {
    cursor: default;
    display: block;
    padding: 6px
}

.select2-container--classic .select2-selection--single {
    background-color: #f7f7f7;
    border: 1px solid #aaa;
    border-radius: 4px;
    outline: 0;
    background-image: -webkit-linear-gradient(top, #fff 50%, #eee 100%);
    background-image: -o-linear-gradient(top, #fff 50%, #eee 100%);
    background-image: linear-gradient(to bottom, #fff 50%, #eee 100%);
    background-repeat: repeat-x
}

.select2-container--classic .select2-selection--single:focus {
    border: 1px solid #5897fb
}

.select2-container--classic .select2-selection--single .select2-selection__rendered {
    color: #444;
    line-height: 28px
}

.select2-container--classic .select2-selection--single .select2-selection__clear {
    cursor: pointer;
    float: right;
    font-weight: 700;
    margin-right: 10px
}

.select2-container--classic .select2-selection--single .select2-selection__placeholder {
    color: #999
}

.select2-container--classic .select2-selection--single .select2-selection__arrow {
    background-color: #ddd;
    border: none;
    border-left: 1px solid #aaa;
    border-top-right-radius: 4px;
    border-bottom-right-radius: 4px;
    height: 26px;
    position: absolute;
    top: 1px;
    right: 1px;
    width: 20px;
    background-image: -webkit-linear-gradient(top, #eee 50%, #ccc 100%);
    background-image: -o-linear-gradient(top, #eee 50%, #ccc 100%);
    background-image: linear-gradient(to bottom, #eee 50%, #ccc 100%);
    background-repeat: repeat-x
}

.select2-container--classic .select2-selection--single .select2-selection__arrow b {
    border-color: #888 transparent transparent transparent;
    border-style: solid;
    border-width: 5px 4px 0 4px;
    height: 0;
    left: 50%;
    margin-left: -4px;
    margin-top: -2px;
    position: absolute;
    top: 50%;
    width: 0
}

.select2-container--classic[dir=rtl] .select2-selection--single .select2-selection__clear {
    float: left
}

.select2-container--classic[dir=rtl] .select2-selection--single .select2-selection__arrow {
    border: none;
    border-right: 1px solid #aaa;
    border-radius: 0;
    border-top-left-radius: 4px;
    border-bottom-left-radius: 4px;
    left: 1px;
    right: auto
}

.select2-container--classic.select2-container--open .select2-selection--single {
    border: 1px solid #5897fb
}

.select2-container--classic.select2-container--open .select2-selection--single .select2-selection__arrow {
    background: 0 0;
    border: none
}

.select2-container--classic.select2-container--open .select2-selection--single .select2-selection__arrow b {
    border-color: transparent transparent #888 transparent;
    border-width: 0 4px 5px 4px
}

.select2-container--classic.select2-container--open.select2-container--above .select2-selection--single {
    border-top: none;
    border-top-left-radius: 0;
    border-top-right-radius: 0;
    background-image: -webkit-linear-gradient(top, #fff 0, #eee 50%);
    background-image: -o-linear-gradient(top, #fff 0, #eee 50%);
    background-image: linear-gradient(to bottom, #fff 0, #eee 50%);
    background-repeat: repeat-x
}

.select2-container--classic.select2-container--open.select2-container--below .select2-selection--single {
    border-bottom: none;
    border-bottom-left-radius: 0;
    border-bottom-right-radius: 0;
    background-image: -webkit-linear-gradient(top, #eee 50%, #fff 100%);
    background-image: -o-linear-gradient(top, #eee 50%, #fff 100%);
    background-image: linear-gradient(to bottom, #eee 50%, #fff 100%);
    background-repeat: repeat-x
}

.select2-container--classic .select2-selection--multiple {
    background-color: #fff;
    border: 1px solid #aaa;
    border-radius: 4px;
    cursor: text;
    outline: 0
}

.select2-container--classic .select2-selection--multiple:focus {
    border: 1px solid #5897fb
}

.select2-container--classic .select2-selection--multiple .select2-selection__rendered {
    list-style: none;
    margin: 0;
    padding: 0 5px
}

.select2-container--classic .select2-selection--multiple .select2-selection__clear {
    display: none
}

.select2-container--classic .select2-selection--multiple .select2-selection__choice {
    background-color: #e4e4e4;
    border: 1px solid #aaa;
    border-radius: 4px;
    cursor: default;
    float: left;
    margin-right: 5px;
    margin-top: 5px;
    padding: 0 5px
}

.select2-container--classic .select2-selection--multiple .select2-selection__choice__remove {
    color: #888;
    cursor: pointer;
    display: inline-block;
    font-weight: 700;
    margin-right: 2px
}

.select2-container--classic .select2-selection--multiple .select2-selection__choice__remove:hover {
    color: #555
}

.select2-container--classic[dir=rtl] .select2-selection--multiple .select2-selection__choice {
    float: right
}

.select2-container--classic[dir=rtl] .select2-selection--multiple .select2-selection__choice {
    margin-left: 5px;
    margin-right: auto
}

.select2-container--classic[dir=rtl] .select2-selection--multiple .select2-selection__choice__remove {
    margin-left: 2px;
    margin-right: auto
}

.select2-container--classic.select2-container--open .select2-selection--multiple {
    border: 1px solid #5897fb
}

.select2-container--classic.select2-container--open.select2-container--above .select2-selection--multiple {
    border-top: none;
    border-top-left-radius: 0;
    border-top-right-radius: 0
}

.select2-container--classic.select2-container--open.select2-container--below .select2-selection--multiple {
    border-bottom: none;
    border-bottom-left-radius: 0;
    border-bottom-right-radius: 0
}

.select2-container--classic .select2-search--dropdown .select2-search__field {
    border: 1px solid #aaa;
    outline: 0
}

.select2-container--classic .select2-search--inline .select2-search__field {
    outline: 0;
    box-shadow: none
}

.select2-container--classic .select2-dropdown {
    background-color: #fff;
    border: 1px solid transparent
}

.select2-container--classic .select2-dropdown--above {
    border-bottom: none
}

.select2-container--classic .select2-dropdown--below {
    border-top: none
}

.select2-container--classic .select2-results>.select2-results__options {
    max-height: 200px;
    overflow-y: auto
}

.select2-container--classic .select2-results__option[role=group] {
    padding: 0
}

.select2-container--classic .select2-results__option[aria-disabled=true] {
    color: grey
}

.select2-container--classic .select2-results__option--highlighted[aria-selected] {
    background-color: #3875d7;
    color: #fff
}

.select2-container--classic .select2-results__group {
    cursor: default;
    display: block;
    padding: 6px
}

.select2-container--classic.select2-container--open .select2-dropdown {
    border-color: #5897fb
}

/*!
 * AdminLTE v2.4.18
 * 
 *   Author:  Colorlib
 *   Support: <https://github.com/ColorlibHQ/AdminLTE/issues>
 *   Repository: git://github.com/ColorlibHQ/AdminLTE.git
 *   License: MIT <http://opensource.org/licenses/MIT>
 */

body,
html {
    height: 100%
}

.layout-boxed body,
.layout-boxed html {
    height: 100%
}

body {
    font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, sans-serif;
    font-weight: 400;
    overflow-x: hidden;
    overflow-y: auto
}

.wrapper {
    height: 100%;
    position: relative;
    overflow-x: hidden;
    overflow-y: auto
}

.wrapper:after,
.wrapper:before {
    content: " ";
    display: table
}

.wrapper:after {
    clear: both
}

.layout-boxed .wrapper {
    max-width: 1250px;
    margin: 0 auto;
    min-height: 100%;
    box-shadow: 0 0 8px rgba(0, 0, 0, .5);
    position: relative
}

.layout-boxed {
    background-color: #f9fafc
}

.content-wrapper,
.main-footer {
    -webkit-transition: -webkit-transform .3s ease-in-out, margin .3s ease-in-out;
    -moz-transition: -moz-transform .3s ease-in-out, margin .3s ease-in-out;
    -o-transition: -o-transform .3s ease-in-out, margin .3s ease-in-out;
    transition: transform .3s ease-in-out, margin .3s ease-in-out;
    margin-left: 230px;
    z-index: 820
}

.layout-top-nav .content-wrapper,
.layout-top-nav .main-footer {
    margin-left: 0
}

@media (max-width:767px) {
    .content-wrapper,
    .main-footer {
        margin-left: 0
    }
}

@media (min-width:768px) {
    .sidebar-collapse .content-wrapper,
    .sidebar-collapse .main-footer {
        margin-left: 0
    }
}

@media (max-width:767px) {
    .sidebar-open .content-wrapper,
    .sidebar-open .main-footer {
        -webkit-transform: translate(230px, 0);
        -ms-transform: translate(230px, 0);
        -o-transform: translate(230px, 0);
        transform: translate(230px, 0)
    }
}

.content-wrapper {
    min-height: calc(100vh - 101px);
    background-color: #ecf0f5;
    z-index: 800
}

@media (max-width:767px) {
    .content-wrapper {
        min-height: calc(100vh - 151px)
    }
}

.main-footer {
    background: #fff;
    padding: 15px;
    color: #444;
    border-top: 1px solid #d2d6de
}

.fixed .left-side,
.fixed .main-header,
.fixed .main-sidebar {
    position: fixed
}

.fixed .main-header {
    top: 0;
    right: 0;
    left: 0
}

.fixed .content-wrapper,
.fixed .right-side {
    padding-top: 50px
}

@media (max-width:767px) {
    .fixed .content-wrapper,
    .fixed .right-side {
        padding-top: 100px
    }
}

.fixed.layout-boxed .wrapper {
    max-width: 100%
}

.fixed .wrapper {
    overflow: hidden
}

.hold-transition .content-wrapper,
.hold-transition .left-side,
.hold-transition .main-footer,
.hold-transition .main-header .logo,
.hold-transition .main-header .navbar,
.hold-transition .main-sidebar,
.hold-transition .menu-open .fa-angle-left,
.hold-transition .right-side {
    -webkit-transition: none;
    -o-transition: none;
    transition: none
}

.content {
    min-height: 250px;
    padding: 15px;
    margin-right: auto;
    margin-left: auto;
    padding-left: 15px;
    padding-right: 15px
}

.h1,
.h2,
.h3,
.h4,
.h5,
.h6,
h1,
h2,
h3,
h4,
h5,
h6 {
    font-family: 'Source Sans Pro', sans-serif
}

a {
    color: #3c8dbc
}

a:active,
a:focus,
a:hover {
    outline: 0;
    text-decoration: none;
    color: #72afd2
}

.page-header {
    margin: 10px 0 20px 0;
    font-size: 22px
}

.page-header>small {
    color: #666;
    display: block;
    margin-top: 5px
}

.main-header {
    position: relative;
    max-height: 100px;
    z-index: 1030
}

.main-header .navbar {
    -webkit-transition: margin-left .3s ease-in-out;
    -o-transition: margin-left .3s ease-in-out;
    transition: margin-left .3s ease-in-out;
    margin-bottom: 0;
    margin-left: 230px;
    border: none;
    min-height: 50px;
    border-radius: 0
}

.layout-top-nav .main-header .navbar {
    margin-left: 0
}

.main-header #navbar-search-input.form-control {
    background: rgba(255, 255, 255, .2);
    border-color: transparent
}

.main-header #navbar-search-input.form-control:active,
.main-header #navbar-search-input.form-control:focus {
    border-color: rgba(0, 0, 0, .1);
    background: rgba(255, 255, 255, .9)
}

.main-header #navbar-search-input.form-control::-moz-placeholder {
    color: #ccc;
    opacity: 1
}

.main-header #navbar-search-input.form-control:-ms-input-placeholder {
    color: #ccc
}

.main-header #navbar-search-input.form-control::-webkit-input-placeholder {
    color: #ccc
}

.main-header .navbar-custom-menu,
.main-header .navbar-right {
    float: right
}

@media (max-width:991px) {
    .main-header .navbar-right a {
        color: inherit;
        background: 0 0
    }
}

@media (max-width:767px) {
    .main-header .navbar-right {
        float: none
    }
    .navbar-collapse .main-header .navbar-right {
        margin: 7.5px -15px
    }
    .main-header .navbar-right>li {
        color: inherit;
        border: 0
    }
}

.main-header .sidebar-toggle {
    float: left;
    background-color: transparent;
    background-image: none;
    padding: 15px 15px;
    font-family: fontAwesome
}

.main-header .sidebar-toggle:before {
    content: "\f0c9"
}

.main-header .sidebar-toggle:hover {
    color: #fff
}

.main-header .sidebar-toggle:active,
.main-header .sidebar-toggle:focus {
    background: 0 0
}

.main-header .sidebar-toggle.fa5 {
    font-family: "Font Awesome\ 5 Free"
}

.main-header .sidebar-toggle.fa5:before {
    content: "\f0c9";
    font-weight: 900
}

.main-header .sidebar-toggle .icon-bar {
    display: none
}

.main-header .navbar .nav>li.user>a>.fa,
.main-header .navbar .nav>li.user>a>.glyphicon,
.main-header .navbar .nav>li.user>a>.ion {
    margin-right: 5px
}

.main-header .navbar .nav>li>a>.label {
    position: absolute;
    top: 9px;
    right: 7px;
    text-align: center;
    font-size: 9px;
    padding: 2px 3px;
    line-height: .9
}

.main-header .logo {
    -webkit-transition: width .3s ease-in-out;
    -o-transition: width .3s ease-in-out;
    transition: width .3s ease-in-out;
    display: block;
    float: left;
    height: 50px;
    font-size: 20px;
    line-height: 50px;
    text-align: center;
    width: 230px;
    font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
    padding: 0 15px;
    font-weight: 300;
    overflow: hidden
}

.main-header .logo img {
    padding: 4px;
    object-fit: contain;
    margin: 0 auto
}

.main-header .logo .logo-lg {
    display: block
}

.main-header .logo .logo-lg img {
    max-width: 200px;
    max-height: 50px
}

.main-header .logo .logo-lg .brandlogo-image {
    margin-top: 8px;
    margin-right: 10px;
    margin-left: -5px
}

.main-header .logo .logo-mini {
    display: none
}

.main-header .logo .logo-mini img {
    max-width: 50px;
    max-height: 50px
}

.main-header .logo .logo-mini .brandlogo-image {
    margin-top: 8px;
    margin-right: 10px;
    margin-left: 10px
}

.main-header .logo .brandlogo-image {
    float: left;
    height: 34px;
    width: auto
}

.main-header .navbar-brand {
    color: #fff
}

.content-header {
    position: relative;
    padding: 15px 15px 0 15px
}

.content-header>h1 {
    margin: 0;
    font-size: 24px
}

.content-header>h1>small {
    font-size: 15px;
    display: inline-block;
    padding-left: 4px;
    font-weight: 300
}

.content-header>.breadcrumb {
    float: right;
    background: 0 0;
    margin-top: 0;
    margin-bottom: 0;
    font-size: 12px;
    padding: 7px 5px;
    position: absolute;
    top: 15px;
    right: 10px;
    border-radius: 2px
}

.content-header>.breadcrumb>li>a {
    color: #444;
    text-decoration: none;
    display: inline-block
}

.content-header>.breadcrumb>li>a>.fa,
.content-header>.breadcrumb>li>a>.glyphicon,
.content-header>.breadcrumb>li>a>.ion {
    margin-right: 5px
}

.content-header>.breadcrumb>li+li:before {
    content: '>\00a0'
}

@media (max-width:991px) {
    .content-header>.breadcrumb {
        position: relative;
        margin-top: 5px;
        top: 0;
        right: 0;
        float: none;
        background: #d2d6de;
        padding-left: 10px
    }
    .content-header>.breadcrumb li:before {
        color: #97a0b3
    }
}

.navbar-toggle {
    color: #fff;
    border: 0;
    margin: 0;
    padding: 15px 15px
}

@media (max-width:991px) {
    .navbar-custom-menu .navbar-nav>li {
        float: left
    }
    .navbar-custom-menu .navbar-nav {
        margin: 0;
        float: left
    }
    .navbar-custom-menu .navbar-nav>li>a {
        padding-top: 15px;
        padding-bottom: 15px;
        line-height: 20px
    }
}

@media (max-width:767px) {
    .main-header {
        position: relative
    }
    .main-header .logo,
    .main-header .navbar {
        width: 100%;
        float: none
    }
    .main-header .navbar {
        margin: 0
    }
    .main-header .navbar-custom-menu {
        float: right
    }
}

@media (max-width:991px) {
    .navbar-collapse.pull-left {
        float: none !important
    }
    .navbar-collapse.pull-left+.navbar-custom-menu {
        display: block;
        position: absolute;
        top: 0;
        right: 40px
    }
}

.main-sidebar {
    position: absolute;
    top: 0;
    left: 0;
    padding-top: 50px;
    min-height: 100%;
    width: 230px;
    z-index: 810;
    -webkit-transition: -webkit-transform .3s ease-in-out, width .3s ease-in-out;
    -moz-transition: -moz-transform .3s ease-in-out, width .3s ease-in-out;
    -o-transition: -o-transform .3s ease-in-out, width .3s ease-in-out;
    transition: transform .3s ease-in-out, width .3s ease-in-out
}

@media (max-width:767px) {
    .main-sidebar {
        padding-top: 100px
    }
}

@media (max-width:767px) {
    .main-sidebar {
        -webkit-transform: translate(-230px, 0);
        -ms-transform: translate(-230px, 0);
        -o-transform: translate(-230px, 0);
        transform: translate(-230px, 0)
    }
}

@media (min-width:768px) {
    .sidebar-collapse .main-sidebar {
        -webkit-transform: translate(-230px, 0);
        -ms-transform: translate(-230px, 0);
        -o-transform: translate(-230px, 0);
        transform: translate(-230px, 0)
    }
}

@media (max-width:767px) {
    .sidebar-open .main-sidebar {
        -webkit-transform: translate(0, 0);
        -ms-transform: translate(0, 0);
        -o-transform: translate(0, 0);
        transform: translate(0, 0)
    }
}

.sidebar {
    padding-bottom: 10px
}

.sidebar-form input:focus {
    border-color: transparent
}

.user-panel {
    position: relative;
    width: 100%;
    padding: 10px;
    overflow: hidden
}

.user-panel:after,
.user-panel:before {
    content: " ";
    display: table
}

.user-panel:after {
    clear: both
}

.user-panel>.image>img {
    width: 100%;
    max-width: 45px;
    height: auto
}

.user-panel>.info {
    padding: 5px 5px 5px 15px;
    line-height: 1;
    position: absolute;
    left: 55px
}

.user-panel>.info>p {
    font-weight: 600;
    margin-bottom: 9px
}

.user-panel>.info>a {
    text-decoration: none;
    padding-right: 5px;
    margin-top: 3px;
    font-size: 11px
}

.user-panel>.info>a>.fa,
.user-panel>.info>a>.glyphicon,
.user-panel>.info>a>.ion {
    margin-right: 3px
}

.sidebar-menu {
    list-style: none;
    margin: 0;
    padding: 0
}

.sidebar-menu>li {
    position: relative;
    margin: 0;
    padding: 0
}

.sidebar-menu>li>a {
    padding: 12px 5px 12px 15px;
    display: block
}

.sidebar-menu>li>a>.fa,
.sidebar-menu>li>a>.glyphicon,
.sidebar-menu>li>a>.ion {
    width: 20px
}

.sidebar-menu>li .badge,
.sidebar-menu>li .label {
    margin-right: 5px
}

.sidebar-menu>li .badge {
    margin-top: 3px
}

.sidebar-menu li.header {
    padding: 10px 25px 10px 15px;
    font-size: 12px
}

.sidebar-menu li>a>.fa-angle-left,
.sidebar-menu li>a>.pull-right-container>.fa-angle-left {
    width: auto;
    height: auto;
    padding: 0;
    margin-right: 10px;
    -webkit-transition: transform .5s ease;
    -o-transition: transform .5s ease;
    transition: transform .5s ease
}

.sidebar-menu li>a>.fa-angle-left {
    position: absolute;
    top: 50%;
    right: 10px;
    margin-top: -8px
}

.sidebar-menu .menu-open>a>.fa-angle-left,
.sidebar-menu .menu-open>a>.pull-right-container>.fa-angle-left {
    -webkit-transform: rotate(-90deg);
    -ms-transform: rotate(-90deg);
    -o-transform: rotate(-90deg);
    transform: rotate(-90deg)
}

.sidebar-menu .active>.treeview-menu {
    display: block
}

@media (min-width:768px) {
    .sidebar-mini.sidebar-collapse .content-wrapper,
    .sidebar-mini.sidebar-collapse .main-footer,
    .sidebar-mini.sidebar-collapse .right-side {
        margin-left: 50px !important;
        z-index: 840
    }
    .sidebar-mini.sidebar-collapse .main-sidebar {
        -webkit-transform: translate(0, 0);
        -ms-transform: translate(0, 0);
        -o-transform: translate(0, 0);
        transform: translate(0, 0);
        width: 50px !important;
        z-index: 850
    }
    .sidebar-mini.sidebar-collapse .sidebar-menu>li {
        position: relative
    }
    .sidebar-mini.sidebar-collapse .sidebar-menu>li>a {
        margin-right: 0
    }
    .sidebar-mini.sidebar-collapse .sidebar-menu>li>a>span {
        border-top-right-radius: 4px
    }
    .sidebar-mini.sidebar-collapse .sidebar-menu>li:not(.treeview)>a>span {
        border-bottom-right-radius: 4px
    }
    .sidebar-mini.sidebar-collapse .sidebar-menu>li>.treeview-menu {
        padding-top: 5px;
        padding-bottom: 5px;
        border-bottom-right-radius: 4px
    }
    .sidebar-mini.sidebar-collapse .main-sidebar .user-panel>.info,
    .sidebar-mini.sidebar-collapse .sidebar-form,
    .sidebar-mini.sidebar-collapse .sidebar-menu li.header,
    .sidebar-mini.sidebar-collapse .sidebar-menu>li>.treeview-menu,
    .sidebar-mini.sidebar-collapse .sidebar-menu>li>a>.pull-right,
    .sidebar-mini.sidebar-collapse .sidebar-menu>li>a>span,
    .sidebar-mini.sidebar-collapse .sidebar-menu>li>a>span>.pull-right {
        display: none !important;
        -webkit-transform: translateZ(0)
    }
    .sidebar-mini.sidebar-collapse .main-header .logo {
        width: 50px
    }
    .sidebar-mini.sidebar-collapse .main-header .logo>.logo-mini {
        display: block;
        margin-left: -15px;
        margin-right: -15px;
        font-size: 18px
    }
    .sidebar-mini.sidebar-collapse .main-header .logo>.logo-lg {
        display: none
    }
    .sidebar-mini.sidebar-collapse .main-header .navbar {
        margin-left: 50px
    }
}

@media (min-width:768px) {
    .sidebar-mini:not(.sidebar-mini-expand-feature).sidebar-collapse .sidebar-menu>li:hover>.treeview-menu,
    .sidebar-mini:not(.sidebar-mini-expand-feature).sidebar-collapse .sidebar-menu>li:hover>a>span:not(.pull-right) {
        display: block !important;
        position: absolute;
        width: 180px;
        left: 50px
    }
    .sidebar-mini:not(.sidebar-mini-expand-feature).sidebar-collapse .sidebar-menu>li:hover>a>span {
        top: 0;
        margin-left: -3px;
        padding: 12px 5px 12px 20px;
        background-color: inherit
    }
    .sidebar-mini:not(.sidebar-mini-expand-feature).sidebar-collapse .sidebar-menu>li:hover>a>.pull-right-container {
        position: relative !important;
        float: right;
        width: auto !important;
        left: 180px !important;
        top: -22px !important;
        z-index: 900
    }
    .sidebar-mini:not(.sidebar-mini-expand-feature).sidebar-collapse .sidebar-menu>li:hover>a>.pull-right-container>.label:not(:first-of-type) {
        display: none
    }
    .sidebar-mini:not(.sidebar-mini-expand-feature).sidebar-collapse .sidebar-menu>li:hover>.treeview-menu {
        top: 44px;
        margin-left: 0
    }
}

.sidebar-expanded-on-hover .content-wrapper,
.sidebar-expanded-on-hover .main-footer {
    margin-left: 50px
}

.sidebar-expanded-on-hover .main-sidebar {
    box-shadow: 3px 0 8px rgba(0, 0, 0, .125)
}

.main-sidebar .user-panel,
.sidebar-menu,
.sidebar-menu>li.header {
    white-space: nowrap;
    overflow: hidden
}

.sidebar-menu:hover {
    overflow: visible
}

.sidebar-form,
.sidebar-menu>li.header {
    overflow: hidden;
    text-overflow: clip
}

.sidebar-menu li>a {
    position: relative
}

.sidebar-menu li>a>.pull-right-container {
    position: absolute;
    right: 10px;
    top: 50%;
    margin-top: -7px
}

.control-sidebar-bg {
    position: fixed;
    z-index: 1000;
    bottom: 0
}

.control-sidebar,
.control-sidebar-bg {
    top: 0;
    right: -230px;
    width: 230px;
    -webkit-transition: right .3s ease-in-out;
    -o-transition: right .3s ease-in-out;
    transition: right .3s ease-in-out
}

.control-sidebar {
    position: absolute;
    padding-top: 50px;
    z-index: 1010
}

@media (max-width:767px) {
    .control-sidebar {
        padding-top: 100px
    }
}

.control-sidebar>.tab-content {
    padding: 10px 15px
}

.control-sidebar.control-sidebar-open,
.control-sidebar.control-sidebar-open+.control-sidebar-bg {
    right: 0
}

.control-sidebar-hold-transition .content-wrapper,
.control-sidebar-hold-transition .control-sidebar,
.control-sidebar-hold-transition .control-sidebar-bg {
    transition: none
}

.control-sidebar-open .control-sidebar,
.control-sidebar-open .control-sidebar-bg {
    right: 0
}

@media (min-width:768px) {
    .control-sidebar-open .content-wrapper,
    .control-sidebar-open .main-footer,
    .control-sidebar-open .right-side {
        margin-right: 230px
    }
}

.fixed .control-sidebar {
    position: fixed;
    height: 100%;
    overflow-y: auto;
    padding-bottom: 50px
}

.nav-tabs.control-sidebar-tabs>li:first-of-type>a,
.nav-tabs.control-sidebar-tabs>li:first-of-type>a:focus,
.nav-tabs.control-sidebar-tabs>li:first-of-type>a:hover {
    border-left-width: 0
}

.nav-tabs.control-sidebar-tabs>li>a {
    border-radius: 0
}

.nav-tabs.control-sidebar-tabs>li>a,
.nav-tabs.control-sidebar-tabs>li>a:hover {
    border-top: none;
    border-right: none;
    border-left: 1px solid transparent;
    border-bottom: 1px solid transparent
}

.nav-tabs.control-sidebar-tabs>li>a .icon {
    font-size: 16px
}

.nav-tabs.control-sidebar-tabs>li.active>a,
.nav-tabs.control-sidebar-tabs>li.active>a:active,
.nav-tabs.control-sidebar-tabs>li.active>a:focus,
.nav-tabs.control-sidebar-tabs>li.active>a:hover {
    border-top: none;
    border-right: none;
    border-bottom: none
}

@media (max-width:768px) {
    .nav-tabs.control-sidebar-tabs {
        display: table
    }
    .nav-tabs.control-sidebar-tabs>li {
        display: table-cell
    }
}

.control-sidebar-heading {
    font-weight: 400;
    font-size: 16px;
    padding: 10px 0;
    margin-bottom: 10px
}

.control-sidebar-subheading {
    display: block;
    font-weight: 400;
    font-size: 14px
}

.control-sidebar-menu {
    list-style: none;
    padding: 0;
    margin: 0 -15px
}

.control-sidebar-menu>li>a {
    display: block;
    padding: 10px 15px
}

.control-sidebar-menu>li>a:after,
.control-sidebar-menu>li>a:before {
    content: " ";
    display: table
}

.control-sidebar-menu>li>a:after {
    clear: both
}

.control-sidebar-menu>li>a>.control-sidebar-subheading {
    margin-top: 0
}

.control-sidebar-menu .menu-icon {
    float: left;
    width: 35px;
    height: 35px;
    border-radius: 50%;
    text-align: center;
    line-height: 35px
}

.control-sidebar-menu .menu-info {
    margin-left: 45px;
    margin-top: 3px
}

.control-sidebar-menu .menu-info>.control-sidebar-subheading {
    margin: 0
}

.control-sidebar-menu .menu-info>p {
    margin: 0;
    font-size: 11px
}

.control-sidebar-menu .progress {
    margin: 0
}

.control-sidebar-dark {
    color: #b8c7ce
}

.control-sidebar-dark,
.control-sidebar-dark+.control-sidebar-bg {
    background: #222d32
}

.control-sidebar-dark .nav-tabs.control-sidebar-tabs {
    border-bottom: #1c2529
}

.control-sidebar-dark .nav-tabs.control-sidebar-tabs>li>a {
    background: #181f23;
    color: #b8c7ce
}

.control-sidebar-dark .nav-tabs.control-sidebar-tabs>li>a,
.control-sidebar-dark .nav-tabs.control-sidebar-tabs>li>a:focus,
.control-sidebar-dark .nav-tabs.control-sidebar-tabs>li>a:hover {
    border-left-color: #141a1d;
    border-bottom-color: #141a1d
}

.control-sidebar-dark .nav-tabs.control-sidebar-tabs>li>a:active,
.control-sidebar-dark .nav-tabs.control-sidebar-tabs>li>a:focus,
.control-sidebar-dark .nav-tabs.control-sidebar-tabs>li>a:hover {
    background: #1c2529
}

.control-sidebar-dark .nav-tabs.control-sidebar-tabs>li>a:hover {
    color: #fff
}

.control-sidebar-dark .nav-tabs.control-sidebar-tabs>li.active>a,
.control-sidebar-dark .nav-tabs.control-sidebar-tabs>li.active>a:active,
.control-sidebar-dark .nav-tabs.control-sidebar-tabs>li.active>a:focus,
.control-sidebar-dark .nav-tabs.control-sidebar-tabs>li.active>a:hover {
    background: #222d32;
    color: #fff
}

.control-sidebar-dark .control-sidebar-heading,
.control-sidebar-dark .control-sidebar-subheading {
    color: #fff
}

.control-sidebar-dark .control-sidebar-menu>li>a:hover {
    background: #1e282c
}

.control-sidebar-dark .control-sidebar-menu>li>a .menu-info>p {
    color: #b8c7ce
}

.control-sidebar-light {
    color: #5e5e5e
}

.control-sidebar-light,
.control-sidebar-light+.control-sidebar-bg {
    background: #f9fafc;
    border-left: 1px solid #d2d6de
}

.control-sidebar-light .nav-tabs.control-sidebar-tabs {
    border-bottom: #d2d6de
}

.control-sidebar-light .nav-tabs.control-sidebar-tabs>li>a {
    background: #e8ecf4;
    color: #444
}

.control-sidebar-light .nav-tabs.control-sidebar-tabs>li>a,
.control-sidebar-light .nav-tabs.control-sidebar-tabs>li>a:focus,
.control-sidebar-light .nav-tabs.control-sidebar-tabs>li>a:hover {
    border-left-color: #d2d6de;
    border-bottom-color: #d2d6de
}

.control-sidebar-light .nav-tabs.control-sidebar-tabs>li>a:active,
.control-sidebar-light .nav-tabs.control-sidebar-tabs>li>a:focus,
.control-sidebar-light .nav-tabs.control-sidebar-tabs>li>a:hover {
    background: #eff1f7
}

.control-sidebar-light .nav-tabs.control-sidebar-tabs>li.active>a,
.control-sidebar-light .nav-tabs.control-sidebar-tabs>li.active>a:active,
.control-sidebar-light .nav-tabs.control-sidebar-tabs>li.active>a:focus,
.control-sidebar-light .nav-tabs.control-sidebar-tabs>li.active>a:hover {
    background: #f9fafc;
    color: #111
}

.control-sidebar-light .control-sidebar-heading,
.control-sidebar-light .control-sidebar-subheading {
    color: #111
}

.control-sidebar-light .control-sidebar-menu {
    margin-left: -14px
}

.control-sidebar-light .control-sidebar-menu>li>a:hover {
    background: #f4f4f5
}

.control-sidebar-light .control-sidebar-menu>li>a .menu-info>p {
    color: #5e5e5e
}

.dropdown-menu {
    box-shadow: none;
    border-color: #eee
}

.dropdown-menu>li>a {
    color: #777
}

.dropdown-menu>li>a>.fa,
.dropdown-menu>li>a>.glyphicon,
.dropdown-menu>li>a>.ion {
    margin-right: 10px
}

.dropdown-menu>li>a:hover {
    background-color: #e1e3e9;
    color: #333
}

.dropdown-menu>.divider {
    background-color: #eee
}

.navbar-nav>.messages-menu>.dropdown-menu,
.navbar-nav>.notifications-menu>.dropdown-menu,
.navbar-nav>.tasks-menu>.dropdown-menu {
    width: 280px;
    padding: 0;
    margin: 0;
    top: 100%
}

.navbar-nav>.messages-menu>.dropdown-menu>li,
.navbar-nav>.notifications-menu>.dropdown-menu>li,
.navbar-nav>.tasks-menu>.dropdown-menu>li {
    position: relative
}

.navbar-nav>.messages-menu>.dropdown-menu>li.header,
.navbar-nav>.notifications-menu>.dropdown-menu>li.header,
.navbar-nav>.tasks-menu>.dropdown-menu>li.header {
    border-top-left-radius: 4px;
    border-top-right-radius: 4px;
    border-bottom-right-radius: 0;
    border-bottom-left-radius: 0;
    background-color: #fff;
    padding: 7px 10px;
    border-bottom: 1px solid #f4f4f4;
    color: #444;
    font-size: 14px
}

.navbar-nav>.messages-menu>.dropdown-menu>li.footer>a,
.navbar-nav>.notifications-menu>.dropdown-menu>li.footer>a,
.navbar-nav>.tasks-menu>.dropdown-menu>li.footer>a {
    border-top-left-radius: 0;
    border-top-right-radius: 0;
    border-bottom-right-radius: 4px;
    border-bottom-left-radius: 4px;
    font-size: 12px;
    background-color: #fff;
    padding: 7px 10px;
    border-bottom: 1px solid #eee;
    color: #444 !important;
    text-align: center
}

@media (max-width:991px) {
    .navbar-nav>.messages-menu>.dropdown-menu>li.footer>a,
    .navbar-nav>.notifications-menu>.dropdown-menu>li.footer>a,
    .navbar-nav>.tasks-menu>.dropdown-menu>li.footer>a {
        background: #fff !important;
        color: #444 !important
    }
}

.navbar-nav>.messages-menu>.dropdown-menu>li.footer>a:hover,
.navbar-nav>.notifications-menu>.dropdown-menu>li.footer>a:hover,
.navbar-nav>.tasks-menu>.dropdown-menu>li.footer>a:hover {
    text-decoration: none;
    font-weight: 400
}

.navbar-nav>.messages-menu>.dropdown-menu>li .menu,
.navbar-nav>.notifications-menu>.dropdown-menu>li .menu,
.navbar-nav>.tasks-menu>.dropdown-menu>li .menu {
    max-height: 200px;
    margin: 0;
    padding: 0;
    list-style: none;
    overflow-x: hidden
}

.navbar-nav>.messages-menu>.dropdown-menu>li .menu>li>a,
.navbar-nav>.notifications-menu>.dropdown-menu>li .menu>li>a,
.navbar-nav>.tasks-menu>.dropdown-menu>li .menu>li>a {
    display: block;
    white-space: nowrap;
    border-bottom: 1px solid #f4f4f4
}

.navbar-nav>.messages-menu>.dropdown-menu>li .menu>li>a:hover,
.navbar-nav>.notifications-menu>.dropdown-menu>li .menu>li>a:hover,
.navbar-nav>.tasks-menu>.dropdown-menu>li .menu>li>a:hover {
    background: #f4f4f4;
    text-decoration: none
}

.navbar-nav>.notifications-menu>.dropdown-menu>li .menu>li>a {
    color: #444;
    overflow: hidden;
    text-overflow: ellipsis;
    padding: 10px
}

.navbar-nav>.notifications-menu>.dropdown-menu>li .menu>li>a>.fa,
.navbar-nav>.notifications-menu>.dropdown-menu>li .menu>li>a>.glyphicon,
.navbar-nav>.notifications-menu>.dropdown-menu>li .menu>li>a>.ion {
    width: 20px
}

.navbar-nav>.messages-menu>.dropdown-menu>li .menu>li>a {
    margin: 0;
    padding: 10px 10px
}

.navbar-nav>.messages-menu>.dropdown-menu>li .menu>li>a>div>img {
    margin: auto 10px auto auto;
    width: 40px;
    height: 40px
}

.navbar-nav>.messages-menu>.dropdown-menu>li .menu>li>a>h4 {
    padding: 0;
    margin: 0 0 0 45px;
    color: #444;
    font-size: 15px;
    position: relative
}

.navbar-nav>.messages-menu>.dropdown-menu>li .menu>li>a>h4>small {
    color: #999;
    font-size: 10px;
    position: absolute;
    top: 0;
    right: 0
}

.navbar-nav>.messages-menu>.dropdown-menu>li .menu>li>a>p {
    margin: 0 0 0 45px;
    font-size: 12px;
    color: #888
}

.navbar-nav>.messages-menu>.dropdown-menu>li .menu>li>a:after,
.navbar-nav>.messages-menu>.dropdown-menu>li .menu>li>a:before {
    content: " ";
    display: table
}

.navbar-nav>.messages-menu>.dropdown-menu>li .menu>li>a:after {
    clear: both
}

.navbar-nav>.tasks-menu>.dropdown-menu>li .menu>li>a {
    padding: 10px
}

.navbar-nav>.tasks-menu>.dropdown-menu>li .menu>li>a>h3 {
    font-size: 14px;
    padding: 0;
    margin: 0 0 10px 0;
    color: #666
}

.navbar-nav>.tasks-menu>.dropdown-menu>li .menu>li>a>.progress {
    padding: 0;
    margin: 0
}

.navbar-nav>.user-menu>.dropdown-menu {
    border-top-right-radius: 0;
    border-top-left-radius: 0;
    padding: 1px 0 0 0;
    border-top-width: 0;
    width: 280px
}

.navbar-nav>.user-menu>.dropdown-menu,
.navbar-nav>.user-menu>.dropdown-menu>.user-body {
    border-bottom-right-radius: 4px;
    border-bottom-left-radius: 4px
}

.navbar-nav>.user-menu>.dropdown-menu>li.user-header {
    height: 175px;
    padding: 10px;
    text-align: center
}

.navbar-nav>.user-menu>.dropdown-menu>li.user-header>img {
    z-index: 5;
    height: 90px;
    width: 90px;
    border: 3px solid;
    border-color: transparent;
    border-color: rgba(255, 255, 255, .2)
}

.navbar-nav>.user-menu>.dropdown-menu>li.user-header>p {
    z-index: 5;
    color: #fff;
    color: rgba(255, 255, 255, .8);
    font-size: 17px;
    margin-top: 10px
}

.navbar-nav>.user-menu>.dropdown-menu>li.user-header>p>small {
    display: block;
    font-size: 12px
}

.navbar-nav>.user-menu>.dropdown-menu>.user-body {
    padding: 15px;
    border-bottom: 1px solid #f4f4f4;
    border-top: 1px solid #ddd
}

.navbar-nav>.user-menu>.dropdown-menu>.user-body:after,
.navbar-nav>.user-menu>.dropdown-menu>.user-body:before {
    content: " ";
    display: table
}

.navbar-nav>.user-menu>.dropdown-menu>.user-body:after {
    clear: both
}

.navbar-nav>.user-menu>.dropdown-menu>.user-body a {
    color: #444 !important
}

@media (max-width:991px) {
    .navbar-nav>.user-menu>.dropdown-menu>.user-body a {
        background: #fff !important;
        color: #444 !important
    }
}

.navbar-nav>.user-menu>.dropdown-menu>.user-footer {
    background-color: #f9f9f9;
    padding: 10px
}

.navbar-nav>.user-menu>.dropdown-menu>.user-footer:after,
.navbar-nav>.user-menu>.dropdown-menu>.user-footer:before {
    content: " ";
    display: table
}

.navbar-nav>.user-menu>.dropdown-menu>.user-footer:after {
    clear: both
}

.navbar-nav>.user-menu>.dropdown-menu>.user-footer .btn-default {
    color: #666
}

@media (max-width:991px) {
    .navbar-nav>.user-menu>.dropdown-menu>.user-footer .btn-default:hover {
        background-color: #f9f9f9
    }
}

.navbar-nav>.user-menu .user-image {
    float: left;
    width: 25px;
    height: 25px;
    border-radius: 50%;
    margin-right: 10px;
    margin-top: -2px
}

@media (max-width:767px) {
    .navbar-nav>.user-menu .user-image {
        float: none;
        margin-right: 0;
        margin-top: -8px;
        line-height: 10px
    }
}

.open:not(.dropup)>.animated-dropdown-menu {
    backface-visibility: visible !important;
    -webkit-animation: flipInX .7s both;
    -o-animation: flipInX .7s both;
    animation: flipInX .7s both
}

@keyframes flipInX {
    0% {
        transform: perspective(400px) rotate3d(1, 0, 0, 90deg);
        transition-timing-function: ease-in;
        opacity: 0
    }
    40% {
        transform: perspective(400px) rotate3d(1, 0, 0, -20deg);
        transition-timing-function: ease-in
    }
    60% {
        transform: perspective(400px) rotate3d(1, 0, 0, 10deg);
        opacity: 1
    }
    80% {
        transform: perspective(400px) rotate3d(1, 0, 0, -5deg)
    }
    100% {
        transform: perspective(400px)
    }
}

@-webkit-keyframes flipInX {
    0% {
        -webkit-transform: perspective(400px) rotate3d(1, 0, 0, 90deg);
        -webkit-transition-timing-function: ease-in;
        opacity: 0
    }
    40% {
        -webkit-transform: perspective(400px) rotate3d(1, 0, 0, -20deg);
        -webkit-transition-timing-function: ease-in
    }
    60% {
        -webkit-transform: perspective(400px) rotate3d(1, 0, 0, 10deg);
        opacity: 1
    }
    80% {
        -webkit-transform: perspective(400px) rotate3d(1, 0, 0, -5deg)
    }
    100% {
        -webkit-transform: perspective(400px)
    }
}

.navbar-custom-menu>.navbar-nav>li {
    position: relative
}

.navbar-custom-menu>.navbar-nav>li>.dropdown-menu {
    position: absolute;
    right: 0;
    left: auto
}

@media (max-width:991px) {
    .navbar-custom-menu>.navbar-nav {
        float: right
    }
    .navbar-custom-menu>.navbar-nav>li {
        position: static
    }
    .navbar-custom-menu>.navbar-nav>li>.dropdown-menu {
        position: absolute;
        right: 5%;
        left: auto;
        border: 1px solid #ddd;
        background: #fff
    }
}

.form-control {
    border-radius: 0;
    box-shadow: none;
    border-color: #d2d6de
}

.form-control:focus {
    border-color: #3c8dbc;
    box-shadow: none
}

.form-control:-ms-input-placeholder,
.form-control::-moz-placeholder,
.form-control::-webkit-input-placeholder {
    color: #bbb;
    opacity: 1
}

.form-control:not(select) {
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none
}

.form-group.has-success label {
    color: #00a65a
}

.form-group.has-success .form-control,
.form-group.has-success .input-group-addon {
    border-color: #00a65a;
    box-shadow: none
}

.form-group.has-success .help-block {
    color: #00a65a
}

.form-group.has-warning label {
    color: #f39c12
}

.form-group.has-warning .form-control,
.form-group.has-warning .input-group-addon {
    border-color: #f39c12;
    box-shadow: none
}

.form-group.has-warning .help-block {
    color: #f39c12
}

.form-group.has-error label {
    color: #dd4b39
}

.form-group.has-error .form-control,
.form-group.has-error .input-group-addon {
    border-color: #dd4b39;
    box-shadow: none
}

.form-group.has-error .help-block {
    color: #dd4b39
}

.input-group .input-group-addon {
    border-radius: 0;
    border-color: #d2d6de;
    background-color: #fff
}

.btn-group-vertical .btn.btn-flat:first-of-type,
.btn-group-vertical .btn.btn-flat:last-of-type {
    border-radius: 0
}

.icheck>label {
    padding-left: 0
}

.form-control-feedback.fa {
    line-height: 34px
}

.form-group-lg .form-control+.form-control-feedback.fa,
.input-group-lg+.form-control-feedback.fa,
.input-lg+.form-control-feedback.fa {
    line-height: 46px
}

.form-group-sm .form-control+.form-control-feedback.fa,
.input-group-sm+.form-control-feedback.fa,
.input-sm+.form-control-feedback.fa {
    line-height: 30px
}

.progress,
.progress>.progress-bar {
    -webkit-box-shadow: none;
    box-shadow: none
}

.progress,
.progress .progress-bar,
.progress>.progress-bar,
.progress>.progress-bar .progress-bar {
    border-radius: 1px
}

.progress-sm,
.progress.sm {
    height: 10px
}

.progress-sm,
.progress-sm .progress-bar,
.progress.sm,
.progress.sm .progress-bar {
    border-radius: 1px
}

.progress-xs,
.progress.xs {
    height: 7px
}

.progress-xs,
.progress-xs .progress-bar,
.progress.xs,
.progress.xs .progress-bar {
    border-radius: 1px
}

.progress-xxs,
.progress.xxs {
    height: 3px
}

.progress-xxs,
.progress-xxs .progress-bar,
.progress.xxs,
.progress.xxs .progress-bar {
    border-radius: 1px
}

.progress.vertical {
    position: relative;
    width: 30px;
    height: 200px;
    display: inline-block;
    margin-right: 10px
}

.progress.vertical>.progress-bar {
    width: 100%;
    position: absolute;
    bottom: 0
}

.progress.vertical.progress-sm,
.progress.vertical.sm {
    width: 20px
}

.progress.vertical.progress-xs,
.progress.vertical.xs {
    width: 10px
}

.progress.vertical.progress-xxs,
.progress.vertical.xxs {
    width: 3px
}

.progress-group .progress-text {
    font-weight: 600
}

.progress-group .progress-number {
    float: right
}

.table tr>td .progress {
    margin: 0
}

.progress-bar-light-blue,
.progress-bar-primary {
    background-color: #3c8dbc
}

.progress-striped .progress-bar-light-blue,
.progress-striped .progress-bar-primary {
    background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, .15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .15) 50%, rgba(255, 255, 255, .15) 75%, transparent 75%, transparent);
    background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, .15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .15) 50%, rgba(255, 255, 255, .15) 75%, transparent 75%, transparent);
    background-image: linear-gradient(45deg, rgba(255, 255, 255, .15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .15) 50%, rgba(255, 255, 255, .15) 75%, transparent 75%, transparent)
}

.progress-bar-green,
.progress-bar-success {
    background-color: #00a65a
}

.progress-striped .progress-bar-green,
.progress-striped .progress-bar-success {
    background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, .15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .15) 50%, rgba(255, 255, 255, .15) 75%, transparent 75%, transparent);
    background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, .15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .15) 50%, rgba(255, 255, 255, .15) 75%, transparent 75%, transparent);
    background-image: linear-gradient(45deg, rgba(255, 255, 255, .15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .15) 50%, rgba(255, 255, 255, .15) 75%, transparent 75%, transparent)
}

.progress-bar-aqua,
.progress-bar-info {
    background-color: #00c0ef
}

.progress-striped .progress-bar-aqua,
.progress-striped .progress-bar-info {
    background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, .15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .15) 50%, rgba(255, 255, 255, .15) 75%, transparent 75%, transparent);
    background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, .15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .15) 50%, rgba(255, 255, 255, .15) 75%, transparent 75%, transparent);
    background-image: linear-gradient(45deg, rgba(255, 255, 255, .15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .15) 50%, rgba(255, 255, 255, .15) 75%, transparent 75%, transparent)
}

.progress-bar-warning,
.progress-bar-yellow {
    background-color: #f39c12
}

.progress-striped .progress-bar-warning,
.progress-striped .progress-bar-yellow {
    background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, .15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .15) 50%, rgba(255, 255, 255, .15) 75%, transparent 75%, transparent);
    background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, .15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .15) 50%, rgba(255, 255, 255, .15) 75%, transparent 75%, transparent);
    background-image: linear-gradient(45deg, rgba(255, 255, 255, .15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .15) 50%, rgba(255, 255, 255, .15) 75%, transparent 75%, transparent)
}

.progress-bar-danger,
.progress-bar-red {
    background-color: #dd4b39
}

.progress-striped .progress-bar-danger,
.progress-striped .progress-bar-red {
    background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, .15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .15) 50%, rgba(255, 255, 255, .15) 75%, transparent 75%, transparent);
    background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, .15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .15) 50%, rgba(255, 255, 255, .15) 75%, transparent 75%, transparent);
    background-image: linear-gradient(45deg, rgba(255, 255, 255, .15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .15) 50%, rgba(255, 255, 255, .15) 75%, transparent 75%, transparent)
}

.small-box {
    border-radius: 2px;
    position: relative;
    display: block;
    margin-bottom: 20px;
    box-shadow: 0 1px 1px rgba(0, 0, 0, .1)
}

.small-box>.inner {
    padding: 10px
}

.small-box>.small-box-footer {
    position: relative;
    text-align: center;
    padding: 3px 0;
    color: #fff;
    color: rgba(255, 255, 255, .8);
    display: block;
    z-index: 10;
    background: rgba(0, 0, 0, .1);
    text-decoration: none
}

.small-box>.small-box-footer:hover {
    color: #fff;
    background: rgba(0, 0, 0, .15)
}

.small-box h3 {
    font-size: 38px;
    font-weight: 700;
    margin: 0 0 10px 0;
    white-space: nowrap;
    padding: 0
}

.small-box p {
    font-size: 15px
}

.small-box p>small {
    display: block;
    color: #f9f9f9;
    font-size: 13px;
    margin-top: 5px
}

.small-box h3,
.small-box p {
    z-index: 5
}

.small-box .icon {
    -webkit-transition: all .3s linear;
    -o-transition: all .3s linear;
    transition: all .3s linear;
    position: absolute;
    top: -10px;
    right: 10px;
    z-index: 0;
    font-size: 90px;
    color: rgba(0, 0, 0, .15)
}

.small-box:hover {
    text-decoration: none;
    color: #f9f9f9
}

.small-box:hover .icon {
    font-size: 95px
}

@media (max-width:767px) {
    .small-box {
        text-align: center
    }
    .small-box .icon {
        display: none
    }
    .small-box p {
        font-size: 12px
    }
}

.box {
    position: relative;
    border-radius: 3px;
    background: #fff;
    border-top: 3px solid #d2d6de;
    margin-bottom: 20px;
    width: 100%;
    box-shadow: 0 1px 1px rgba(0, 0, 0, .1)
}

.box.box-primary {
    border-top-color: #3c8dbc
}

.box.box-info {
    border-top-color: #00c0ef
}

.box.box-danger {
    border-top-color: #dd4b39
}

.box.box-warning {
    border-top-color: #f39c12
}

.box.box-success {
    border-top-color: #00a65a
}

.box.box-default {
    border-top-color: #d2d6de
}

.box.collapsed-box .box-body,
.box.collapsed-box .box-footer {
    display: none
}

.box .nav-stacked>li {
    border-bottom: 1px solid #f4f4f4;
    margin: 0
}

.box .nav-stacked>li:last-of-type {
    border-bottom: none
}

.box.height-control .box-body {
    max-height: 300px;
    overflow: auto
}

.box .border-right {
    border-right: 1px solid #f4f4f4
}

.box .border-left {
    border-left: 1px solid #f4f4f4
}

.box.box-solid {
    border-top: 0
}

.box.box-solid>.box-header .btn.btn-default {
    background: 0 0
}

.box.box-solid>.box-header .btn:hover,
.box.box-solid>.box-header a:hover {
    background: rgba(0, 0, 0, .1)
}

.box.box-solid.box-default {
    border: 1px solid #d2d6de
}

.box.box-solid.box-default>.box-header {
    color: #444;
    background: #d2d6de;
    background-color: #d2d6de
}

.box.box-solid.box-default>.box-header .btn,
.box.box-solid.box-default>.box-header a {
    color: #444
}

.box.box-solid.box-primary {
    border: 1px solid #3c8dbc
}

.box.box-solid.box-primary>.box-header {
    color: #fff;
    background: #3c8dbc;
    background-color: #3c8dbc
}

.box.box-solid.box-primary>.box-header .btn,
.box.box-solid.box-primary>.box-header a {
    color: #fff
}

.box.box-solid.box-info {
    border: 1px solid #00c0ef
}

.box.box-solid.box-info>.box-header {
    color: #fff;
    background: #00c0ef;
    background-color: #00c0ef
}

.box.box-solid.box-info>.box-header .btn,
.box.box-solid.box-info>.box-header a {
    color: #fff
}

.box.box-solid.box-danger {
    border: 1px solid #dd4b39
}

.box.box-solid.box-danger>.box-header {
    color: #fff;
    background: #dd4b39;
    background-color: #dd4b39
}

.box.box-solid.box-danger>.box-header .btn,
.box.box-solid.box-danger>.box-header a {
    color: #fff
}

.box.box-solid.box-warning {
    border: 1px solid #f39c12
}

.box.box-solid.box-warning>.box-header {
    color: #fff;
    background: #f39c12;
    background-color: #f39c12
}

.box.box-solid.box-warning>.box-header .btn,
.box.box-solid.box-warning>.box-header a {
    color: #fff
}

.box.box-solid.box-success {
    border: 1px solid #00a65a
}

.box.box-solid.box-success>.box-header {
    color: #fff;
    background: #00a65a;
    background-color: #00a65a
}

.box.box-solid.box-success>.box-header .btn,
.box.box-solid.box-success>.box-header a {
    color: #fff
}

.box.box-solid>.box-header>.box-tools .btn {
    border: 0;
    box-shadow: none
}

.box.box-solid[class*=bg]>.box-header {
    color: #fff
}

.box .box-group>.box {
    margin-bottom: 5px
}

.box .knob-label {
    text-align: center;
    color: #333;
    font-weight: 100;
    font-size: 12px;
    margin-bottom: .3em
}

.box>.loading-img,
.box>.overlay,
.overlay-wrapper>.loading-img,
.overlay-wrapper>.overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%
}

.box .overlay,
.overlay-wrapper .overlay {
    z-index: 50;
    background: rgba(255, 255, 255, .7);
    border-radius: 3px
}

.box .overlay>.fa,
.overlay-wrapper .overlay>.fa {
    position: absolute;
    top: 50%;
    left: 50%;
    margin-left: -15px;
    margin-top: -15px;
    color: #000;
    font-size: 30px
}

.box .overlay.dark,
.overlay-wrapper .overlay.dark {
    background: rgba(0, 0, 0, .5)
}

.box-body:after,
.box-body:before,
.box-footer:after,
.box-footer:before,
.box-header:after,
.box-header:before {
    content: " ";
    display: table
}

.box-body:after,
.box-footer:after,
.box-header:after {
    clear: both
}

.box-header {
    color: #444;
    display: block;
    padding: 10px;
    position: relative
}

.box-header.with-border {
    border-bottom: 1px solid #f4f4f4
}

.collapsed-box .box-header.with-border {
    border-bottom: none
}

.box-header .box-title,
.box-header>.fa,
.box-header>.glyphicon,
.box-header>.ion {
    display: inline-block;
    font-size: 18px;
    margin: 0;
    line-height: 1
}

.box-header>.fa,
.box-header>.glyphicon,
.box-header>.ion {
    margin-right: 5px
}

.box-header>.box-tools {
    float: right;
    margin-top: -5px;
    margin-bottom: -5px
}

.box-header>.box-tools [data-toggle=tooltip] {
    position: relative
}

.box-header>.box-tools.pull-right .dropdown-menu {
    right: 0;
    left: auto
}

.box-header>.box-tools .dropdown-menu>li>a {
    color: #444 !important
}

.btn-box-tool {
    padding: 5px;
    font-size: 12px;
    background: 0 0;
    color: #97a0b3
}

.btn-box-tool:hover,
.open .btn-box-tool {
    color: #606c84
}

.btn-box-tool.btn:active {
    box-shadow: none
}

.box-body {
    border-top-left-radius: 0;
    border-top-right-radius: 0;
    border-bottom-right-radius: 3px;
    border-bottom-left-radius: 3px;
    padding: 10px
}

.no-header .box-body {
    border-top-right-radius: 3px;
    border-top-left-radius: 3px
}

.box-body>.table {
    margin-bottom: 0
}

.box-body .fc {
    margin-top: 5px
}

.box-body .full-width-chart {
    margin: -19px
}

.box-body.no-padding .full-width-chart {
    margin: -9px
}

.box-body .box-pane {
    border-top-left-radius: 0;
    border-top-right-radius: 0;
    border-bottom-right-radius: 0;
    border-bottom-left-radius: 3px
}

.box-body .box-pane-right {
    border-top-left-radius: 0;
    border-top-right-radius: 0;
    border-bottom-right-radius: 3px;
    border-bottom-left-radius: 0
}

.box-footer {
    border-top-left-radius: 0;
    border-top-right-radius: 0;
    border-bottom-right-radius: 3px;
    border-bottom-left-radius: 3px;
    border-top: 1px solid #f4f4f4;
    padding: 10px;
    background-color: #fff
}

.chart-legend {
    margin: 10px 0
}

@media (max-width:991px) {
    .chart-legend>li {
        float: left;
        margin-right: 10px
    }
}

.box-comments {
    background: #f7f7f7
}

.box-comments .box-comment {
    padding: 8px 0;
    border-bottom: 1px solid #eee
}

.box-comments .box-comment:after,
.box-comments .box-comment:before {
    content: " ";
    display: table
}

.box-comments .box-comment:after {
    clear: both
}

.box-comments .box-comment:last-of-type {
    border-bottom: 0
}

.box-comments .box-comment:first-of-type {
    padding-top: 0
}

.box-comments .box-comment img {
    float: left
}

.box-comments .comment-text {
    margin-left: 40px;
    color: #555
}

.box-comments .username {
    color: #444;
    display: block;
    font-weight: 600
}

.box-comments .text-muted {
    font-weight: 400;
    font-size: 12px
}

.todo-list {
    margin: 0;
    padding: 0;
    list-style: none;
    overflow: auto
}

.todo-list>li {
    border-radius: 2px;
    padding: 10px;
    background: #f4f4f4;
    margin-bottom: 2px;
    border-left: 2px solid #e6e7e8;
    color: #444
}

.todo-list>li:last-of-type {
    margin-bottom: 0
}

.todo-list>li>input[type=checkbox] {
    margin: 0 10px 0 5px
}

.todo-list>li .text {
    display: inline-block;
    margin-left: 5px;
    font-weight: 600
}

.todo-list>li .label {
    margin-left: 10px;
    font-size: 9px
}

.todo-list>li .tools {
    display: none;
    float: right;
    color: #dd4b39
}

.todo-list>li .tools>.fa,
.todo-list>li .tools>.glyphicon,
.todo-list>li .tools>.ion {
    margin-right: 5px;
    cursor: pointer
}

.todo-list>li:hover .tools {
    display: inline-block
}

.todo-list>li.done {
    color: #999
}

.todo-list>li.done .text {
    text-decoration: line-through;
    font-weight: 500
}

.todo-list>li.done .label {
    background: #d2d6de !important
}

.todo-list .danger {
    border-left-color: #dd4b39
}

.todo-list .warning {
    border-left-color: #f39c12
}

.todo-list .info {
    border-left-color: #00c0ef
}

.todo-list .success {
    border-left-color: #00a65a
}

.todo-list .primary {
    border-left-color: #3c8dbc
}

.todo-list .handle {
    display: inline-block;
    cursor: move;
    margin: 0 5px
}

.chat {
    padding: 5px 20px 5px 10px
}

.chat .item {
    margin-bottom: 10px
}

.chat .item:after,
.chat .item:before {
    content: " ";
    display: table
}

.chat .item:after {
    clear: both
}

.chat .item>img {
    width: 40px;
    height: 40px;
    border: 2px solid transparent;
    border-radius: 50%
}

.chat .item>.online {
    border: 2px solid #00a65a
}

.chat .item>.offline {
    border: 2px solid #dd4b39
}

.chat .item>.message {
    margin-left: 55px;
    margin-top: -40px
}

.chat .item>.message>.name {
    display: block;
    font-weight: 600
}

.chat .item>.attachment {
    border-radius: 3px;
    background: #f4f4f4;
    margin-left: 65px;
    margin-right: 15px;
    padding: 10px
}

.chat .item>.attachment>h4 {
    margin: 0 0 5px 0;
    font-weight: 600;
    font-size: 14px
}

.chat .item>.attachment>.filename,
.chat .item>.attachment>p {
    font-weight: 600;
    font-size: 13px;
    font-style: italic;
    margin: 0
}

.chat .item>.attachment:after,
.chat .item>.attachment:before {
    content: " ";
    display: table
}

.chat .item>.attachment:after {
    clear: both
}

.box-input {
    max-width: 200px
}

.modal .panel-body {
    color: #444
}

.info-box {
    display: block;
    min-height: 90px;
    background: #fff;
    width: 100%;
    box-shadow: 0 1px 1px rgba(0, 0, 0, .1);
    border-radius: 2px;
    margin-bottom: 15px
}

.info-box small {
    font-size: 14px
}

.info-box .progress {
    background: rgba(0, 0, 0, .2);
    margin: 5px -10px 5px -10px;
    height: 2px
}

.info-box .progress,
.info-box .progress .progress-bar {
    border-radius: 0
}

.info-box .progress .progress-bar {
    background: #fff
}

.info-box-icon {
    border-top-left-radius: 2px;
    border-top-right-radius: 0;
    border-bottom-right-radius: 0;
    border-bottom-left-radius: 2px;
    display: block;
    float: left;
    height: 90px;
    width: 90px;
    text-align: center;
    font-size: 45px;
    line-height: 90px;
    background: rgba(0, 0, 0, .2)
}

.info-box-icon>img {
    max-width: 100%
}

.info-box-content {
    padding: 5px 10px;
    margin-left: 90px
}

.info-box-number {
    display: block;
    font-weight: 700;
    font-size: 18px
}

.info-box-text,
.progress-description {
    display: block;
    font-size: 14px;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis
}

.info-box-text {
    text-transform: uppercase
}

.info-box-more {
    display: block
}

.progress-description {
    margin: 0
}

.timeline {
    position: relative;
    margin: 0 0 30px 0;
    padding: 0;
    list-style: none
}

.timeline:before {
    content: '';
    position: absolute;
    top: 0;
    bottom: 0;
    width: 4px;
    background: #ddd;
    left: 31px;
    margin: 0;
    border-radius: 2px
}

.timeline>li {
    position: relative;
    margin-right: 10px;
    margin-bottom: 15px
}

.timeline>li:after,
.timeline>li:before {
    content: " ";
    display: table
}

.timeline>li:after {
    clear: both
}

.timeline>li>.timeline-item {
    -webkit-box-shadow: 0 1px 1px rgba(0, 0, 0, .1);
    box-shadow: 0 1px 1px rgba(0, 0, 0, .1);
    border-radius: 3px;
    margin-top: 0;
    background: #fff;
    color: #444;
    margin-left: 60px;
    margin-right: 15px;
    padding: 0;
    position: relative
}

.timeline>li>.timeline-item>.time {
    color: #999;
    float: right;
    padding: 10px;
    font-size: 12px
}

.timeline>li>.timeline-item>.timeline-header {
    margin: 0;
    color: #555;
    border-bottom: 1px solid #f4f4f4;
    padding: 10px;
    font-size: 16px;
    line-height: 1.1
}

.timeline>li>.timeline-item>.timeline-header>a {
    font-weight: 600
}

.timeline>li>.timeline-item>.timeline-body,
.timeline>li>.timeline-item>.timeline-footer {
    padding: 10px
}

.timeline>li>.fa,
.timeline>li>.glyphicon,
.timeline>li>.ion {
    width: 30px;
    height: 30px;
    font-size: 15px;
    line-height: 30px;
    position: absolute;
    color: #666;
    background: #d2d6de;
    border-radius: 50%;
    text-align: center;
    left: 18px;
    top: 0
}

.timeline>.time-label>span {
    font-weight: 600;
    padding: 5px;
    display: inline-block;
    background-color: #fff;
    border-radius: 4px
}

.timeline-inverse>li>.timeline-item {
    background: #f0f0f0;
    border: 1px solid #ddd;
    -webkit-box-shadow: none;
    box-shadow: none
}

.timeline-inverse>li>.timeline-item>.timeline-header {
    border-bottom-color: #ddd
}

.btn {
    border-radius: 3px;
    -webkit-box-shadow: none;
    box-shadow: none;
    border: 1px solid transparent
}

.btn.uppercase {
    text-transform: uppercase
}

.btn.btn-flat {
    border-radius: 0;
    -webkit-box-shadow: none;
    -moz-box-shadow: none;
    box-shadow: none;
    border-width: 1px
}

.btn:active {
    -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, .125);
    -moz-box-shadow: inset 0 3px 5px rgba(0, 0, 0, .125);
    box-shadow: inset 0 3px 5px rgba(0, 0, 0, .125)
}

.btn:focus {
    outline: 0
}

.btn.btn-file {
    position: relative;
    overflow: hidden
}

.btn.btn-file>input[type=file] {
    position: absolute;
    top: 0;
    right: 0;
    min-width: 100%;
    min-height: 100%;
    font-size: 100px;
    text-align: right;
    opacity: 0;
    outline: 0;
    background: #fff;
    cursor: inherit;
    display: block
}

.btn-default {
    background-color: #f4f4f4;
    color: #444;
    border-color: #ddd
}

.btn-default.hover,
.btn-default:active,
.btn-default:hover {
    background-color: #e7e7e7
}

.btn-primary {
    background-color: #3c8dbc;
    border-color: #367fa9
}

.btn-primary.hover,
.btn-primary:active,
.btn-primary:hover {
    background-color: #367fa9
}

.btn-success {
    background-color: #00a65a;
    border-color: #008d4c
}

.btn-success.hover,
.btn-success:active,
.btn-success:hover {
    background-color: #008d4c
}

.btn-info {
    background-color: #00c0ef;
    border-color: #00acd6
}

.btn-info.hover,
.btn-info:active,
.btn-info:hover {
    background-color: #00acd6
}

.btn-danger {
    background-color: #dd4b39;
    border-color: #d73925
}

.btn-danger.hover,
.btn-danger:active,
.btn-danger:hover {
    background-color: #d73925
}

.btn-warning {
    background-color: #f39c12;
    border-color: #e08e0b
}

.btn-warning.hover,
.btn-warning:active,
.btn-warning:hover {
    background-color: #e08e0b
}

.btn-outline {
    border: 1px solid #fff;
    background: 0 0;
    color: #fff
}

.btn-outline:active,
.btn-outline:focus,
.btn-outline:hover {
    color: rgba(255, 255, 255, .7);
    border-color: rgba(255, 255, 255, .7)
}

.btn-link {
    -webkit-box-shadow: none;
    box-shadow: none
}

.btn[class*=bg-]:hover {
    -webkit-box-shadow: inset 0 0 100px rgba(0, 0, 0, .2);
    box-shadow: inset 0 0 100px rgba(0, 0, 0, .2)
}

.btn-app {
    border-radius: 3px;
    position: relative;
    padding: 15px 5px;
    margin: 0 0 10px 10px;
    min-width: 80px;
    height: 60px;
    text-align: center;
    color: #666;
    border: 1px solid #ddd;
    background-color: #f4f4f4;
    font-size: 12px
}

.btn-app>.fa,
.btn-app>.glyphicon,
.btn-app>.ion {
    font-size: 20px;
    display: block
}

.btn-app:hover {
    background: #f4f4f4;
    color: #444;
    border-color: #aaa
}

.btn-app:active,
.btn-app:focus {
    -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, .125);
    -moz-box-shadow: inset 0 3px 5px rgba(0, 0, 0, .125);
    box-shadow: inset 0 3px 5px rgba(0, 0, 0, .125)
}

.btn-app>.badge {
    position: absolute;
    top: -3px;
    right: -10px;
    font-size: 10px;
    font-weight: 400
}

.callout {
    border-radius: 3px;
    margin: 0 0 20px 0;
    padding: 15px 30px 15px 15px;
    border-left: 5px solid #eee
}

.callout a {
    color: #fff;
    text-decoration: underline
}

.callout a:hover {
    color: #eee
}

.callout h4 {
    margin-top: 0;
    font-weight: 600
}

.callout p:last-child {
    margin-bottom: 0
}

.callout .highlight,
.callout code {
    background-color: #fff
}

.callout.callout-danger {
    border-color: #c23321
}

.callout.callout-warning {
    border-color: #c87f0a
}

.callout.callout-info {
    border-color: #0097bc
}

.callout.callout-success {
    border-color: #00733e
}

.alert {
    border-radius: 3px
}

.alert h4 {
    font-weight: 600
}

.alert .icon {
    margin-right: 10px
}

.alert .close {
    color: #000;
    opacity: .2
}

.alert .close:hover {
    opacity: .5
}

.alert a {
    color: #fff;
    text-decoration: underline
}

.alert-success {
    border-color: #008d4c
}

.alert-danger,
.alert-error {
    border-color: #d73925
}

.alert-warning {
    border-color: #e08e0b
}

.alert-info {
    border-color: #00acd6
}

.nav>li>a:active,
.nav>li>a:focus,
.nav>li>a:hover {
    color: #444;
    background: #f7f7f7
}

.nav-pills>li>a {
    border-radius: 0;
    border-top: 3px solid transparent;
    color: #444
}

.nav-pills>li>a>.fa,
.nav-pills>li>a>.glyphicon,
.nav-pills>li>a>.ion {
    margin-right: 5px
}

.nav-pills>li.active>a,
.nav-pills>li.active>a:focus,
.nav-pills>li.active>a:hover {
    border-top-color: #3c8dbc
}

.nav-pills>li.active>a {
    font-weight: 600
}

.nav-stacked>li>a {
    border-radius: 0;
    border-top: 0;
    border-left: 3px solid transparent;
    color: #444
}

.nav-stacked>li.active>a,
.nav-stacked>li.active>a:hover {
    background: 0 0;
    color: #444;
    border-top: 0;
    border-left-color: #3c8dbc
}

.nav-stacked>li.header {
    border-bottom: 1px solid #ddd;
    color: #777;
    margin-bottom: 10px;
    padding: 5px 10px;
    text-transform: uppercase
}

.nav-tabs-custom {
    margin-bottom: 20px;
    background: #fff;
    box-shadow: 0 1px 1px rgba(0, 0, 0, .1);
    border-radius: 3px
}

.nav-tabs-custom>.nav-tabs {
    margin: 0;
    border-bottom-color: #f4f4f4;
    border-top-right-radius: 3px;
    border-top-left-radius: 3px
}

.nav-tabs-custom>.nav-tabs>li {
    border-top: 3px solid transparent;
    margin-bottom: -2px;
    margin-right: 5px
}

.nav-tabs-custom>.nav-tabs>li.disabled>a {
    color: #777
}

.nav-tabs-custom>.nav-tabs>li>a {
    color: #444;
    border-radius: 0
}

.nav-tabs-custom>.nav-tabs>li>a.text-muted {
    color: #999
}

.nav-tabs-custom>.nav-tabs>li>a,
.nav-tabs-custom>.nav-tabs>li>a:hover {
    background: 0 0;
    margin: 0
}

.nav-tabs-custom>.nav-tabs>li>a:hover {
    color: #999
}

.nav-tabs-custom>.nav-tabs>li:not(.active)>a:active,
.nav-tabs-custom>.nav-tabs>li:not(.active)>a:focus,
.nav-tabs-custom>.nav-tabs>li:not(.active)>a:hover {
    border-color: transparent
}

.nav-tabs-custom>.nav-tabs>li.active {
    border-top-color: #3c8dbc
}

.nav-tabs-custom>.nav-tabs>li.active:hover>a,
.nav-tabs-custom>.nav-tabs>li.active>a {
    background-color: #fff;
    color: #444
}

.nav-tabs-custom>.nav-tabs>li.active>a {
    border-top-color: transparent;
    border-left-color: #f4f4f4;
    border-right-color: #f4f4f4
}

.nav-tabs-custom>.nav-tabs>li:first-of-type {
    margin-left: 0
}

.nav-tabs-custom>.nav-tabs>li:first-of-type.active>a {
    border-left-color: transparent
}

.nav-tabs-custom>.nav-tabs.pull-right {
    float: none !important
}

.nav-tabs-custom>.nav-tabs.pull-right>li {
    float: right
}

.nav-tabs-custom>.nav-tabs.pull-right>li:first-of-type {
    margin-right: 0
}

.nav-tabs-custom>.nav-tabs.pull-right>li:first-of-type>a {
    border-left-width: 1px
}

.nav-tabs-custom>.nav-tabs.pull-right>li:first-of-type.active>a {
    border-left-color: #f4f4f4;
    border-right-color: transparent
}

.nav-tabs-custom>.nav-tabs>li.header {
    line-height: 35px;
    padding: 0 10px;
    font-size: 20px;
    color: #444
}

.nav-tabs-custom>.nav-tabs>li.header>.fa,
.nav-tabs-custom>.nav-tabs>li.header>.glyphicon,
.nav-tabs-custom>.nav-tabs>li.header>.ion {
    margin-right: 5px
}

.nav-tabs-custom>.tab-content {
    background: #fff;
    padding: 10px;
    border-bottom-right-radius: 3px;
    border-bottom-left-radius: 3px
}

.nav-tabs-custom .dropdown.open>a:active,
.nav-tabs-custom .dropdown.open>a:focus {
    background: 0 0;
    color: #999
}

.nav-tabs-custom.tab-primary>.nav-tabs>li.active {
    border-top-color: #3c8dbc
}

.nav-tabs-custom.tab-info>.nav-tabs>li.active {
    border-top-color: #00c0ef
}

.nav-tabs-custom.tab-danger>.nav-tabs>li.active {
    border-top-color: #dd4b39
}

.nav-tabs-custom.tab-warning>.nav-tabs>li.active {
    border-top-color: #f39c12
}

.nav-tabs-custom.tab-success>.nav-tabs>li.active {
    border-top-color: #00a65a
}

.nav-tabs-custom.tab-default>.nav-tabs>li.active {
    border-top-color: #d2d6de
}

.pagination>li>a {
    background: #fafafa;
    color: #666
}

.pagination.pagination-flat>li>a {
    border-radius: 0 !important
}

.products-list {
    list-style: none;
    margin: 0;
    padding: 0
}

.products-list>.item {
    border-radius: 3px;
    -webkit-box-shadow: 0 1px 1px rgba(0, 0, 0, .1);
    box-shadow: 0 1px 1px rgba(0, 0, 0, .1);
    padding: 10px 0;
    background: #fff
}

.products-list>.item:after,
.products-list>.item:before {
    content: " ";
    display: table
}

.products-list>.item:after {
    clear: both
}

.products-list .product-img {
    float: left
}

.products-list .product-img img {
    width: 50px;
    height: 50px
}

.products-list .product-info {
    margin-left: 60px
}

.products-list .product-title {
    font-weight: 600
}

.products-list .product-description {
    display: block;
    color: #999;
    overflow: hidden;
    white-space: nowrap;
    text-overflow: ellipsis
}

.product-list-in-box>.item {
    -webkit-box-shadow: none;
    box-shadow: none;
    border-radius: 0;
    border-bottom: 1px solid #f4f4f4
}

.product-list-in-box>.item:last-of-type {
    border-bottom-width: 0
}

.table>tbody>tr>td,
.table>tbody>tr>th,
.table>tfoot>tr>td,
.table>tfoot>tr>th,
.table>thead>tr>td,
.table>thead>tr>th {
    border-top: 1px solid #f4f4f4
}

.table>thead>tr>th {
    border-bottom: 2px solid #f4f4f4
}

.table tr td .progress {
    margin-top: 5px
}

.table-bordered {
    border: 1px solid #f4f4f4
}

.table-bordered>tbody>tr>td,
.table-bordered>tbody>tr>th,
.table-bordered>tfoot>tr>td,
.table-bordered>tfoot>tr>th,
.table-bordered>thead>tr>td,
.table-bordered>thead>tr>th {
    border: 1px solid #f4f4f4
}

.table-bordered>thead>tr>td,
.table-bordered>thead>tr>th {
    border-bottom-width: 2px
}

.table.no-border,
.table.no-border td,
.table.no-border th {
    border: 0
}

table.text-center,
table.text-center td,
table.text-center th {
    text-align: center
}

.table.align th {
    text-align: left
}

.table.align td {
    text-align: right
}

.label-default {
    background-color: #d2d6de;
    color: #444
}

.direct-chat .box-body {
    border-bottom-right-radius: 0;
    border-bottom-left-radius: 0;
    position: relative;
    overflow-x: hidden;
    padding: 0
}

.direct-chat.chat-pane-open .direct-chat-contacts {
    -webkit-transform: translate(0, 0);
    -ms-transform: translate(0, 0);
    -o-transform: translate(0, 0);
    transform: translate(0, 0)
}

.direct-chat-messages {
    -webkit-transform: translate(0, 0);
    -ms-transform: translate(0, 0);
    -o-transform: translate(0, 0);
    transform: translate(0, 0);
    padding: 10px;
    height: 250px;
    overflow: auto
}

.direct-chat-msg,
.direct-chat-text {
    display: block
}

.direct-chat-msg {
    margin-bottom: 10px
}

.direct-chat-msg:after,
.direct-chat-msg:before {
    content: " ";
    display: table
}

.direct-chat-msg:after {
    clear: both
}

.direct-chat-contacts,
.direct-chat-messages {
    -webkit-transition: -webkit-transform .5s ease-in-out;
    -moz-transition: -moz-transform .5s ease-in-out;
    -o-transition: -o-transform .5s ease-in-out;
    transition: transform .5s ease-in-out
}

.direct-chat-text {
    border-radius: 5px;
    position: relative;
    padding: 5px 10px;
    background: #d2d6de;
    border: 1px solid #d2d6de;
    margin: 5px 0 0 50px;
    color: #444
}

.direct-chat-text:after,
.direct-chat-text:before {
    position: absolute;
    right: 100%;
    top: 15px;
    border: solid transparent;
    border-right-color: #d2d6de;
    content: ' ';
    height: 0;
    width: 0;
    pointer-events: none
}

.direct-chat-text:after {
    border-width: 5px;
    margin-top: -5px
}

.direct-chat-text:before {
    border-width: 6px;
    margin-top: -6px
}

.right .direct-chat-text {
    margin-right: 50px;
    margin-left: 0
}

.right .direct-chat-text:after,
.right .direct-chat-text:before {
    right: auto;
    left: 100%;
    border-right-color: transparent;
    border-left-color: #d2d6de
}

.direct-chat-img {
    border-radius: 50%;
    float: left;
    width: 40px;
    height: 40px
}

.right .direct-chat-img {
    float: right
}

.direct-chat-info {
    display: block;
    margin-bottom: 2px;
    font-size: 12px
}

.direct-chat-name {
    font-weight: 600
}

.direct-chat-timestamp {
    color: #999
}

.direct-chat-contacts-open .direct-chat-contacts {
    -webkit-transform: translate(0, 0);
    -ms-transform: translate(0, 0);
    -o-transform: translate(0, 0);
    transform: translate(0, 0)
}

.direct-chat-contacts {
    -webkit-transform: translate(101%, 0);
    -ms-transform: translate(101%, 0);
    -o-transform: translate(101%, 0);
    transform: translate(101%, 0);
    position: absolute;
    top: 0;
    bottom: 0;
    height: 250px;
    width: 100%;
    background: #222d32;
    color: #fff;
    overflow: auto
}

.contacts-list>li {
    border-bottom: 1px solid rgba(0, 0, 0, .2);
    padding: 10px;
    margin: 0
}

.contacts-list>li:after,
.contacts-list>li:before {
    content: " ";
    display: table
}

.contacts-list>li:after {
    clear: both
}

.contacts-list>li:last-of-type {
    border-bottom: none
}

.contacts-list-img {
    border-radius: 50%;
    width: 40px;
    float: left
}

.contacts-list-info {
    margin-left: 45px;
    color: #fff
}

.contacts-list-name,
.contacts-list-status {
    display: block
}

.contacts-list-name {
    font-weight: 600
}

.contacts-list-status {
    font-size: 12px
}

.contacts-list-date {
    color: #aaa;
    font-weight: 400
}

.contacts-list-msg {
    color: #999
}

.direct-chat-danger .right>.direct-chat-text {
    background: #dd4b39;
    border-color: #dd4b39;
    color: #fff
}

.direct-chat-danger .right>.direct-chat-text:after,
.direct-chat-danger .right>.direct-chat-text:before {
    border-left-color: #dd4b39
}

.direct-chat-primary .right>.direct-chat-text {
    background: #3c8dbc;
    border-color: #3c8dbc;
    color: #fff
}

.direct-chat-primary .right>.direct-chat-text:after,
.direct-chat-primary .right>.direct-chat-text:before {
    border-left-color: #3c8dbc
}

.direct-chat-warning .right>.direct-chat-text {
    background: #f39c12;
    border-color: #f39c12;
    color: #fff
}

.direct-chat-warning .right>.direct-chat-text:after,
.direct-chat-warning .right>.direct-chat-text:before {
    border-left-color: #f39c12
}

.direct-chat-info .right>.direct-chat-text {
    background: #00c0ef;
    border-color: #00c0ef;
    color: #fff
}

.direct-chat-info .right>.direct-chat-text:after,
.direct-chat-info .right>.direct-chat-text:before {
    border-left-color: #00c0ef
}

.direct-chat-success .right>.direct-chat-text {
    background: #00a65a;
    border-color: #00a65a;
    color: #fff
}

.direct-chat-success .right>.direct-chat-text:after,
.direct-chat-success .right>.direct-chat-text:before {
    border-left-color: #00a65a
}

.users-list>li {
    width: 25%;
    float: left;
    padding: 10px;
    text-align: center
}

.users-list>li img {
    border-radius: 50%;
    max-width: 100%;
    height: auto
}

.users-list>li>a:hover,
.users-list>li>a:hover .users-list-name {
    color: #999
}

.users-list-date,
.users-list-name {
    display: block
}

.users-list-name {
    font-weight: 600;
    color: #444;
    overflow: hidden;
    white-space: nowrap;
    text-overflow: ellipsis
}

.users-list-date {
    color: #999;
    font-size: 12px
}

.carousel-control.left,
.carousel-control.right {
    background-image: none
}

.carousel-control>.fa {
    font-size: 40px;
    position: absolute;
    top: 50%;
    z-index: 5;
    display: inline-block;
    margin-top: -20px
}

.modal {
    background: rgba(0, 0, 0, .3)
}

.modal-content {
    border-radius: 0;
    -webkit-box-shadow: 0 2px 3px rgba(0, 0, 0, .125);
    box-shadow: 0 2px 3px rgba(0, 0, 0, .125);
    border: 0
}

@media (min-width:768px) {
    .modal-content {
        -webkit-box-shadow: 0 2px 3px rgba(0, 0, 0, .125);
        box-shadow: 0 2px 3px rgba(0, 0, 0, .125)
    }
}

.modal-header {
    border-bottom-color: #f4f4f4
}

.modal-footer {
    border-top-color: #f4f4f4
}

.modal-primary .modal-footer,
.modal-primary .modal-header {
    border-color: #307095
}

.modal-warning .modal-footer,
.modal-warning .modal-header {
    border-color: #c87f0a
}

.modal-info .modal-footer,
.modal-info .modal-header {
    border-color: #0097bc
}

.modal-success .modal-footer,
.modal-success .modal-header {
    border-color: #00733e
}

.modal-danger .modal-footer,
.modal-danger .modal-header {
    border-color: #c23321
}

.box-widget {
    border: none;
    position: relative
}

.widget-user .widget-user-header {
    padding: 20px;
    height: 120px;
    border-top-right-radius: 3px;
    border-top-left-radius: 3px
}

.widget-user .widget-user-username {
    margin-top: 0;
    margin-bottom: 5px;
    font-size: 25px;
    font-weight: 300;
    text-shadow: 0 1px 1px rgba(0, 0, 0, .2)
}

.widget-user .widget-user-desc {
    margin-top: 0
}

.widget-user .widget-user-image {
    position: absolute;
    top: 65px;
    left: 50%;
    margin-left: -45px
}

.widget-user .widget-user-image>img {
    width: 90px;
    height: auto;
    border: 3px solid #fff
}

.widget-user .box-footer {
    padding-top: 30px
}

.widget-user-2 .widget-user-header {
    padding: 20px;
    border-top-right-radius: 3px;
    border-top-left-radius: 3px
}

.widget-user-2 .widget-user-username {
    margin-top: 5px;
    margin-bottom: 5px;
    font-size: 25px;
    font-weight: 300
}

.widget-user-2 .widget-user-desc {
    margin-top: 0
}

.widget-user-2 .widget-user-desc,
.widget-user-2 .widget-user-username {
    margin-left: 75px
}

.widget-user-2 .widget-user-image>img {
    width: 65px;
    height: auto;
    float: left
}

.treeview-menu {
    display: none;
    list-style: none;
    padding: 0;
    margin: 0;
    padding-left: 5px
}

.treeview-menu .treeview-menu {
    padding-left: 20px
}

.treeview-menu>li {
    margin: 0
}

.treeview-menu>li>a {
    padding: 5px 5px 5px 15px;
    display: block;
    font-size: 14px
}

.treeview-menu>li>a>.fa,
.treeview-menu>li>a>.glyphicon,
.treeview-menu>li>a>.ion {
    width: 20px
}

.treeview-menu>li>a>.fa-angle-down,
.treeview-menu>li>a>.fa-angle-left,
.treeview-menu>li>a>.pull-right-container>.fa-angle-down,
.treeview-menu>li>a>.pull-right-container>.fa-angle-left {
    width: auto
}

.treeview>ul.treeview-menu {
    overflow: hidden;
    height: auto;
    padding-top: 0 !important;
    padding-bottom: 0 !important
}

.treeview.menu-open>ul.treeview-menu {
    overflow: visible;
    height: auto
}

.mailbox-messages>.table {
    margin: 0
}

.mailbox-controls {
    padding: 5px
}

.mailbox-controls.with-border {
    border-bottom: 1px solid #f4f4f4
}

.mailbox-read-info {
    border-bottom: 1px solid #f4f4f4;
    padding: 10px
}

.mailbox-read-info h3 {
    font-size: 20px;
    margin: 0
}

.mailbox-read-info h5 {
    margin: 0;
    padding: 5px 0 0 0
}

.mailbox-read-time {
    color: #999;
    font-size: 13px
}

.mailbox-read-message {
    padding: 10px
}

.mailbox-attachments li {
    float: left;
    width: 200px;
    border: 1px solid #eee;
    margin-bottom: 10px;
    margin-right: 10px
}

.mailbox-attachment-name {
    font-weight: 700;
    color: #666
}

.mailbox-attachment-icon,
.mailbox-attachment-info,
.mailbox-attachment-size {
    display: block
}

.mailbox-attachment-info {
    padding: 10px;
    background: #f4f4f4
}

.mailbox-attachment-size {
    color: #999;
    font-size: 12px
}

.mailbox-attachment-icon {
    text-align: center;
    font-size: 65px;
    color: #666;
    padding: 20px 10px
}

.mailbox-attachment-icon.has-img {
    padding: 0
}

.mailbox-attachment-icon.has-img>img {
    max-width: 100%;
    height: auto
}

.lockscreen {
    background: #d2d6de
}

.lockscreen-logo {
    font-size: 35px;
    text-align: center;
    margin-bottom: 25px;
    font-weight: 300
}

.lockscreen-logo a {
    color: #444
}

.lockscreen-wrapper {
    max-width: 400px;
    margin: 0 auto;
    margin-top: 10%
}

.lockscreen .lockscreen-name {
    text-align: center;
    font-weight: 600
}

.lockscreen-item {
    border-radius: 4px;
    padding: 0;
    background: #fff;
    position: relative;
    margin: 10px auto 30px auto;
    width: 290px
}

.lockscreen-image {
    border-radius: 50%;
    position: absolute;
    left: -10px;
    top: -25px;
    background: #fff;
    padding: 5px;
    z-index: 10
}

.lockscreen-image>img {
    border-radius: 50%;
    width: 70px;
    height: 70px
}

.lockscreen-credentials {
    margin-left: 70px
}

.lockscreen-credentials .form-control {
    border: 0
}

.lockscreen-credentials .btn {
    background-color: #fff;
    border: 0;
    padding: 0 10px
}

.lockscreen-footer {
    margin-top: 10px
}

.login-logo,
.register-logo {
    font-size: 35px;
    text-align: center;
    margin-bottom: 25px;
    font-weight: 300
}

.login-logo a,
.register-logo a {
    color: #444
}

.login-page,
.register-page {
    height: auto;
    background: #d2d6de
}

.login-box,
.register-box {
    width: 360px;
    margin: 7% auto
}

@media (max-width:768px) {
    .login-box,
    .register-box {
        width: 90%;
        margin-top: 20px
    }
}

.login-box-body,
.register-box-body {
    background: #fff;
    padding: 20px;
    border-top: 0;
    color: #666
}

.login-box-body .form-control-feedback,
.register-box-body .form-control-feedback {
    color: #777
}

.login-box-msg,
.register-box-msg {
    margin: 0;
    text-align: center;
    padding: 0 20px 20px 20px
}

.social-auth-links {
    margin: 10px 0
}

.error-page {
    width: 600px;
    margin: 20px auto 0 auto
}

@media (max-width:991px) {
    .error-page {
        width: 100%
    }
}

.error-page>.headline {
    float: left;
    font-size: 100px;
    font-weight: 300
}

@media (max-width:991px) {
    .error-page>.headline {
        float: none;
        text-align: center
    }
}

.error-page>.error-content {
    margin-left: 190px;
    display: block
}

@media (max-width:991px) {
    .error-page>.error-content {
        margin-left: 0
    }
}

.error-page>.error-content>h3 {
    font-weight: 300;
    font-size: 25px
}

@media (max-width:991px) {
    .error-page>.error-content>h3 {
        text-align: center
    }
}

.invoice {
    position: relative;
    background: #fff;
    border: 1px solid #f4f4f4;
    padding: 20px;
    margin: 10px 25px
}

.invoice-title {
    margin-top: 0
}

.profile-user-img {
    margin: 0 auto;
    width: 100px;
    padding: 3px;
    border: 3px solid #d2d6de
}

.profile-username {
    font-size: 21px;
    margin-top: 5px
}

.post {
    border-bottom: 1px solid #d2d6de;
    margin-bottom: 15px;
    padding-bottom: 15px;
    color: #666
}

.post:last-of-type {
    border-bottom: 0;
    margin-bottom: 0;
    padding-bottom: 0
}

.post .user-block {
    margin-bottom: 15px
}

.btn-social {
    position: relative;
    padding-left: 44px;
    text-align: left;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis
}

.btn-social>:first-child {
    position: absolute;
    left: 0;
    top: 0;
    bottom: 0;
    width: 32px;
    line-height: 34px;
    font-size: 1.6em;
    text-align: center;
    border-right: 1px solid rgba(0, 0, 0, .2)
}

.btn-social.btn-lg {
    padding-left: 61px
}

.btn-social.btn-lg>:first-child {
    line-height: 45px;
    width: 45px;
    font-size: 1.8em
}

.btn-social.btn-sm {
    padding-left: 38px
}

.btn-social.btn-sm>:first-child {
    line-height: 28px;
    width: 28px;
    font-size: 1.4em
}

.btn-social.btn-xs {
    padding-left: 30px
}

.btn-social.btn-xs>:first-child {
    line-height: 20px;
    width: 20px;
    font-size: 1.2em
}

.btn-social-icon {
    position: relative;
    padding-left: 44px;
    text-align: left;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
    height: 34px;
    width: 34px;
    padding: 0
}

.btn-social-icon>:first-child {
    position: absolute;
    left: 0;
    top: 0;
    bottom: 0;
    width: 32px;
    line-height: 34px;
    font-size: 1.6em;
    text-align: center;
    border-right: 1px solid rgba(0, 0, 0, .2)
}

.btn-social-icon.btn-lg {
    padding-left: 61px
}

.btn-social-icon.btn-lg>:first-child {
    line-height: 45px;
    width: 45px;
    font-size: 1.8em
}

.btn-social-icon.btn-sm {
    padding-left: 38px
}

.btn-social-icon.btn-sm>:first-child {
    line-height: 28px;
    width: 28px;
    font-size: 1.4em
}

.btn-social-icon.btn-xs {
    padding-left: 30px
}

.btn-social-icon.btn-xs>:first-child {
    line-height: 20px;
    width: 20px;
    font-size: 1.2em
}

.btn-social-icon>:first-child {
    border: none;
    text-align: center;
    width: 100%
}

.btn-social-icon.btn-lg {
    height: 45px;
    width: 45px;
    padding-left: 0;
    padding-right: 0
}

.btn-social-icon.btn-sm {
    height: 30px;
    width: 30px;
    padding-left: 0;
    padding-right: 0
}

.btn-social-icon.btn-xs {
    height: 22px;
    width: 22px;
    padding-left: 0;
    padding-right: 0
}

.btn-adn {
    color: #fff;
    background-color: #d87a68;
    border-color: rgba(0, 0, 0, .2)
}

.btn-adn.focus,
.btn-adn:focus {
    color: #fff;
    background-color: #ce563f;
    border-color: rgba(0, 0, 0, .2)
}

.btn-adn:hover {
    color: #fff;
    background-color: #ce563f;
    border-color: rgba(0, 0, 0, .2)
}

.btn-adn.active,
.btn-adn:active,
.open>.dropdown-toggle.btn-adn {
    color: #fff;
    background-color: #ce563f;
    border-color: rgba(0, 0, 0, .2)
}

.btn-adn.active.focus,
.btn-adn.active:focus,
.btn-adn.active:hover,
.btn-adn:active.focus,
.btn-adn:active:focus,
.btn-adn:active:hover,
.open>.dropdown-toggle.btn-adn.focus,
.open>.dropdown-toggle.btn-adn:focus,
.open>.dropdown-toggle.btn-adn:hover {
    color: #fff;
    background-color: #b94630;
    border-color: rgba(0, 0, 0, .2)
}

.btn-adn.active,
.btn-adn:active,
.open>.dropdown-toggle.btn-adn {
    background-image: none
}

.btn-adn.disabled.focus,
.btn-adn.disabled:focus,
.btn-adn.disabled:hover,
.btn-adn[disabled].focus,
.btn-adn[disabled]:focus,
.btn-adn[disabled]:hover,
fieldset[disabled] .btn-adn.focus,
fieldset[disabled] .btn-adn:focus,
fieldset[disabled] .btn-adn:hover {
    background-color: #d87a68;
    border-color: rgba(0, 0, 0, .2)
}

.btn-adn .badge {
    color: #d87a68;
    background-color: #fff
}

.btn-bitbucket {
    color: #fff;
    background-color: #205081;
    border-color: rgba(0, 0, 0, .2)
}

.btn-bitbucket.focus,
.btn-bitbucket:focus {
    color: #fff;
    background-color: #163758;
    border-color: rgba(0, 0, 0, .2)
}

.btn-bitbucket:hover {
    color: #fff;
    background-color: #163758;
    border-color: rgba(0, 0, 0, .2)
}

.btn-bitbucket.active,
.btn-bitbucket:active,
.open>.dropdown-toggle.btn-bitbucket {
    color: #fff;
    background-color: #163758;
    border-color: rgba(0, 0, 0, .2)
}

.btn-bitbucket.active.focus,
.btn-bitbucket.active:focus,
.btn-bitbucket.active:hover,
.btn-bitbucket:active.focus,
.btn-bitbucket:active:focus,
.btn-bitbucket:active:hover,
.open>.dropdown-toggle.btn-bitbucket.focus,
.open>.dropdown-toggle.btn-bitbucket:focus,
.open>.dropdown-toggle.btn-bitbucket:hover {
    color: #fff;
    background-color: #0f253c;
    border-color: rgba(0, 0, 0, .2)
}

.btn-bitbucket.active,
.btn-bitbucket:active,
.open>.dropdown-toggle.btn-bitbucket {
    background-image: none
}

.btn-bitbucket.disabled.focus,
.btn-bitbucket.disabled:focus,
.btn-bitbucket.disabled:hover,
.btn-bitbucket[disabled].focus,
.btn-bitbucket[disabled]:focus,
.btn-bitbucket[disabled]:hover,
fieldset[disabled] .btn-bitbucket.focus,
fieldset[disabled] .btn-bitbucket:focus,
fieldset[disabled] .btn-bitbucket:hover {
    background-color: #205081;
    border-color: rgba(0, 0, 0, .2)
}

.btn-bitbucket .badge {
    color: #205081;
    background-color: #fff
}

.btn-dropbox {
    color: #fff;
    background-color: #1087dd;
    border-color: rgba(0, 0, 0, .2)
}

.btn-dropbox.focus,
.btn-dropbox:focus {
    color: #fff;
    background-color: #0d6aad;
    border-color: rgba(0, 0, 0, .2)
}

.btn-dropbox:hover {
    color: #fff;
    background-color: #0d6aad;
    border-color: rgba(0, 0, 0, .2)
}

.btn-dropbox.active,
.btn-dropbox:active,
.open>.dropdown-toggle.btn-dropbox {
    color: #fff;
    background-color: #0d6aad;
    border-color: rgba(0, 0, 0, .2)
}

.btn-dropbox.active.focus,
.btn-dropbox.active:focus,
.btn-dropbox.active:hover,
.btn-dropbox:active.focus,
.btn-dropbox:active:focus,
.btn-dropbox:active:hover,
.open>.dropdown-toggle.btn-dropbox.focus,
.open>.dropdown-toggle.btn-dropbox:focus,
.open>.dropdown-toggle.btn-dropbox:hover {
    color: #fff;
    background-color: #0a568c;
    border-color: rgba(0, 0, 0, .2)
}

.btn-dropbox.active,
.btn-dropbox:active,
.open>.dropdown-toggle.btn-dropbox {
    background-image: none
}

.btn-dropbox.disabled.focus,
.btn-dropbox.disabled:focus,
.btn-dropbox.disabled:hover,
.btn-dropbox[disabled].focus,
.btn-dropbox[disabled]:focus,
.btn-dropbox[disabled]:hover,
fieldset[disabled] .btn-dropbox.focus,
fieldset[disabled] .btn-dropbox:focus,
fieldset[disabled] .btn-dropbox:hover {
    background-color: #1087dd;
    border-color: rgba(0, 0, 0, .2)
}

.btn-dropbox .badge {
    color: #1087dd;
    background-color: #fff
}

.btn-facebook {
    color: #fff;
    background-color: #3b5998;
    border-color: rgba(0, 0, 0, .2)
}

.btn-facebook.focus,
.btn-facebook:focus {
    color: #fff;
    background-color: #2d4373;
    border-color: rgba(0, 0, 0, .2)
}

.btn-facebook:hover {
    color: #fff;
    background-color: #2d4373;
    border-color: rgba(0, 0, 0, .2)
}

.btn-facebook.active,
.btn-facebook:active,
.open>.dropdown-toggle.btn-facebook {
    color: #fff;
    background-color: #2d4373;
    border-color: rgba(0, 0, 0, .2)
}

.btn-facebook.active.focus,
.btn-facebook.active:focus,
.btn-facebook.active:hover,
.btn-facebook:active.focus,
.btn-facebook:active:focus,
.btn-facebook:active:hover,
.open>.dropdown-toggle.btn-facebook.focus,
.open>.dropdown-toggle.btn-facebook:focus,
.open>.dropdown-toggle.btn-facebook:hover {
    color: #fff;
    background-color: #23345a;
    border-color: rgba(0, 0, 0, .2)
}

.btn-facebook.active,
.btn-facebook:active,
.open>.dropdown-toggle.btn-facebook {
    background-image: none
}

.btn-facebook.disabled.focus,
.btn-facebook.disabled:focus,
.btn-facebook.disabled:hover,
.btn-facebook[disabled].focus,
.btn-facebook[disabled]:focus,
.btn-facebook[disabled]:hover,
fieldset[disabled] .btn-facebook.focus,
fieldset[disabled] .btn-facebook:focus,
fieldset[disabled] .btn-facebook:hover {
    background-color: #3b5998;
    border-color: rgba(0, 0, 0, .2)
}

.btn-facebook .badge {
    color: #3b5998;
    background-color: #fff
}

.btn-flickr {
    color: #fff;
    background-color: #ff0084;
    border-color: rgba(0, 0, 0, .2)
}

.btn-flickr.focus,
.btn-flickr:focus {
    color: #fff;
    background-color: #cc006a;
    border-color: rgba(0, 0, 0, .2)
}

.btn-flickr:hover {
    color: #fff;
    background-color: #cc006a;
    border-color: rgba(0, 0, 0, .2)
}

.btn-flickr.active,
.btn-flickr:active,
.open>.dropdown-toggle.btn-flickr {
    color: #fff;
    background-color: #cc006a;
    border-color: rgba(0, 0, 0, .2)
}

.btn-flickr.active.focus,
.btn-flickr.active:focus,
.btn-flickr.active:hover,
.btn-flickr:active.focus,
.btn-flickr:active:focus,
.btn-flickr:active:hover,
.open>.dropdown-toggle.btn-flickr.focus,
.open>.dropdown-toggle.btn-flickr:focus,
.open>.dropdown-toggle.btn-flickr:hover {
    color: #fff;
    background-color: #a80057;
    border-color: rgba(0, 0, 0, .2)
}

.btn-flickr.active,
.btn-flickr:active,
.open>.dropdown-toggle.btn-flickr {
    background-image: none
}

.btn-flickr.disabled.focus,
.btn-flickr.disabled:focus,
.btn-flickr.disabled:hover,
.btn-flickr[disabled].focus,
.btn-flickr[disabled]:focus,
.btn-flickr[disabled]:hover,
fieldset[disabled] .btn-flickr.focus,
fieldset[disabled] .btn-flickr:focus,
fieldset[disabled] .btn-flickr:hover {
    background-color: #ff0084;
    border-color: rgba(0, 0, 0, .2)
}

.btn-flickr .badge {
    color: #ff0084;
    background-color: #fff
}

.btn-foursquare {
    color: #fff;
    background-color: #f94877;
    border-color: rgba(0, 0, 0, .2)
}

.btn-foursquare.focus,
.btn-foursquare:focus {
    color: #fff;
    background-color: #f71752;
    border-color: rgba(0, 0, 0, .2)
}

.btn-foursquare:hover {
    color: #fff;
    background-color: #f71752;
    border-color: rgba(0, 0, 0, .2)
}

.btn-foursquare.active,
.btn-foursquare:active,
.open>.dropdown-toggle.btn-foursquare {
    color: #fff;
    background-color: #f71752;
    border-color: rgba(0, 0, 0, .2)
}

.btn-foursquare.active.focus,
.btn-foursquare.active:focus,
.btn-foursquare.active:hover,
.btn-foursquare:active.focus,
.btn-foursquare:active:focus,
.btn-foursquare:active:hover,
.open>.dropdown-toggle.btn-foursquare.focus,
.open>.dropdown-toggle.btn-foursquare:focus,
.open>.dropdown-toggle.btn-foursquare:hover {
    color: #fff;
    background-color: #e30742;
    border-color: rgba(0, 0, 0, .2)
}

.btn-foursquare.active,
.btn-foursquare:active,
.open>.dropdown-toggle.btn-foursquare {
    background-image: none
}

.btn-foursquare.disabled.focus,
.btn-foursquare.disabled:focus,
.btn-foursquare.disabled:hover,
.btn-foursquare[disabled].focus,
.btn-foursquare[disabled]:focus,
.btn-foursquare[disabled]:hover,
fieldset[disabled] .btn-foursquare.focus,
fieldset[disabled] .btn-foursquare:focus,
fieldset[disabled] .btn-foursquare:hover {
    background-color: #f94877;
    border-color: rgba(0, 0, 0, .2)
}

.btn-foursquare .badge {
    color: #f94877;
    background-color: #fff
}

.btn-github {
    color: #fff;
    background-color: #444;
    border-color: rgba(0, 0, 0, .2)
}

.btn-github.focus,
.btn-github:focus {
    color: #fff;
    background-color: #2b2b2b;
    border-color: rgba(0, 0, 0, .2)
}

.btn-github:hover {
    color: #fff;
    background-color: #2b2b2b;
    border-color: rgba(0, 0, 0, .2)
}

.btn-github.active,
.btn-github:active,
.open>.dropdown-toggle.btn-github {
    color: #fff;
    background-color: #2b2b2b;
    border-color: rgba(0, 0, 0, .2)
}

.btn-github.active.focus,
.btn-github.active:focus,
.btn-github.active:hover,
.btn-github:active.focus,
.btn-github:active:focus,
.btn-github:active:hover,
.open>.dropdown-toggle.btn-github.focus,
.open>.dropdown-toggle.btn-github:focus,
.open>.dropdown-toggle.btn-github:hover {
    color: #fff;
    background-color: #191919;
    border-color: rgba(0, 0, 0, .2)
}

.btn-github.active,
.btn-github:active,
.open>.dropdown-toggle.btn-github {
    background-image: none
}

.btn-github.disabled.focus,
.btn-github.disabled:focus,
.btn-github.disabled:hover,
.btn-github[disabled].focus,
.btn-github[disabled]:focus,
.btn-github[disabled]:hover,
fieldset[disabled] .btn-github.focus,
fieldset[disabled] .btn-github:focus,
fieldset[disabled] .btn-github:hover {
    background-color: #444;
    border-color: rgba(0, 0, 0, .2)
}

.btn-github .badge {
    color: #444;
    background-color: #fff
}

.btn-google {
    color: #fff;
    background-color: #dd4b39;
    border-color: rgba(0, 0, 0, .2)
}

.btn-google.focus,
.btn-google:focus {
    color: #fff;
    background-color: #c23321;
    border-color: rgba(0, 0, 0, .2)
}

.btn-google:hover {
    color: #fff;
    background-color: #c23321;
    border-color: rgba(0, 0, 0, .2)
}

.btn-google.active,
.btn-google:active,
.open>.dropdown-toggle.btn-google {
    color: #fff;
    background-color: #c23321;
    border-color: rgba(0, 0, 0, .2)
}

.btn-google.active.focus,
.btn-google.active:focus,
.btn-google.active:hover,
.btn-google:active.focus,
.btn-google:active:focus,
.btn-google:active:hover,
.open>.dropdown-toggle.btn-google.focus,
.open>.dropdown-toggle.btn-google:focus,
.open>.dropdown-toggle.btn-google:hover {
    color: #fff;
    background-color: #a32b1c;
    border-color: rgba(0, 0, 0, .2)
}

.btn-google.active,
.btn-google:active,
.open>.dropdown-toggle.btn-google {
    background-image: none
}

.btn-google.disabled.focus,
.btn-google.disabled:focus,
.btn-google.disabled:hover,
.btn-google[disabled].focus,
.btn-google[disabled]:focus,
.btn-google[disabled]:hover,
fieldset[disabled] .btn-google.focus,
fieldset[disabled] .btn-google:focus,
fieldset[disabled] .btn-google:hover {
    background-color: #dd4b39;
    border-color: rgba(0, 0, 0, .2)
}

.btn-google .badge {
    color: #dd4b39;
    background-color: #fff
}

.btn-instagram {
    color: #fff;
    background-color: #3f729b;
    border-color: rgba(0, 0, 0, .2)
}

.btn-instagram.focus,
.btn-instagram:focus {
    color: #fff;
    background-color: #305777;
    border-color: rgba(0, 0, 0, .2)
}

.btn-instagram:hover {
    color: #fff;
    background-color: #305777;
    border-color: rgba(0, 0, 0, .2)
}

.btn-instagram.active,
.btn-instagram:active,
.open>.dropdown-toggle.btn-instagram {
    color: #fff;
    background-color: #305777;
    border-color: rgba(0, 0, 0, .2)
}

.btn-instagram.active.focus,
.btn-instagram.active:focus,
.btn-instagram.active:hover,
.btn-instagram:active.focus,
.btn-instagram:active:focus,
.btn-instagram:active:hover,
.open>.dropdown-toggle.btn-instagram.focus,
.open>.dropdown-toggle.btn-instagram:focus,
.open>.dropdown-toggle.btn-instagram:hover {
    color: #fff;
    background-color: #26455d;
    border-color: rgba(0, 0, 0, .2)
}

.btn-instagram.active,
.btn-instagram:active,
.open>.dropdown-toggle.btn-instagram {
    background-image: none
}

.btn-instagram.disabled.focus,
.btn-instagram.disabled:focus,
.btn-instagram.disabled:hover,
.btn-instagram[disabled].focus,
.btn-instagram[disabled]:focus,
.btn-instagram[disabled]:hover,
fieldset[disabled] .btn-instagram.focus,
fieldset[disabled] .btn-instagram:focus,
fieldset[disabled] .btn-instagram:hover {
    background-color: #3f729b;
    border-color: rgba(0, 0, 0, .2)
}

.btn-instagram .badge {
    color: #3f729b;
    background-color: #fff
}

.btn-linkedin {
    color: #fff;
    background-color: #007bb6;
    border-color: rgba(0, 0, 0, .2)
}

.btn-linkedin.focus,
.btn-linkedin:focus {
    color: #fff;
    background-color: #005983;
    border-color: rgba(0, 0, 0, .2)
}

.btn-linkedin:hover {
    color: #fff;
    background-color: #005983;
    border-color: rgba(0, 0, 0, .2)
}

.btn-linkedin.active,
.btn-linkedin:active,
.open>.dropdown-toggle.btn-linkedin {
    color: #fff;
    background-color: #005983;
    border-color: rgba(0, 0, 0, .2)
}

.btn-linkedin.active.focus,
.btn-linkedin.active:focus,
.btn-linkedin.active:hover,
.btn-linkedin:active.focus,
.btn-linkedin:active:focus,
.btn-linkedin:active:hover,
.open>.dropdown-toggle.btn-linkedin.focus,
.open>.dropdown-toggle.btn-linkedin:focus,
.open>.dropdown-toggle.btn-linkedin:hover {
    color: #fff;
    background-color: #00405f;
    border-color: rgba(0, 0, 0, .2)
}

.btn-linkedin.active,
.btn-linkedin:active,
.open>.dropdown-toggle.btn-linkedin {
    background-image: none
}

.btn-linkedin.disabled.focus,
.btn-linkedin.disabled:focus,
.btn-linkedin.disabled:hover,
.btn-linkedin[disabled].focus,
.btn-linkedin[disabled]:focus,
.btn-linkedin[disabled]:hover,
fieldset[disabled] .btn-linkedin.focus,
fieldset[disabled] .btn-linkedin:focus,
fieldset[disabled] .btn-linkedin:hover {
    background-color: #007bb6;
    border-color: rgba(0, 0, 0, .2)
}

.btn-linkedin .badge {
    color: #007bb6;
    background-color: #fff
}

.btn-microsoft {
    color: #fff;
    background-color: #2672ec;
    border-color: rgba(0, 0, 0, .2)
}

.btn-microsoft.focus,
.btn-microsoft:focus {
    color: #fff;
    background-color: #125acd;
    border-color: rgba(0, 0, 0, .2)
}

.btn-microsoft:hover {
    color: #fff;
    background-color: #125acd;
    border-color: rgba(0, 0, 0, .2)
}

.btn-microsoft.active,
.btn-microsoft:active,
.open>.dropdown-toggle.btn-microsoft {
    color: #fff;
    background-color: #125acd;
    border-color: rgba(0, 0, 0, .2)
}

.btn-microsoft.active.focus,
.btn-microsoft.active:focus,
.btn-microsoft.active:hover,
.btn-microsoft:active.focus,
.btn-microsoft:active:focus,
.btn-microsoft:active:hover,
.open>.dropdown-toggle.btn-microsoft.focus,
.open>.dropdown-toggle.btn-microsoft:focus,
.open>.dropdown-toggle.btn-microsoft:hover {
    color: #fff;
    background-color: #0f4bac;
    border-color: rgba(0, 0, 0, .2)
}

.btn-microsoft.active,
.btn-microsoft:active,
.open>.dropdown-toggle.btn-microsoft {
    background-image: none
}

.btn-microsoft.disabled.focus,
.btn-microsoft.disabled:focus,
.btn-microsoft.disabled:hover,
.btn-microsoft[disabled].focus,
.btn-microsoft[disabled]:focus,
.btn-microsoft[disabled]:hover,
fieldset[disabled] .btn-microsoft.focus,
fieldset[disabled] .btn-microsoft:focus,
fieldset[disabled] .btn-microsoft:hover {
    background-color: #2672ec;
    border-color: rgba(0, 0, 0, .2)
}

.btn-microsoft .badge {
    color: #2672ec;
    background-color: #fff
}

.btn-openid {
    color: #fff;
    background-color: #f7931e;
    border-color: rgba(0, 0, 0, .2)
}

.btn-openid.focus,
.btn-openid:focus {
    color: #fff;
    background-color: #da7908;
    border-color: rgba(0, 0, 0, .2)
}

.btn-openid:hover {
    color: #fff;
    background-color: #da7908;
    border-color: rgba(0, 0, 0, .2)
}

.btn-openid.active,
.btn-openid:active,
.open>.dropdown-toggle.btn-openid {
    color: #fff;
    background-color: #da7908;
    border-color: rgba(0, 0, 0, .2)
}

.btn-openid.active.focus,
.btn-openid.active:focus,
.btn-openid.active:hover,
.btn-openid:active.focus,
.btn-openid:active:focus,
.btn-openid:active:hover,
.open>.dropdown-toggle.btn-openid.focus,
.open>.dropdown-toggle.btn-openid:focus,
.open>.dropdown-toggle.btn-openid:hover {
    color: #fff;
    background-color: #b86607;
    border-color: rgba(0, 0, 0, .2)
}

.btn-openid.active,
.btn-openid:active,
.open>.dropdown-toggle.btn-openid {
    background-image: none
}

.btn-openid.disabled.focus,
.btn-openid.disabled:focus,
.btn-openid.disabled:hover,
.btn-openid[disabled].focus,
.btn-openid[disabled]:focus,
.btn-openid[disabled]:hover,
fieldset[disabled] .btn-openid.focus,
fieldset[disabled] .btn-openid:focus,
fieldset[disabled] .btn-openid:hover {
    background-color: #f7931e;
    border-color: rgba(0, 0, 0, .2)
}

.btn-openid .badge {
    color: #f7931e;
    background-color: #fff
}

.btn-pinterest {
    color: #fff;
    background-color: #cb2027;
    border-color: rgba(0, 0, 0, .2)
}

.btn-pinterest.focus,
.btn-pinterest:focus {
    color: #fff;
    background-color: #9f191f;
    border-color: rgba(0, 0, 0, .2)
}

.btn-pinterest:hover {
    color: #fff;
    background-color: #9f191f;
    border-color: rgba(0, 0, 0, .2)
}

.btn-pinterest.active,
.btn-pinterest:active,
.open>.dropdown-toggle.btn-pinterest {
    color: #fff;
    background-color: #9f191f;
    border-color: rgba(0, 0, 0, .2)
}

.btn-pinterest.active.focus,
.btn-pinterest.active:focus,
.btn-pinterest.active:hover,
.btn-pinterest:active.focus,
.btn-pinterest:active:focus,
.btn-pinterest:active:hover,
.open>.dropdown-toggle.btn-pinterest.focus,
.open>.dropdown-toggle.btn-pinterest:focus,
.open>.dropdown-toggle.btn-pinterest:hover {
    color: #fff;
    background-color: #801419;
    border-color: rgba(0, 0, 0, .2)
}

.btn-pinterest.active,
.btn-pinterest:active,
.open>.dropdown-toggle.btn-pinterest {
    background-image: none
}

.btn-pinterest.disabled.focus,
.btn-pinterest.disabled:focus,
.btn-pinterest.disabled:hover,
.btn-pinterest[disabled].focus,
.btn-pinterest[disabled]:focus,
.btn-pinterest[disabled]:hover,
fieldset[disabled] .btn-pinterest.focus,
fieldset[disabled] .btn-pinterest:focus,
fieldset[disabled] .btn-pinterest:hover {
    background-color: #cb2027;
    border-color: rgba(0, 0, 0, .2)
}

.btn-pinterest .badge {
    color: #cb2027;
    background-color: #fff
}

.btn-reddit {
    color: #000;
    background-color: #eff7ff;
    border-color: rgba(0, 0, 0, .2)
}

.btn-reddit.focus,
.btn-reddit:focus {
    color: #000;
    background-color: #bcddff;
    border-color: rgba(0, 0, 0, .2)
}

.btn-reddit:hover {
    color: #000;
    background-color: #bcddff;
    border-color: rgba(0, 0, 0, .2)
}

.btn-reddit.active,
.btn-reddit:active,
.open>.dropdown-toggle.btn-reddit {
    color: #000;
    background-color: #bcddff;
    border-color: rgba(0, 0, 0, .2)
}

.btn-reddit.active.focus,
.btn-reddit.active:focus,
.btn-reddit.active:hover,
.btn-reddit:active.focus,
.btn-reddit:active:focus,
.btn-reddit:active:hover,
.open>.dropdown-toggle.btn-reddit.focus,
.open>.dropdown-toggle.btn-reddit:focus,
.open>.dropdown-toggle.btn-reddit:hover {
    color: #000;
    background-color: #98ccff;
    border-color: rgba(0, 0, 0, .2)
}

.btn-reddit.active,
.btn-reddit:active,
.open>.dropdown-toggle.btn-reddit {
    background-image: none
}

.btn-reddit.disabled.focus,
.btn-reddit.disabled:focus,
.btn-reddit.disabled:hover,
.btn-reddit[disabled].focus,
.btn-reddit[disabled]:focus,
.btn-reddit[disabled]:hover,
fieldset[disabled] .btn-reddit.focus,
fieldset[disabled] .btn-reddit:focus,
fieldset[disabled] .btn-reddit:hover {
    background-color: #eff7ff;
    border-color: rgba(0, 0, 0, .2)
}

.btn-reddit .badge {
    color: #eff7ff;
    background-color: #000
}

.btn-soundcloud {
    color: #fff;
    background-color: #f50;
    border-color: rgba(0, 0, 0, .2)
}

.btn-soundcloud.focus,
.btn-soundcloud:focus {
    color: #fff;
    background-color: #c40;
    border-color: rgba(0, 0, 0, .2)
}

.btn-soundcloud:hover {
    color: #fff;
    background-color: #c40;
    border-color: rgba(0, 0, 0, .2)
}

.btn-soundcloud.active,
.btn-soundcloud:active,
.open>.dropdown-toggle.btn-soundcloud {
    color: #fff;
    background-color: #c40;
    border-color: rgba(0, 0, 0, .2)
}

.btn-soundcloud.active.focus,
.btn-soundcloud.active:focus,
.btn-soundcloud.active:hover,
.btn-soundcloud:active.focus,
.btn-soundcloud:active:focus,
.btn-soundcloud:active:hover,
.open>.dropdown-toggle.btn-soundcloud.focus,
.open>.dropdown-toggle.btn-soundcloud:focus,
.open>.dropdown-toggle.btn-soundcloud:hover {
    color: #fff;
    background-color: #a83800;
    border-color: rgba(0, 0, 0, .2)
}

.btn-soundcloud.active,
.btn-soundcloud:active,
.open>.dropdown-toggle.btn-soundcloud {
    background-image: none
}

.btn-soundcloud.disabled.focus,
.btn-soundcloud.disabled:focus,
.btn-soundcloud.disabled:hover,
.btn-soundcloud[disabled].focus,
.btn-soundcloud[disabled]:focus,
.btn-soundcloud[disabled]:hover,
fieldset[disabled] .btn-soundcloud.focus,
fieldset[disabled] .btn-soundcloud:focus,
fieldset[disabled] .btn-soundcloud:hover {
    background-color: #f50;
    border-color: rgba(0, 0, 0, .2)
}

.btn-soundcloud .badge {
    color: #f50;
    background-color: #fff
}

.btn-tumblr {
    color: #fff;
    background-color: #2c4762;
    border-color: rgba(0, 0, 0, .2)
}

.btn-tumblr.focus,
.btn-tumblr:focus {
    color: #fff;
    background-color: #1c2d3f;
    border-color: rgba(0, 0, 0, .2)
}

.btn-tumblr:hover {
    color: #fff;
    background-color: #1c2d3f;
    border-color: rgba(0, 0, 0, .2)
}

.btn-tumblr.active,
.btn-tumblr:active,
.open>.dropdown-toggle.btn-tumblr {
    color: #fff;
    background-color: #1c2d3f;
    border-color: rgba(0, 0, 0, .2)
}

.btn-tumblr.active.focus,
.btn-tumblr.active:focus,
.btn-tumblr.active:hover,
.btn-tumblr:active.focus,
.btn-tumblr:active:focus,
.btn-tumblr:active:hover,
.open>.dropdown-toggle.btn-tumblr.focus,
.open>.dropdown-toggle.btn-tumblr:focus,
.open>.dropdown-toggle.btn-tumblr:hover {
    color: #fff;
    background-color: #111c26;
    border-color: rgba(0, 0, 0, .2)
}

.btn-tumblr.active,
.btn-tumblr:active,
.open>.dropdown-toggle.btn-tumblr {
    background-image: none
}

.btn-tumblr.disabled.focus,
.btn-tumblr.disabled:focus,
.btn-tumblr.disabled:hover,
.btn-tumblr[disabled].focus,
.btn-tumblr[disabled]:focus,
.btn-tumblr[disabled]:hover,
fieldset[disabled] .btn-tumblr.focus,
fieldset[disabled] .btn-tumblr:focus,
fieldset[disabled] .btn-tumblr:hover {
    background-color: #2c4762;
    border-color: rgba(0, 0, 0, .2)
}

.btn-tumblr .badge {
    color: #2c4762;
    background-color: #fff
}

.btn-twitter {
    color: #fff;
    background-color: #55acee;
    border-color: rgba(0, 0, 0, .2)
}

.btn-twitter.focus,
.btn-twitter:focus {
    color: #fff;
    background-color: #2795e9;
    border-color: rgba(0, 0, 0, .2)
}

.btn-twitter:hover {
    color: #fff;
    background-color: #2795e9;
    border-color: rgba(0, 0, 0, .2)
}

.btn-twitter.active,
.btn-twitter:active,
.open>.dropdown-toggle.btn-twitter {
    color: #fff;
    background-color: #2795e9;
    border-color: rgba(0, 0, 0, .2)
}

.btn-twitter.active.focus,
.btn-twitter.active:focus,
.btn-twitter.active:hover,
.btn-twitter:active.focus,
.btn-twitter:active:focus,
.btn-twitter:active:hover,
.open>.dropdown-toggle.btn-twitter.focus,
.open>.dropdown-toggle.btn-twitter:focus,
.open>.dropdown-toggle.btn-twitter:hover {
    color: #fff;
    background-color: #1583d7;
    border-color: rgba(0, 0, 0, .2)
}

.btn-twitter.active,
.btn-twitter:active,
.open>.dropdown-toggle.btn-twitter {
    background-image: none
}

.btn-twitter.disabled.focus,
.btn-twitter.disabled:focus,
.btn-twitter.disabled:hover,
.btn-twitter[disabled].focus,
.btn-twitter[disabled]:focus,
.btn-twitter[disabled]:hover,
fieldset[disabled] .btn-twitter.focus,
fieldset[disabled] .btn-twitter:focus,
fieldset[disabled] .btn-twitter:hover {
    background-color: #55acee;
    border-color: rgba(0, 0, 0, .2)
}

.btn-twitter .badge {
    color: #55acee;
    background-color: #fff
}

.btn-vimeo {
    color: #fff;
    background-color: #1ab7ea;
    border-color: rgba(0, 0, 0, .2)
}

.btn-vimeo.focus,
.btn-vimeo:focus {
    color: #fff;
    background-color: #1295bf;
    border-color: rgba(0, 0, 0, .2)
}

.btn-vimeo:hover {
    color: #fff;
    background-color: #1295bf;
    border-color: rgba(0, 0, 0, .2)
}

.btn-vimeo.active,
.btn-vimeo:active,
.open>.dropdown-toggle.btn-vimeo {
    color: #fff;
    background-color: #1295bf;
    border-color: rgba(0, 0, 0, .2)
}

.btn-vimeo.active.focus,
.btn-vimeo.active:focus,
.btn-vimeo.active:hover,
.btn-vimeo:active.focus,
.btn-vimeo:active:focus,
.btn-vimeo:active:hover,
.open>.dropdown-toggle.btn-vimeo.focus,
.open>.dropdown-toggle.btn-vimeo:focus,
.open>.dropdown-toggle.btn-vimeo:hover {
    color: #fff;
    background-color: #0f7b9f;
    border-color: rgba(0, 0, 0, .2)
}

.btn-vimeo.active,
.btn-vimeo:active,
.open>.dropdown-toggle.btn-vimeo {
    background-image: none
}

.btn-vimeo.disabled.focus,
.btn-vimeo.disabled:focus,
.btn-vimeo.disabled:hover,
.btn-vimeo[disabled].focus,
.btn-vimeo[disabled]:focus,
.btn-vimeo[disabled]:hover,
fieldset[disabled] .btn-vimeo.focus,
fieldset[disabled] .btn-vimeo:focus,
fieldset[disabled] .btn-vimeo:hover {
    background-color: #1ab7ea;
    border-color: rgba(0, 0, 0, .2)
}

.btn-vimeo .badge {
    color: #1ab7ea;
    background-color: #fff
}

.btn-vk {
    color: #fff;
    background-color: #587ea3;
    border-color: rgba(0, 0, 0, .2)
}

.btn-vk.focus,
.btn-vk:focus {
    color: #fff;
    background-color: #466482;
    border-color: rgba(0, 0, 0, .2)
}

.btn-vk:hover {
    color: #fff;
    background-color: #466482;
    border-color: rgba(0, 0, 0, .2)
}

.btn-vk.active,
.btn-vk:active,
.open>.dropdown-toggle.btn-vk {
    color: #fff;
    background-color: #466482;
    border-color: rgba(0, 0, 0, .2)
}

.btn-vk.active.focus,
.btn-vk.active:focus,
.btn-vk.active:hover,
.btn-vk:active.focus,
.btn-vk:active:focus,
.btn-vk:active:hover,
.open>.dropdown-toggle.btn-vk.focus,
.open>.dropdown-toggle.btn-vk:focus,
.open>.dropdown-toggle.btn-vk:hover {
    color: #fff;
    background-color: #3a526b;
    border-color: rgba(0, 0, 0, .2)
}

.btn-vk.active,
.btn-vk:active,
.open>.dropdown-toggle.btn-vk {
    background-image: none
}

.btn-vk.disabled.focus,
.btn-vk.disabled:focus,
.btn-vk.disabled:hover,
.btn-vk[disabled].focus,
.btn-vk[disabled]:focus,
.btn-vk[disabled]:hover,
fieldset[disabled] .btn-vk.focus,
fieldset[disabled] .btn-vk:focus,
fieldset[disabled] .btn-vk:hover {
    background-color: #587ea3;
    border-color: rgba(0, 0, 0, .2)
}

.btn-vk .badge {
    color: #587ea3;
    background-color: #fff
}

.btn-yahoo {
    color: #fff;
    background-color: #720e9e;
    border-color: rgba(0, 0, 0, .2)
}

.btn-yahoo.focus,
.btn-yahoo:focus {
    color: #fff;
    background-color: #500a6f;
    border-color: rgba(0, 0, 0, .2)
}

.btn-yahoo:hover {
    color: #fff;
    background-color: #500a6f;
    border-color: rgba(0, 0, 0, .2)
}

.btn-yahoo.active,
.btn-yahoo:active,
.open>.dropdown-toggle.btn-yahoo {
    color: #fff;
    background-color: #500a6f;
    border-color: rgba(0, 0, 0, .2)
}

.btn-yahoo.active.focus,
.btn-yahoo.active:focus,
.btn-yahoo.active:hover,
.btn-yahoo:active.focus,
.btn-yahoo:active:focus,
.btn-yahoo:active:hover,
.open>.dropdown-toggle.btn-yahoo.focus,
.open>.dropdown-toggle.btn-yahoo:focus,
.open>.dropdown-toggle.btn-yahoo:hover {
    color: #fff;
    background-color: #39074e;
    border-color: rgba(0, 0, 0, .2)
}

.btn-yahoo.active,
.btn-yahoo:active,
.open>.dropdown-toggle.btn-yahoo {
    background-image: none
}

.btn-yahoo.disabled.focus,
.btn-yahoo.disabled:focus,
.btn-yahoo.disabled:hover,
.btn-yahoo[disabled].focus,
.btn-yahoo[disabled]:focus,
.btn-yahoo[disabled]:hover,
fieldset[disabled] .btn-yahoo.focus,
fieldset[disabled] .btn-yahoo:focus,
fieldset[disabled] .btn-yahoo:hover {
    background-color: #720e9e;
    border-color: rgba(0, 0, 0, .2)
}

.btn-yahoo .badge {
    color: #720e9e;
    background-color: #fff
}

.fc-button {
    background: #f4f4f4;
    background-image: none;
    color: #444;
    border-color: #ddd;
    border-bottom-color: #ddd
}

.fc-button.hover,
.fc-button:active,
.fc-button:hover {
    background-color: #e9e9e9
}

.fc-header-title h2 {
    font-size: 15px;
    line-height: 1.6em;
    color: #666;
    margin-left: 10px
}

.fc-header-right {
    padding-right: 10px
}

.fc-header-left {
    padding-left: 10px
}

.fc-widget-header {
    background: #fafafa
}

.fc-grid {
    width: 100%;
    border: 0
}

.fc-widget-content:first-of-type,
.fc-widget-header:first-of-type {
    border-left: 0;
    border-right: 0
}

.fc-widget-content:last-of-type,
.fc-widget-header:last-of-type {
    border-right: 0
}

.fc-toolbar {
    padding: 10px;
    margin: 0
}

.fc-day-number {
    font-size: 20px;
    font-weight: 300;
    padding-right: 10px
}

.fc-color-picker {
    list-style: none;
    margin: 0;
    padding: 0
}

.fc-color-picker>li {
    float: left;
    font-size: 30px;
    margin-right: 5px;
    line-height: 30px
}

.fc-color-picker>li .fa {
    -webkit-transition: -webkit-transform linear .3s;
    -moz-transition: -moz-transform linear .3s;
    -o-transition: -o-transform linear .3s;
    transition: transform linear .3s
}

.fc-color-picker>li .fa:hover {
    -webkit-transform: rotate(30deg);
    -ms-transform: rotate(30deg);
    -o-transform: rotate(30deg);
    transform: rotate(30deg)
}

#add-new-event {
    -webkit-transition: all linear .3s;
    -o-transition: all linear .3s;
    transition: all linear .3s
}

.external-event {
    padding: 5px 10px;
    font-weight: 700;
    margin-bottom: 4px;
    box-shadow: 0 1px 1px rgba(0, 0, 0, .1);
    text-shadow: 0 1px 1px rgba(0, 0, 0, .1);
    border-radius: 3px;
    cursor: move
}

.external-event:hover {
    box-shadow: inset 0 0 90px rgba(0, 0, 0, .2)
}

.select2-container--default.select2-container--focus,
.select2-container--default:active,
.select2-container--default:focus,
.select2-selection.select2-container--focus,
.select2-selection:active,
.select2-selection:focus {
    outline: 0
}

.select2-container--default .select2-selection--single,
.select2-selection .select2-selection--single {
    border: 1px solid #d2d6de;
    border-radius: 0;
    padding: 6px 12px;
    height: 34px
}

.select2-container--default.select2-container--open {
    border-color: #3c8dbc
}

.select2-dropdown {
    border: 1px solid #d2d6de;
    border-radius: 0
}

.select2-container--default .select2-results__option--highlighted[aria-selected] {
    background-color: #3c8dbc;
    color: #fff
}

.select2-results__option {
    padding: 6px 12px;
    user-select: none;
    -webkit-user-select: none
}

.select2-container .select2-selection--single .select2-selection__rendered {
    padding-left: 0;
    padding-right: 0;
    height: auto;
    margin-top: -4px
}

.select2-container[dir=rtl] .select2-selection--single .select2-selection__rendered {
    padding-right: 6px;
    padding-left: 20px
}

.select2-container--default .select2-selection--single .select2-selection__arrow {
    height: 28px;
    right: 3px
}

.select2-container--default .select2-selection--single .select2-selection__arrow b {
    margin-top: 0
}

.select2-dropdown .select2-search__field,
.select2-search--inline .select2-search__field {
    border: 1px solid #d2d6de
}

.select2-dropdown .select2-search__field:focus,
.select2-search--inline .select2-search__field:focus {
    outline: 0
}

.select2-container--default .select2-search--dropdown .select2-search__field,
.select2-container--default.select2-container--focus .select2-selection--multiple {
    border-color: #3c8dbc !important
}

.select2-container--default .select2-results__option[aria-disabled=true] {
    color: #999
}

.select2-container--default .select2-results__option[aria-selected=true] {
    background-color: #ddd
}

.select2-container--default .select2-results__option[aria-selected=true],
.select2-container--default .select2-results__option[aria-selected=true]:hover {
    color: #444
}

.select2-container--default .select2-selection--multiple {
    border: 1px solid #d2d6de;
    border-radius: 0
}

.select2-container--default .select2-selection--multiple:focus {
    border-color: #3c8dbc
}

.select2-container--default.select2-container--focus .select2-selection--multiple {
    border-color: #d2d6de
}

.select2-container--default .select2-selection--multiple .select2-selection__choice {
    background-color: #3c8dbc;
    border-color: #367fa9;
    padding: 1px 10px;
    color: #fff
}

.select2-container--default .select2-selection--multiple .select2-selection__choice__remove {
    margin-right: 5px;
    color: rgba(255, 255, 255, .7)
}

.select2-container--default .select2-selection--multiple .select2-selection__choice__remove:hover {
    color: #fff
}

.select2-container .select2-selection--single .select2-selection__rendered {
    padding-right: 10px
}

.box .datepicker-inline,
.box .datepicker-inline .datepicker-days,
.box .datepicker-inline .datepicker-days>table,
.box .datepicker-inline>table {
    width: 100%
}

.box .datepicker-inline .datepicker-days td:hover,
.box .datepicker-inline .datepicker-days>table td:hover,
.box .datepicker-inline td:hover,
.box .datepicker-inline>table td:hover {
    background-color: rgba(255, 255, 255, .3)
}

.box .datepicker-inline .datepicker-days td.day.new,
.box .datepicker-inline .datepicker-days td.day.old,
.box .datepicker-inline .datepicker-days>table td.day.new,
.box .datepicker-inline .datepicker-days>table td.day.old,
.box .datepicker-inline td.day.new,
.box .datepicker-inline td.day.old,
.box .datepicker-inline>table td.day.new,
.box .datepicker-inline>table td.day.old {
    color: #777
}

.pad {
    padding: 10px
}

.margin {
    margin: 10px
}

.margin-bottom {
    margin-bottom: 20px
}

.margin-bottom-none {
    margin-bottom: 0
}

.margin-r-5 {
    margin-right: 5px
}

.inline {
    display: inline
}

.description-block {
    display: block;
    margin: 10px 0;
    text-align: center
}

.description-block.margin-bottom {
    margin-bottom: 25px
}

.description-block>.description-header {
    margin: 0;
    padding: 0;
    font-weight: 600;
    font-size: 16px
}

.description-block>.description-text {
    text-transform: uppercase
}

.alert-danger,
.alert-error,
.alert-info,
.alert-success,
.alert-warning,
.bg-aqua,
.bg-aqua-active,
.bg-black,
.bg-black-active,
.bg-blue,
.bg-blue-active,
.bg-fuchsia,
.bg-fuchsia-active,
.bg-green,
.bg-green-active,
.bg-light-blue,
.bg-light-blue-active,
.bg-lime,
.bg-lime-active,
.bg-maroon,
.bg-maroon-active,
.bg-navy,
.bg-navy-active,
.bg-olive,
.bg-olive-active,
.bg-orange,
.bg-orange-active,
.bg-purple,
.bg-purple-active,
.bg-red,
.bg-red-active,
.bg-teal,
.bg-teal-active,
.bg-yellow,
.bg-yellow-active,
.callout.callout-danger,
.callout.callout-info,
.callout.callout-success,
.callout.callout-warning,
.label-danger,
.label-info,
.label-primary,
.label-success,
.label-warning,
.modal-danger .modal-body,
.modal-danger .modal-footer,
.modal-danger .modal-header,
.modal-info .modal-body,
.modal-info .modal-footer,
.modal-info .modal-header,
.modal-primary .modal-body,
.modal-primary .modal-footer,
.modal-primary .modal-header,
.modal-success .modal-body,
.modal-success .modal-footer,
.modal-success .modal-header,
.modal-warning .modal-body,
.modal-warning .modal-footer,
.modal-warning .modal-header {
    color: #fff !important
}

.bg-gray {
    color: #000;
    background-color: #d2d6de !important
}

.bg-gray-light {
    background-color: #f7f7f7
}

.bg-black {
    background-color: #111 !important
}

.alert-danger,
.alert-error,
.bg-red,
.callout.callout-danger,
.label-danger,
.modal-danger .modal-body {
    background-color: #dd4b39 !important
}

.alert-warning,
.bg-yellow,
.callout.callout-warning,
.label-warning,
.modal-warning .modal-body {
    background-color: #f39c12 !important
}

.alert-info,
.bg-aqua,
.callout.callout-info,
.label-info,
.modal-info .modal-body {
    background-color: #00c0ef !important
}

.bg-blue {
    background-color: #0073b7 !important
}

.bg-light-blue,
.label-primary,
.modal-primary .modal-body {
    background-color: #3c8dbc !important
}

.alert-success,
.bg-green,
.callout.callout-success,
.label-success,
.modal-success .modal-body {
    background-color: #00a65a !important
}

.bg-navy {
    background-color: #001f3f !important
}

.bg-teal {
    background-color: #39cccc !important
}

.bg-olive {
    background-color: #3d9970 !important
}

.bg-lime {
    background-color: #01ff70 !important
}

.bg-orange {
    background-color: #ff851b !important
}

.bg-fuchsia {
    background-color: #f012be !important
}

.bg-purple {
    background-color: #605ca8 !important
}

.bg-maroon {
    background-color: #d81b60 !important
}

.bg-gray-active {
    color: #000;
    background-color: #b5bbc8 !important
}

.bg-black-active {
    background-color: #000 !important
}

.bg-red-active,
.modal-danger .modal-footer,
.modal-danger .modal-header {
    background-color: #d33724 !important
}

.bg-yellow-active,
.modal-warning .modal-footer,
.modal-warning .modal-header {
    background-color: #db8b0b !important
}

.bg-aqua-active,
.modal-info .modal-footer,
.modal-info .modal-header {
    background-color: #00a7d0 !important
}

.bg-blue-active {
    background-color: #005384 !important
}

.bg-light-blue-active,
.modal-primary .modal-footer,
.modal-primary .modal-header {
    background-color: #357ca5 !important
}

.bg-green-active,
.modal-success .modal-footer,
.modal-success .modal-header {
    background-color: #008d4c !important
}

.bg-navy-active {
    background-color: #001a35 !important
}

.bg-teal-active {
    background-color: #30bbbb !important
}

.bg-olive-active {
    background-color: #368763 !important
}

.bg-lime-active {
    background-color: #00e765 !important
}

.bg-orange-active {
    background-color: #ff7701 !important
}

.bg-fuchsia-active {
    background-color: #db0ead !important
}

.bg-purple-active {
    background-color: #555299 !important
}

.bg-maroon-active {
    background-color: #ca195a !important
}

[class^=bg-].disabled {
    opacity: .65
}

.text-red {
    color: #dd4b39 !important
}

.text-yellow {
    color: #f39c12 !important
}

.text-aqua {
    color: #00c0ef !important
}

.text-blue {
    color: #0073b7 !important
}

.text-black {
    color: #111 !important
}

.text-light-blue {
    color: #3c8dbc !important
}

.text-green {
    color: #00a65a !important
}

.text-gray {
    color: #d2d6de !important
}

.text-navy {
    color: #001f3f !important
}

.text-teal {
    color: #39cccc !important
}

.text-olive {
    color: #3d9970 !important
}

.text-lime {
    color: #01ff70 !important
}

.text-orange {
    color: #ff851b !important
}

.text-fuchsia {
    color: #f012be !important
}

.text-purple {
    color: #605ca8 !important
}

.text-maroon {
    color: #d81b60 !important
}

.link-muted {
    color: #7a869d
}

.link-muted:focus,
.link-muted:hover {
    color: #606c84
}

.link-black {
    color: #666
}

.link-black:focus,
.link-black:hover {
    color: #999
}

.hide {
    display: none !important
}

.no-border {
    border: 0 !important
}

.no-padding {
    padding: 0 !important
}

.no-margin {
    margin: 0 !important
}

.no-shadow {
    box-shadow: none !important
}

.chart-legend,
.contacts-list,
.list-unstyled,
.mailbox-attachments,
.users-list {
    list-style: none;
    margin: 0;
    padding: 0
}

.list-group-unbordered>.list-group-item {
    border-left: 0;
    border-right: 0;
    border-radius: 0;
    padding-left: 0;
    padding-right: 0
}

.flat {
    border-radius: 0 !important
}

.text-bold,
.text-bold.table td,
.text-bold.table th {
    font-weight: 700
}

.text-sm {
    font-size: 12px
}

.jqstooltip {
    padding: 5px !important;
    width: auto !important;
    height: auto !important
}

.bg-teal-gradient {
    background: #39cccc !important;
    background: -webkit-gradient(linear, left bottom, left top, color-stop(0, #39cccc), color-stop(1, #7adddd)) !important;
    background: -ms-linear-gradient(bottom, #39cccc, #7adddd) !important;
    background: -moz-linear-gradient(center bottom, #39cccc 0, #7adddd 100%) !important;
    background: -o-linear-gradient(#7adddd, #39cccc) !important;
    color: #fff
}

.bg-light-blue-gradient {
    background: #3c8dbc !important;
    background: -webkit-gradient(linear, left bottom, left top, color-stop(0, #3c8dbc), color-stop(1, #67a8ce)) !important;
    background: -ms-linear-gradient(bottom, #3c8dbc, #67a8ce) !important;
    background: -moz-linear-gradient(center bottom, #3c8dbc 0, #67a8ce 100%) !important;
    background: -o-linear-gradient(#67a8ce, #3c8dbc) !important;
    color: #fff
}

.bg-blue-gradient {
    background: #0073b7 !important;
    background: -webkit-gradient(linear, left bottom, left top, color-stop(0, #0073b7), color-stop(1, #0089db)) !important;
    background: -ms-linear-gradient(bottom, #0073b7, #0089db) !important;
    background: -moz-linear-gradient(center bottom, #0073b7 0, #0089db 100%) !important;
    background: -o-linear-gradient(#0089db, #0073b7) !important;
    color: #fff
}

.bg-aqua-gradient {
    background: #00c0ef !important;
    background: -webkit-gradient(linear, left bottom, left top, color-stop(0, #00c0ef), color-stop(1, #14d1ff)) !important;
    background: -ms-linear-gradient(bottom, #00c0ef, #14d1ff) !important;
    background: -moz-linear-gradient(center bottom, #00c0ef 0, #14d1ff 100%) !important;
    background: -o-linear-gradient(#14d1ff, #00c0ef) !important;
    color: #fff
}

.bg-yellow-gradient {
    background: #f39c12 !important;
    background: -webkit-gradient(linear, left bottom, left top, color-stop(0, #f39c12), color-stop(1, #f7bc60)) !important;
    background: -ms-linear-gradient(bottom, #f39c12, #f7bc60) !important;
    background: -moz-linear-gradient(center bottom, #f39c12 0, #f7bc60 100%) !important;
    background: -o-linear-gradient(#f7bc60, #f39c12) !important;
    color: #fff
}

.bg-purple-gradient {
    background: #605ca8 !important;
    background: -webkit-gradient(linear, left bottom, left top, color-stop(0, #605ca8), color-stop(1, #9491c4)) !important;
    background: -ms-linear-gradient(bottom, #605ca8, #9491c4) !important;
    background: -moz-linear-gradient(center bottom, #605ca8 0, #9491c4 100%) !important;
    background: -o-linear-gradient(#9491c4, #605ca8) !important;
    color: #fff
}

.bg-green-gradient {
    background: #00a65a !important;
    background: -webkit-gradient(linear, left bottom, left top, color-stop(0, #00a65a), color-stop(1, #00ca6d)) !important;
    background: -ms-linear-gradient(bottom, #00a65a, #00ca6d) !important;
    background: -moz-linear-gradient(center bottom, #00a65a 0, #00ca6d 100%) !important;
    background: -o-linear-gradient(#00ca6d, #00a65a) !important;
    color: #fff
}

.bg-red-gradient {
    background: #dd4b39 !important;
    background: -webkit-gradient(linear, left bottom, left top, color-stop(0, #dd4b39), color-stop(1, #e47365)) !important;
    background: -ms-linear-gradient(bottom, #dd4b39, #e47365) !important;
    background: -moz-linear-gradient(center bottom, #dd4b39 0, #e47365 100%) !important;
    background: -o-linear-gradient(#e47365, #dd4b39) !important;
    color: #fff
}

.bg-black-gradient {
    background: #111 !important;
    background: -webkit-gradient(linear, left bottom, left top, color-stop(0, #111), color-stop(1, #2b2b2b)) !important;
    background: -ms-linear-gradient(bottom, #111, #2b2b2b) !important;
    background: -moz-linear-gradient(center bottom, #111 0, #2b2b2b 100%) !important;
    background: -o-linear-gradient(#2b2b2b, #111) !important;
    color: #fff
}

.bg-maroon-gradient {
    background: #d81b60 !important;
    background: -webkit-gradient(linear, left bottom, left top, color-stop(0, #d81b60), color-stop(1, #e73f7c)) !important;
    background: -ms-linear-gradient(bottom, #d81b60, #e73f7c) !important;
    background: -moz-linear-gradient(center bottom, #d81b60 0, #e73f7c 100%) !important;
    background: -o-linear-gradient(#e73f7c, #d81b60) !important;
    color: #fff
}

.description-block .description-icon {
    font-size: 16px
}

.no-pad-top {
    padding-top: 0
}

.position-static {
    position: static !important
}

.list-header {
    font-size: 15px;
    padding: 10px 4px;
    font-weight: 700;
    color: #666
}

.list-seperator {
    height: 1px;
    background: #f4f4f4;
    margin: 15px 0 9px 0
}

.list-link>a {
    padding: 4px;
    color: #777
}

.list-link>a:hover {
    color: #222
}

.font-light {
    font-weight: 300
}

.user-block:after,
.user-block:before {
    content: " ";
    display: table
}

.user-block:after {
    clear: both
}

.user-block img {
    width: 40px;
    height: 40px;
    float: left
}

.user-block .comment,
.user-block .description,
.user-block .username {
    display: block;
    margin-left: 50px
}

.user-block .username {
    font-size: 16px;
    font-weight: 600
}

.user-block .description {
    color: #999;
    font-size: 13px
}

.user-block.user-block-sm .comment,
.user-block.user-block-sm .description,
.user-block.user-block-sm .username {
    margin-left: 40px
}

.user-block.user-block-sm .username {
    font-size: 14px
}

.box-comments .box-comment img,
.img-lg,
.img-md,
.img-sm,
.user-block.user-block-sm img {
    float: left
}

.box-comments .box-comment img,
.img-sm,
.user-block.user-block-sm img {
    width: 30px !important;
    height: 30px !important
}

.img-sm+.img-push {
    margin-left: 40px
}

.img-md {
    width: 60px;
    height: 60px
}

.img-md+.img-push {
    margin-left: 70px
}

.img-lg {
    width: 100px;
    height: 100px
}

.img-lg+.img-push {
    margin-left: 110px
}

.img-bordered {
    border: 3px solid #d2d6de;
    padding: 3px
}

.img-bordered-sm {
    border: 2px solid #d2d6de;
    padding: 2px
}

.attachment-block {
    border: 1px solid #f4f4f4;
    padding: 5px;
    margin-bottom: 10px;
    background: #f7f7f7
}

.attachment-block .attachment-img {
    max-width: 100px;
    max-height: 100px;
    height: auto;
    float: left
}

.attachment-block .attachment-pushed {
    margin-left: 110px
}

.attachment-block .attachment-heading {
    margin: 0
}

.attachment-block .attachment-text {
    color: #555
}

.connectedSortable {
    min-height: 100px
}

.ui-helper-hidden-accessible {
    border: 0;
    clip: rect(0 0 0 0);
    height: 1px;
    margin: -1px;
    overflow: hidden;
    padding: 0;
    position: absolute;
    width: 1px
}

.sort-highlight {
    background: #f4f4f4;
    border: 1px dashed #ddd;
    margin-bottom: 10px
}

.full-opacity-hover {
    opacity: .65
}

.full-opacity-hover:hover {
    opacity: 1
}

.chart {
    position: relative;
    overflow: hidden;
    width: 100%
}

.chart canvas,
.chart svg {
    width: 100% !important
}

hr {
    border-top: 1px solid #555
}

#red .slider-selection {
    background: #f56954
}

#blue .slider-selection {
    background: #3c8dbc
}

#green .slider-selection {
    background: #00a65a
}

#yellow .slider-selection {
    background: #f39c12
}

#aqua .slider-selection {
    background: #00c0ef
}

#purple .slider-selection {
    background: #932ab6
}

@media print {
    .content-header,
    .left-side,
    .main-header,
    .main-sidebar,
    .no-print {
        display: none !important
    }
    .content-wrapper,
    .main-footer,
    .right-side {
        margin-left: 0 !important;
        min-height: 0 !important;
        -webkit-transform: translate(0, 0) !important;
        -ms-transform: translate(0, 0) !important;
        -o-transform: translate(0, 0) !important;
        transform: translate(0, 0) !important
    }
    .fixed .content-wrapper,
    .fixed .right-side {
        padding-top: 0 !important
    }
    .invoice {
        width: 100%;
        border: 0;
        margin: 0;
        padding: 0
    }
    .invoice-col {
        float: left;
        width: 33.3333333%
    }
    .table-responsive {
        overflow: auto
    }
    .table-responsive>.table tr td,
    .table-responsive>.table tr th {
        white-space: normal !important
    }
}

/*!
 * Datepicker for Bootstrap v1.9.0 (https://github.com/uxsolutions/bootstrap-datepicker)
 *
 * Licensed under the Apache License v2.0 (http://www.apache.org/licenses/LICENSE-2.0)
 */

.datepicker {
    padding: 4px;
    -webkit-border-radius: 4px;
    -moz-border-radius: 4px;
    border-radius: 4px;
    direction: ltr
}

.datepicker-inline {
    width: 220px
}

.datepicker-rtl {
    direction: rtl
}

.datepicker-rtl.dropdown-menu {
    left: auto
}

.datepicker-rtl table tr td span {
    float: right
}

.datepicker-dropdown {
    top: 0;
    left: 0
}

.datepicker-dropdown:before {
    content: '';
    display: inline-block;
    border-left: 7px solid transparent;
    border-right: 7px solid transparent;
    border-bottom: 7px solid #999;
    border-top: 0;
    border-bottom-color: rgba(0, 0, 0, .2);
    position: absolute
}

.datepicker-dropdown:after {
    content: '';
    display: inline-block;
    border-left: 6px solid transparent;
    border-right: 6px solid transparent;
    border-bottom: 6px solid #fff;
    border-top: 0;
    position: absolute
}

.datepicker-dropdown.datepicker-orient-left:before {
    left: 6px
}

.datepicker-dropdown.datepicker-orient-left:after {
    left: 7px
}

.datepicker-dropdown.datepicker-orient-right:before {
    right: 6px
}

.datepicker-dropdown.datepicker-orient-right:after {
    right: 7px
}

.datepicker-dropdown.datepicker-orient-bottom:before {
    top: -7px
}

.datepicker-dropdown.datepicker-orient-bottom:after {
    top: -6px
}

.datepicker-dropdown.datepicker-orient-top:before {
    bottom: -7px;
    border-bottom: 0;
    border-top: 7px solid #999
}

.datepicker-dropdown.datepicker-orient-top:after {
    bottom: -6px;
    border-bottom: 0;
    border-top: 6px solid #fff
}

.datepicker table {
    margin: 0;
    -webkit-touch-callout: none;
    -webkit-user-select: none;
    -khtml-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none
}

.datepicker td,
.datepicker th {
    text-align: center;
    width: 20px;
    height: 20px;
    -webkit-border-radius: 4px;
    -moz-border-radius: 4px;
    border-radius: 4px;
    border: none
}

.table-striped .datepicker table tr td,
.table-striped .datepicker table tr th {
    background-color: transparent
}

.datepicker table tr td.day.focused,
.datepicker table tr td.day:hover {
    background: #eee;
    cursor: pointer
}

.datepicker table tr td.new,
.datepicker table tr td.old {
    color: #999
}

.datepicker table tr td.disabled,
.datepicker table tr td.disabled:hover {
    background: 0 0;
    color: #999;
    cursor: default
}

.datepicker table tr td.highlighted {
    background: #d9edf7;
    border-radius: 0
}

.datepicker table tr td.today,
.datepicker table tr td.today.disabled,
.datepicker table tr td.today.disabled:hover,
.datepicker table tr td.today:hover {
    background-color: #fde19a;
    background-image: -moz-linear-gradient(to bottom, #fdd49a, #fdf59a);
    background-image: -ms-linear-gradient(to bottom, #fdd49a, #fdf59a);
    background-image: -webkit-gradient(linear, 0 0, 0 100%, from(#fdd49a), to(#fdf59a));
    background-image: -webkit-linear-gradient(to bottom, #fdd49a, #fdf59a);
    background-image: -o-linear-gradient(to bottom, #fdd49a, #fdf59a);
    background-image: linear-gradient(to bottom, #fdd49a, #fdf59a);
    background-repeat: repeat-x;
    border-color: #fdf59a #fdf59a #fbed50;
    border-color: rgba(0, 0, 0, .1) rgba(0, 0, 0, .1) rgba(0, 0, 0, .25);
    color: #000
}

.datepicker table tr td.today.active,
.datepicker table tr td.today.disabled,
.datepicker table tr td.today.disabled.active,
.datepicker table tr td.today.disabled.disabled,
.datepicker table tr td.today.disabled:active,
.datepicker table tr td.today.disabled:hover,
.datepicker table tr td.today.disabled:hover.active,
.datepicker table tr td.today.disabled:hover.disabled,
.datepicker table tr td.today.disabled:hover:active,
.datepicker table tr td.today.disabled:hover:hover,
.datepicker table tr td.today.disabled:hover[disabled],
.datepicker table tr td.today.disabled[disabled],
.datepicker table tr td.today:active,
.datepicker table tr td.today:hover,
.datepicker table tr td.today:hover.active,
.datepicker table tr td.today:hover.disabled,
.datepicker table tr td.today:hover:active,
.datepicker table tr td.today:hover:hover,
.datepicker table tr td.today:hover[disabled],
.datepicker table tr td.today[disabled] {
    background-color: #fdf59a
}

.datepicker table tr td.today:hover:hover {
    color: #000
}

.datepicker table tr td.today.active:hover {
    color: #fff
}

.datepicker table tr td.range,
.datepicker table tr td.range.disabled,
.datepicker table tr td.range.disabled:hover,
.datepicker table tr td.range:hover {
    background: #eee;
    -webkit-border-radius: 0;
    -moz-border-radius: 0;
    border-radius: 0
}

.datepicker table tr td.range.today,
.datepicker table tr td.range.today.disabled,
.datepicker table tr td.range.today.disabled:hover,
.datepicker table tr td.range.today:hover {
    background-color: #f3d17a;
    background-image: -moz-linear-gradient(to bottom, #f3c17a, #f3e97a);
    background-image: -ms-linear-gradient(to bottom, #f3c17a, #f3e97a);
    background-image: -webkit-gradient(linear, 0 0, 0 100%, from(#f3c17a), to(#f3e97a));
    background-image: -webkit-linear-gradient(to bottom, #f3c17a, #f3e97a);
    background-image: -o-linear-gradient(to bottom, #f3c17a, #f3e97a);
    background-image: linear-gradient(to bottom, #f3c17a, #f3e97a);
    background-repeat: repeat-x;
    border-color: #f3e97a #f3e97a #edde34;
    border-color: rgba(0, 0, 0, .1) rgba(0, 0, 0, .1) rgba(0, 0, 0, .25);
    -webkit-border-radius: 0;
    -moz-border-radius: 0;
    border-radius: 0
}

.datepicker table tr td.range.today.active,
.datepicker table tr td.range.today.disabled,
.datepicker table tr td.range.today.disabled.active,
.datepicker table tr td.range.today.disabled.disabled,
.datepicker table tr td.range.today.disabled:active,
.datepicker table tr td.range.today.disabled:hover,
.datepicker table tr td.range.today.disabled:hover.active,
.datepicker table tr td.range.today.disabled:hover.disabled,
.datepicker table tr td.range.today.disabled:hover:active,
.datepicker table tr td.range.today.disabled:hover:hover,
.datepicker table tr td.range.today.disabled:hover[disabled],
.datepicker table tr td.range.today.disabled[disabled],
.datepicker table tr td.range.today:active,
.datepicker table tr td.range.today:hover,
.datepicker table tr td.range.today:hover.active,
.datepicker table tr td.range.today:hover.disabled,
.datepicker table tr td.range.today:hover:active,
.datepicker table tr td.range.today:hover:hover,
.datepicker table tr td.range.today:hover[disabled],
.datepicker table tr td.range.today[disabled] {
    background-color: #f3e97a
}

.datepicker table tr td.selected,
.datepicker table tr td.selected.disabled,
.datepicker table tr td.selected.disabled:hover,
.datepicker table tr td.selected:hover {
    background-color: #9e9e9e;
    background-image: -moz-linear-gradient(to bottom, #b3b3b3, grey);
    background-image: -ms-linear-gradient(to bottom, #b3b3b3, grey);
    background-image: -webkit-gradient(linear, 0 0, 0 100%, from(#b3b3b3), to(grey));
    background-image: -webkit-linear-gradient(to bottom, #b3b3b3, grey);
    background-image: -o-linear-gradient(to bottom, #b3b3b3, grey);
    background-image: linear-gradient(to bottom, #b3b3b3, grey);
    background-repeat: repeat-x;
    border-color: grey grey #595959;
    border-color: rgba(0, 0, 0, .1) rgba(0, 0, 0, .1) rgba(0, 0, 0, .25);
    color: #fff;
    text-shadow: 0 -1px 0 rgba(0, 0, 0, .25)
}

.datepicker table tr td.selected.active,
.datepicker table tr td.selected.disabled,
.datepicker table tr td.selected.disabled.active,
.datepicker table tr td.selected.disabled.disabled,
.datepicker table tr td.selected.disabled:active,
.datepicker table tr td.selected.disabled:hover,
.datepicker table tr td.selected.disabled:hover.active,
.datepicker table tr td.selected.disabled:hover.disabled,
.datepicker table tr td.selected.disabled:hover:active,
.datepicker table tr td.selected.disabled:hover:hover,
.datepicker table tr td.selected.disabled:hover[disabled],
.datepicker table tr td.selected.disabled[disabled],
.datepicker table tr td.selected:active,
.datepicker table tr td.selected:hover,
.datepicker table tr td.selected:hover.active,
.datepicker table tr td.selected:hover.disabled,
.datepicker table tr td.selected:hover:active,
.datepicker table tr td.selected:hover:hover,
.datepicker table tr td.selected:hover[disabled],
.datepicker table tr td.selected[disabled] {
    background-color: grey
}

.datepicker table tr td.active,
.datepicker table tr td.active.disabled,
.datepicker table tr td.active.disabled:hover,
.datepicker table tr td.active:hover {
    background-color: #006dcc;
    background-image: -moz-linear-gradient(to bottom, #08c, #04c);
    background-image: -ms-linear-gradient(to bottom, #08c, #04c);
    background-image: -webkit-gradient(linear, 0 0, 0 100%, from(#08c), to(#04c));
    background-image: -webkit-linear-gradient(to bottom, #08c, #04c);
    background-image: -o-linear-gradient(to bottom, #08c, #04c);
    background-image: linear-gradient(to bottom, #08c, #04c);
    background-repeat: repeat-x;
    border-color: #04c #04c #002a80;
    border-color: rgba(0, 0, 0, .1) rgba(0, 0, 0, .1) rgba(0, 0, 0, .25);
    color: #fff;
    text-shadow: 0 -1px 0 rgba(0, 0, 0, .25)
}

.datepicker table tr td.active.active,
.datepicker table tr td.active.disabled,
.datepicker table tr td.active.disabled.active,
.datepicker table tr td.active.disabled.disabled,
.datepicker table tr td.active.disabled:active,
.datepicker table tr td.active.disabled:hover,
.datepicker table tr td.active.disabled:hover.active,
.datepicker table tr td.active.disabled:hover.disabled,
.datepicker table tr td.active.disabled:hover:active,
.datepicker table tr td.active.disabled:hover:hover,
.datepicker table tr td.active.disabled:hover[disabled],
.datepicker table tr td.active.disabled[disabled],
.datepicker table tr td.active:active,
.datepicker table tr td.active:hover,
.datepicker table tr td.active:hover.active,
.datepicker table tr td.active:hover.disabled,
.datepicker table tr td.active:hover:active,
.datepicker table tr td.active:hover:hover,
.datepicker table tr td.active:hover[disabled],
.datepicker table tr td.active[disabled] {
    background-color: #04c
}

.datepicker table tr td span {
    display: block;
    width: 23%;
    height: 54px;
    line-height: 54px;
    float: left;
    margin: 1%;
    cursor: pointer;
    -webkit-border-radius: 4px;
    -moz-border-radius: 4px;
    border-radius: 4px
}

.datepicker table tr td span.focused,
.datepicker table tr td span:hover {
    background: #eee
}

.datepicker table tr td span.disabled,
.datepicker table tr td span.disabled:hover {
    background: 0 0;
    color: #999;
    cursor: default
}

.datepicker table tr td span.active,
.datepicker table tr td span.active.disabled,
.datepicker table tr td span.active.disabled:hover,
.datepicker table tr td span.active:hover {
    background-color: #006dcc;
    background-image: -moz-linear-gradient(to bottom, #08c, #04c);
    background-image: -ms-linear-gradient(to bottom, #08c, #04c);
    background-image: -webkit-gradient(linear, 0 0, 0 100%, from(#08c), to(#04c));
    background-image: -webkit-linear-gradient(to bottom, #08c, #04c);
    background-image: -o-linear-gradient(to bottom, #08c, #04c);
    background-image: linear-gradient(to bottom, #08c, #04c);
    background-repeat: repeat-x;
    border-color: #04c #04c #002a80;
    border-color: rgba(0, 0, 0, .1) rgba(0, 0, 0, .1) rgba(0, 0, 0, .25);
    color: #fff;
    text-shadow: 0 -1px 0 rgba(0, 0, 0, .25)
}

.datepicker table tr td span.active.active,
.datepicker table tr td span.active.disabled,
.datepicker table tr td span.active.disabled.active,
.datepicker table tr td span.active.disabled.disabled,
.datepicker table tr td span.active.disabled:active,
.datepicker table tr td span.active.disabled:hover,
.datepicker table tr td span.active.disabled:hover.active,
.datepicker table tr td span.active.disabled:hover.disabled,
.datepicker table tr td span.active.disabled:hover:active,
.datepicker table tr td span.active.disabled:hover:hover,
.datepicker table tr td span.active.disabled:hover[disabled],
.datepicker table tr td span.active.disabled[disabled],
.datepicker table tr td span.active:active,
.datepicker table tr td span.active:hover,
.datepicker table tr td span.active:hover.active,
.datepicker table tr td span.active:hover.disabled,
.datepicker table tr td span.active:hover:active,
.datepicker table tr td span.active:hover:hover,
.datepicker table tr td span.active:hover[disabled],
.datepicker table tr td span.active[disabled] {
    background-color: #04c
}

.datepicker table tr td span.new,
.datepicker table tr td span.old {
    color: #999
}

.datepicker .datepicker-switch {
    width: 145px
}

.datepicker .datepicker-switch,
.datepicker .next,
.datepicker .prev,
.datepicker tfoot tr th {
    cursor: pointer
}

.datepicker .datepicker-switch:hover,
.datepicker .next:hover,
.datepicker .prev:hover,
.datepicker tfoot tr th:hover {
    background: #eee
}

.datepicker .next.disabled,
.datepicker .prev.disabled {
    visibility: hidden
}

.datepicker .cw {
    font-size: 10px;
    width: 12px;
    padding: 0 2px 0 5px;
    vertical-align: middle
}

.input-append.date .add-on,
.input-prepend.date .add-on {
    cursor: pointer
}

.input-append.date .add-on i,
.input-prepend.date .add-on i {
    margin-top: 3px
}

.input-daterange input {
    text-align: center
}

.input-daterange input:first-child {
    -webkit-border-radius: 3px 0 0 3px;
    -moz-border-radius: 3px 0 0 3px;
    border-radius: 3px 0 0 3px
}

.input-daterange input:last-child {
    -webkit-border-radius: 0 3px 3px 0;
    -moz-border-radius: 0 3px 3px 0;
    border-radius: 0 3px 3px 0
}

.input-daterange .add-on {
    display: inline-block;
    width: auto;
    min-width: 16px;
    height: 18px;
    padding: 4px 5px;
    font-weight: 400;
    line-height: 18px;
    text-align: center;
    text-shadow: 0 1px 0 #fff;
    vertical-align: middle;
    background-color: #eee;
    border: 1px solid #ccc;
    margin-left: -5px;
    margin-right: -5px
}

table.dataTable {
    clear: both;
    margin-top: 6px !important;
    margin-bottom: 6px !important;
    max-width: none !important;
    border-collapse: separate !important
}

table.dataTable td,
table.dataTable th {
    -webkit-box-sizing: content-box;
    box-sizing: content-box
}

table.dataTable td.dataTables_empty,
table.dataTable th.dataTables_empty {
    text-align: center
}

table.dataTable.nowrap td,
table.dataTable.nowrap th {
    white-space: nowrap
}

div.dataTables_wrapper div.dataTables_length label {
    font-weight: 400;
    text-align: left;
    white-space: nowrap
}

div.dataTables_wrapper div.dataTables_length select {
    width: 75px;
    display: inline-block
}

div.dataTables_wrapper div.dataTables_filter {
    text-align: right
}

div.dataTables_wrapper div.dataTables_filter label {
    font-weight: 400;
    white-space: nowrap;
    text-align: left
}

div.dataTables_wrapper div.dataTables_filter input {
    margin-left: .5em;
    display: inline-block;
    width: auto
}

div.dataTables_wrapper div.dataTables_info {
    padding-top: 8px;
    white-space: nowrap
}

div.dataTables_wrapper div.dataTables_paginate {
    margin: 0;
    white-space: nowrap;
    text-align: right
}

div.dataTables_wrapper div.dataTables_paginate ul.pagination {
    margin: 2px 0;
    white-space: nowrap
}

div.dataTables_wrapper div.dataTables_processing {
    position: absolute;
    top: 50%;
    left: 50%;
    width: 200px;
    margin-left: -100px;
    margin-top: -26px;
    text-align: center;
    padding: 1em 0
}

table.dataTable thead>tr>td.sorting,
table.dataTable thead>tr>td.sorting_asc,
table.dataTable thead>tr>td.sorting_desc,
table.dataTable thead>tr>th.sorting,
table.dataTable thead>tr>th.sorting_asc,
table.dataTable thead>tr>th.sorting_desc {
    padding-right: 30px
}

table.dataTable thead>tr>td:active,
table.dataTable thead>tr>th:active {
    outline: 0
}

table.dataTable thead .sorting,
table.dataTable thead .sorting_asc,
table.dataTable thead .sorting_asc_disabled,
table.dataTable thead .sorting_desc,
table.dataTable thead .sorting_desc_disabled {
    cursor: pointer;
    position: relative
}

table.dataTable thead .sorting:after,
table.dataTable thead .sorting_asc:after,
table.dataTable thead .sorting_asc_disabled:after,
table.dataTable thead .sorting_desc:after,
table.dataTable thead .sorting_desc_disabled:after {
    position: absolute;
    bottom: 8px;
    right: 8px;
    display: block;
    font-family: 'Glyphicons Halflings';
    opacity: .5
}

table.dataTable thead .sorting:after {
    opacity: .2;
    content: "\e150"
}

table.dataTable thead .sorting_asc:after {
    content: "\e155"
}

table.dataTable thead .sorting_desc:after {
    content: "\e156"
}

table.dataTable thead .sorting_asc_disabled:after,
table.dataTable thead .sorting_desc_disabled:after {
    color: #eee
}

div.dataTables_scrollHead table.dataTable {
    margin-bottom: 0 !important
}

div.dataTables_scrollBody>table {
    border-top: none;
    margin-top: 0 !important;
    margin-bottom: 0 !important
}

div.dataTables_scrollBody>table>thead .sorting:after,
div.dataTables_scrollBody>table>thead .sorting_asc:after,
div.dataTables_scrollBody>table>thead .sorting_desc:after {
    display: none
}

div.dataTables_scrollBody>table>tbody>tr:first-child>td,
div.dataTables_scrollBody>table>tbody>tr:first-child>th {
    border-top: none
}

div.dataTables_scrollFoot>.dataTables_scrollFootInner {
    box-sizing: content-box
}

div.dataTables_scrollFoot>.dataTables_scrollFootInner>table {
    margin-top: 0 !important;
    border-top: none
}

@media screen and (max-width:767px) {
    div.dataTables_wrapper div.dataTables_filter,
    div.dataTables_wrapper div.dataTables_info,
    div.dataTables_wrapper div.dataTables_length,
    div.dataTables_wrapper div.dataTables_paginate {
        text-align: center
    }
}

table.dataTable.table-condensed>thead>tr>th {
    padding-right: 20px
}

table.dataTable.table-condensed .sorting:after,
table.dataTable.table-condensed .sorting_asc:after,
table.dataTable.table-condensed .sorting_desc:after {
    top: 6px;
    right: 6px
}

table.table-bordered.dataTable td,
table.table-bordered.dataTable th {
    border-left-width: 0
}

table.table-bordered.dataTable td:last-child,
table.table-bordered.dataTable th:last-child {
    border-right-width: 0
}

table.table-bordered.dataTable tbody td,
table.table-bordered.dataTable tbody th {
    border-bottom-width: 0
}

div.dataTables_scrollHead table.table-bordered {
    border-bottom-width: 0
}

div.table-responsive>div.dataTables_wrapper>div.row {
    margin: 0
}

div.table-responsive>div.dataTables_wrapper>div.row>div[class^=col-]:first-child {
    padding-left: 0
}

div.table-responsive>div.dataTables_wrapper>div.row>div[class^=col-]:last-child {
    padding-right: 0
}

div.dt-autofill-handle {
    position: absolute;
    height: 8px;
    width: 8px;
    z-index: 102;
    box-sizing: border-box;
    border: 1px solid #337ab7;
    background: #337ab7
}

div.dt-autofill-select {
    position: absolute;
    z-index: 1001;
    background-color: #337ab7;
    background-image: repeating-linear-gradient(45deg, transparent, transparent 5px, rgba(255, 255, 255, .5) 5px, rgba(255, 255, 255, .5) 10px)
}

div.dt-autofill-select.bottom,
div.dt-autofill-select.top {
    height: 3px;
    margin-top: -1px
}

div.dt-autofill-select.left,
div.dt-autofill-select.right {
    width: 3px;
    margin-left: -1px
}

div.dt-autofill-list {
    position: fixed;
    top: 50%;
    left: 50%;
    width: 500px;
    margin-left: -250px;
    background-color: #fff;
    border-radius: 6px;
    box-shadow: 0 0 5px #555;
    border: 2px solid #444;
    z-index: 11;
    box-sizing: border-box;
    padding: 1.5em 2em
}

div.dt-autofill-list ul {
    display: table;
    margin: 0;
    padding: 0;
    list-style: none;
    width: 100%
}

div.dt-autofill-list ul li {
    display: table-row
}

div.dt-autofill-list ul li:last-child div.dt-autofill-button,
div.dt-autofill-list ul li:last-child div.dt-autofill-question {
    border-bottom: none
}

div.dt-autofill-list ul li:hover {
    background-color: #f6f6f6
}

div.dt-autofill-list div.dt-autofill-question {
    display: table-cell;
    padding: .5em 0;
    border-bottom: 1px solid #ccc
}

div.dt-autofill-list div.dt-autofill-question input[type=number] {
    padding: 6px;
    width: 30px;
    margin: -2px 0
}

div.dt-autofill-list div.dt-autofill-button {
    display: table-cell;
    padding: .5em 0;
    border-bottom: 1px solid #ccc
}

div.dt-autofill-background {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, .7);
    background: radial-gradient(ellipse farthest-corner at center, rgba(0, 0, 0, .3) 0, rgba(0, 0, 0, .7) 100%);
    z-index: 10
}

@keyframes dtb-spinner {
    100% {
        transform: rotate(360deg)
    }
}

@-o-keyframes dtb-spinner {
    100% {
        -o-transform: rotate(360deg);
        transform: rotate(360deg)
    }
}

@-ms-keyframes dtb-spinner {
    100% {
        -ms-transform: rotate(360deg);
        transform: rotate(360deg)
    }
}

@-webkit-keyframes dtb-spinner {
    100% {
        -webkit-transform: rotate(360deg);
        transform: rotate(360deg)
    }
}

@-moz-keyframes dtb-spinner {
    100% {
        -moz-transform: rotate(360deg);
        transform: rotate(360deg)
    }
}

div.dt-button-info {
    position: fixed;
    top: 50%;
    left: 50%;
    width: 400px;
    margin-top: -100px;
    margin-left: -200px;
    background-color: #fff;
    border: 2px solid #111;
    box-shadow: 3px 3px 8px rgba(0, 0, 0, .3);
    border-radius: 3px;
    text-align: center;
    z-index: 21
}

div.dt-button-info h2 {
    padding: .5em;
    margin: 0;
    font-weight: 400;
    border-bottom: 1px solid #ddd;
    background-color: #f3f3f3
}

div.dt-button-info>div {
    padding: 1em
}

ul.dt-button-collection.dropdown-menu {
    display: block;
    z-index: 2002;
    -webkit-column-gap: 8px;
    -moz-column-gap: 8px;
    -ms-column-gap: 8px;
    -o-column-gap: 8px;
    column-gap: 8px
}

ul.dt-button-collection.dropdown-menu.fixed {
    position: fixed;
    top: 50%;
    left: 50%;
    margin-left: -75px;
    border-radius: 0
}

ul.dt-button-collection.dropdown-menu.fixed.two-column {
    margin-left: -150px
}

ul.dt-button-collection.dropdown-menu.fixed.three-column {
    margin-left: -225px
}

ul.dt-button-collection.dropdown-menu.fixed.four-column {
    margin-left: -300px
}

ul.dt-button-collection.dropdown-menu>* {
    -webkit-column-break-inside: avoid;
    break-inside: avoid
}

ul.dt-button-collection.dropdown-menu.two-column {
    width: 300px;
    padding-bottom: 1px;
    -webkit-column-count: 2;
    -moz-column-count: 2;
    -ms-column-count: 2;
    -o-column-count: 2;
    column-count: 2
}

ul.dt-button-collection.dropdown-menu.three-column {
    width: 450px;
    padding-bottom: 1px;
    -webkit-column-count: 3;
    -moz-column-count: 3;
    -ms-column-count: 3;
    -o-column-count: 3;
    column-count: 3
}

ul.dt-button-collection.dropdown-menu.four-column {
    width: 600px;
    padding-bottom: 1px;
    -webkit-column-count: 4;
    -moz-column-count: 4;
    -ms-column-count: 4;
    -o-column-count: 4;
    column-count: 4
}

div.dt-button-background {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    z-index: 2001
}

@media screen and (max-width:767px) {
    div.dt-buttons {
        float: none;
        width: 100%;
        text-align: center;
        margin-bottom: .5em
    }
    div.dt-buttons a.btn {
        float: none
    }
}

div.dt-buttons a.btn.processing,
div.dt-buttons button.btn.processing,
div.dt-buttons div.btn.processing {
    color: rgba(0, 0, 0, .2)
}

div.dt-buttons a.btn.processing:after,
div.dt-buttons button.btn.processing:after,
div.dt-buttons div.btn.processing:after {
    position: absolute;
    top: 50%;
    left: 50%;
    width: 16px;
    height: 16px;
    margin: -8px 0 0 -8px;
    box-sizing: border-box;
    display: block;
    content: ' ';
    border: 2px solid #282828;
    border-radius: 50%;
    border-left-color: transparent;
    border-right-color: transparent;
    animation: dtb-spinner 1.5s infinite linear;
    -o-animation: dtb-spinner 1.5s infinite linear;
    -ms-animation: dtb-spinner 1500ms infinite linear;
    -webkit-animation: dtb-spinner 1.5s infinite linear;
    -moz-animation: dtb-spinner 1.5s infinite linear
}

table.DTFC_Cloned tr {
    background-color: #fff;
    margin-bottom: 0
}

div.DTFC_LeftHeadWrapper table,
div.DTFC_RightHeadWrapper table {
    border-bottom: none !important;
    margin-bottom: 0 !important;
    background-color: #fff
}

div.DTFC_LeftBodyWrapper table,
div.DTFC_RightBodyWrapper table {
    border-top: none;
    margin: 0 !important
}

div.DTFC_LeftBodyWrapper table thead .sorting:after,
div.DTFC_LeftBodyWrapper table thead .sorting_asc:after,
div.DTFC_LeftBodyWrapper table thead .sorting_desc:after,
div.DTFC_RightBodyWrapper table thead .sorting:after,
div.DTFC_RightBodyWrapper table thead .sorting_asc:after,
div.DTFC_RightBodyWrapper table thead .sorting_desc:after {
    display: none
}

div.DTFC_LeftBodyWrapper table tbody tr:first-child td,
div.DTFC_LeftBodyWrapper table tbody tr:first-child th,
div.DTFC_RightBodyWrapper table tbody tr:first-child td,
div.DTFC_RightBodyWrapper table tbody tr:first-child th {
    border-top: none
}

div.DTFC_LeftFootWrapper table,
div.DTFC_RightFootWrapper table {
    border-top: none;
    margin-top: 0 !important;
    background-color: #fff
}

div.DTFC_Blocker {
    background-color: #fff
}

table.dataTable.fixedHeader-floating,
table.dataTable.fixedHeader-locked {
    background-color: #fff;
    margin-top: 0 !important;
    margin-bottom: 0 !important
}

table.dataTable.fixedHeader-floating {
    position: fixed !important
}

table.dataTable.fixedHeader-locked {
    position: absolute !important
}

@media print {
    table.fixedHeader-floating {
        display: none
    }
}

table.dataTable td.focus,
table.dataTable th.focus {
    outline: 3px solid #337ab7;
    outline-offset: -1px
}

table.dataTable.dtr-inline.collapsed>tbody>tr>td.child,
table.dataTable.dtr-inline.collapsed>tbody>tr>td.dataTables_empty,
table.dataTable.dtr-inline.collapsed>tbody>tr>th.child {
    cursor: default !important
}

table.dataTable.dtr-inline.collapsed>tbody>tr>td.child:before,
table.dataTable.dtr-inline.collapsed>tbody>tr>td.dataTables_empty:before,
table.dataTable.dtr-inline.collapsed>tbody>tr>th.child:before {
    display: none !important
}

table.dataTable.dtr-inline.collapsed>tbody>tr[role=row]>td:first-child,
table.dataTable.dtr-inline.collapsed>tbody>tr[role=row]>th:first-child {
    position: relative;
    padding-left: 30px;
    cursor: pointer
}

table.dataTable.dtr-inline.collapsed>tbody>tr[role=row]>td:first-child:before,
table.dataTable.dtr-inline.collapsed>tbody>tr[role=row]>th:first-child:before {
    top: 9px;
    left: 4px;
    height: 14px;
    width: 14px;
    display: block;
    position: absolute;
    color: #fff;
    border: 2px solid #fff;
    border-radius: 14px;
    box-shadow: 0 0 3px #444;
    box-sizing: content-box;
    text-align: center;
    text-indent: 0 !important;
    font-family: 'Courier New', Courier, monospace;
    line-height: 14px;
    content: '+';
    background-color: #337ab7
}

table.dataTable.dtr-inline.collapsed>tbody>tr.parent>td:first-child:before,
table.dataTable.dtr-inline.collapsed>tbody>tr.parent>th:first-child:before {
    content: '-';
    background-color: #d33333
}

table.dataTable.dtr-inline.collapsed.compact>tbody>tr>td:first-child,
table.dataTable.dtr-inline.collapsed.compact>tbody>tr>th:first-child {
    padding-left: 27px
}

table.dataTable.dtr-inline.collapsed.compact>tbody>tr>td:first-child:before,
table.dataTable.dtr-inline.collapsed.compact>tbody>tr>th:first-child:before {
    top: 5px;
    left: 4px;
    height: 14px;
    width: 14px;
    border-radius: 14px;
    line-height: 14px;
    text-indent: 3px
}

table.dataTable.dtr-column>tbody>tr>td.control,
table.dataTable.dtr-column>tbody>tr>th.control {
    position: relative;
    cursor: pointer
}

table.dataTable.dtr-column>tbody>tr>td.control:before,
table.dataTable.dtr-column>tbody>tr>th.control:before {
    top: 50%;
    left: 50%;
    height: 16px;
    width: 16px;
    margin-top: -10px;
    margin-left: -10px;
    display: block;
    position: absolute;
    color: #fff;
    border: 2px solid #fff;
    border-radius: 14px;
    box-shadow: 0 0 3px #444;
    box-sizing: content-box;
    text-align: center;
    text-indent: 0 !important;
    font-family: 'Courier New', Courier, monospace;
    line-height: 14px;
    content: '+';
    background-color: #337ab7
}

table.dataTable.dtr-column>tbody>tr.parent td.control:before,
table.dataTable.dtr-column>tbody>tr.parent th.control:before {
    content: '-';
    background-color: #d33333
}

table.dataTable>tbody>tr.child {
    padding: .5em 1em
}

table.dataTable>tbody>tr.child:hover {
    background: 0 0 !important
}

table.dataTable>tbody>tr.child ul.dtr-details {
    display: inline-block;
    list-style-type: none;
    margin: 0;
    padding: 0
}

table.dataTable>tbody>tr.child ul.dtr-details>li {
    border-bottom: 1px solid #efefef;
    padding: .5em 0
}

table.dataTable>tbody>tr.child ul.dtr-details>li:first-child {
    padding-top: 0
}

table.dataTable>tbody>tr.child ul.dtr-details>li:last-child {
    border-bottom: none
}

table.dataTable>tbody>tr.child span.dtr-title {
    display: inline-block;
    min-width: 75px;
    font-weight: 700
}

div.dtr-modal {
    position: fixed;
    box-sizing: border-box;
    top: 0;
    left: 0;
    height: 100%;
    width: 100%;
    z-index: 100;
    padding: 10em 1em
}

div.dtr-modal div.dtr-modal-display {
    position: absolute;
    top: 0;
    left: 0;
    bottom: 0;
    right: 0;
    width: 50%;
    height: 50%;
    overflow: auto;
    margin: auto;
    z-index: 102;
    overflow: auto;
    background-color: #f5f5f7;
    border: 1px solid #000;
    border-radius: .5em;
    box-shadow: 0 12px 30px rgba(0, 0, 0, .6)
}

div.dtr-modal div.dtr-modal-content {
    position: relative;
    padding: 1em
}

div.dtr-modal div.dtr-modal-close {
    position: absolute;
    top: 6px;
    right: 6px;
    width: 22px;
    height: 22px;
    border: 1px solid #eaeaea;
    background-color: #f9f9f9;
    text-align: center;
    border-radius: 3px;
    cursor: pointer;
    z-index: 12
}

div.dtr-modal div.dtr-modal-close:hover {
    background-color: #eaeaea
}

div.dtr-modal div.dtr-modal-background {
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    z-index: 101;
    background: rgba(0, 0, 0, .6)
}

@media screen and (max-width:767px) {
    div.dtr-modal div.dtr-modal-display {
        width: 95%
    }
}

div.dtr-bs-modal table.table tr:first-child td {
    border-top: none
}

.toast-title {
    font-weight: 700
}

.toast-message {
    -ms-word-wrap: break-word;
    word-wrap: break-word
}

.toast-message a,
.toast-message label {
    color: #fff
}

.toast-message a:hover {
    color: #ccc;
    text-decoration: none
}

.toast-close-button {
    position: relative;
    right: -.3em;
    top: -.3em;
    float: right;
    font-size: 20px;
    font-weight: 700;
    color: #fff;
    -webkit-text-shadow: 0 1px 0 #fff;
    text-shadow: 0 1px 0 #fff;
    opacity: .8;
    line-height: 1
}

.toast-close-button:focus,
.toast-close-button:hover {
    color: #000;
    text-decoration: none;
    cursor: pointer;
    opacity: .4
}

.rtl .toast-close-button {
    left: -.3em;
    float: left;
    right: .3em
}

button.toast-close-button {
    padding: 0;
    cursor: pointer;
    background: 0 0;
    border: 0;
    -webkit-appearance: none
}

.toast-top-center {
    top: 0;
    right: 0;
    width: 100%
}

.toast-bottom-center {
    bottom: 0;
    right: 0;
    width: 100%
}

.toast-top-full-width {
    top: 0;
    right: 0;
    width: 100%
}

.toast-bottom-full-width {
    bottom: 0;
    right: 0;
    width: 100%
}

.toast-top-left {
    top: 12px;
    left: 12px
}

.toast-top-right {
    top: 12px;
    right: 12px
}

.toast-bottom-right {
    right: 12px;
    bottom: 12px
}

.toast-bottom-left {
    bottom: 12px;
    left: 12px
}

#toast-container {
    position: fixed;
    z-index: 999999;
    pointer-events: none
}

#toast-container * {
    -moz-box-sizing: border-box;
    -webkit-box-sizing: border-box;
    box-sizing: border-box
}

#toast-container>div {
    position: relative;
    pointer-events: auto;
    overflow: hidden;
    margin: 0 0 6px;
    padding: 15px 15px 15px 50px;
    width: 300px;
    -moz-border-radius: 3px;
    -webkit-border-radius: 3px;
    border-radius: 3px;
    background-position: 15px center;
    background-repeat: no-repeat;
    -moz-box-shadow: 0 0 12px #999;
    -webkit-box-shadow: 0 0 12px #999;
    box-shadow: 0 0 12px #999;
    color: #fff;
    opacity: .8
}

#toast-container>div.rtl {
    direction: rtl;
    padding: 15px 50px 15px 15px;
    background-position: right 15px center
}

#toast-container>div:hover {
    -moz-box-shadow: 0 0 12px #000;
    -webkit-box-shadow: 0 0 12px #000;
    box-shadow: 0 0 12px #000;
    opacity: 1;
    cursor: pointer
}

#toast-container>.toast-info {
    background-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAGwSURBVEhLtZa9SgNBEMc9sUxxRcoUKSzSWIhXpFMhhYWFhaBg4yPYiWCXZxBLERsLRS3EQkEfwCKdjWJAwSKCgoKCcudv4O5YLrt7EzgXhiU3/4+b2ckmwVjJSpKkQ6wAi4gwhT+z3wRBcEz0yjSseUTrcRyfsHsXmD0AmbHOC9Ii8VImnuXBPglHpQ5wwSVM7sNnTG7Za4JwDdCjxyAiH3nyA2mtaTJufiDZ5dCaqlItILh1NHatfN5skvjx9Z38m69CgzuXmZgVrPIGE763Jx9qKsRozWYw6xOHdER+nn2KkO+Bb+UV5CBN6WC6QtBgbRVozrahAbmm6HtUsgtPC19tFdxXZYBOfkbmFJ1VaHA1VAHjd0pp70oTZzvR+EVrx2Ygfdsq6eu55BHYR8hlcki+n+kERUFG8BrA0BwjeAv2M8WLQBtcy+SD6fNsmnB3AlBLrgTtVW1c2QN4bVWLATaIS60J2Du5y1TiJgjSBvFVZgTmwCU+dAZFoPxGEEs8nyHC9Bwe2GvEJv2WXZb0vjdyFT4Cxk3e/kIqlOGoVLwwPevpYHT+00T+hWwXDf4AJAOUqWcDhbwAAAAASUVORK5CYII=) !important
}

#toast-container>.toast-error {
    background-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAHOSURBVEhLrZa/SgNBEMZzh0WKCClSCKaIYOED+AAKeQQLG8HWztLCImBrYadgIdY+gIKNYkBFSwu7CAoqCgkkoGBI/E28PdbLZmeDLgzZzcx83/zZ2SSXC1j9fr+I1Hq93g2yxH4iwM1vkoBWAdxCmpzTxfkN2RcyZNaHFIkSo10+8kgxkXIURV5HGxTmFuc75B2RfQkpxHG8aAgaAFa0tAHqYFfQ7Iwe2yhODk8+J4C7yAoRTWI3w/4klGRgR4lO7Rpn9+gvMyWp+uxFh8+H+ARlgN1nJuJuQAYvNkEnwGFck18Er4q3egEc/oO+mhLdKgRyhdNFiacC0rlOCbhNVz4H9FnAYgDBvU3QIioZlJFLJtsoHYRDfiZoUyIxqCtRpVlANq0EU4dApjrtgezPFad5S19Wgjkc0hNVnuF4HjVA6C7QrSIbylB+oZe3aHgBsqlNqKYH48jXyJKMuAbiyVJ8KzaB3eRc0pg9VwQ4niFryI68qiOi3AbjwdsfnAtk0bCjTLJKr6mrD9g8iq/S/B81hguOMlQTnVyG40wAcjnmgsCNESDrjme7wfftP4P7SP4N3CJZdvzoNyGq2c/HWOXJGsvVg+RA/k2MC/wN6I2YA2Pt8GkAAAAASUVORK5CYII=) !important
}

#toast-container>.toast-success {
    background-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAADsSURBVEhLY2AYBfQMgf///3P8+/evAIgvA/FsIF+BavYDDWMBGroaSMMBiE8VC7AZDrIFaMFnii3AZTjUgsUUWUDA8OdAH6iQbQEhw4HyGsPEcKBXBIC4ARhex4G4BsjmweU1soIFaGg/WtoFZRIZdEvIMhxkCCjXIVsATV6gFGACs4Rsw0EGgIIH3QJYJgHSARQZDrWAB+jawzgs+Q2UO49D7jnRSRGoEFRILcdmEMWGI0cm0JJ2QpYA1RDvcmzJEWhABhD/pqrL0S0CWuABKgnRki9lLseS7g2AlqwHWQSKH4oKLrILpRGhEQCw2LiRUIa4lwAAAABJRU5ErkJggg==) !important
}

#toast-container>.toast-warning {
    background-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAGYSURBVEhL5ZSvTsNQFMbXZGICMYGYmJhAQIJAICYQPAACiSDB8AiICQQJT4CqQEwgJvYASAQCiZiYmJhAIBATCARJy+9rTsldd8sKu1M0+dLb057v6/lbq/2rK0mS/TRNj9cWNAKPYIJII7gIxCcQ51cvqID+GIEX8ASG4B1bK5gIZFeQfoJdEXOfgX4QAQg7kH2A65yQ87lyxb27sggkAzAuFhbbg1K2kgCkB1bVwyIR9m2L7PRPIhDUIXgGtyKw575yz3lTNs6X4JXnjV+LKM/m3MydnTbtOKIjtz6VhCBq4vSm3ncdrD2lk0VgUXSVKjVDJXJzijW1RQdsU7F77He8u68koNZTz8Oz5yGa6J3H3lZ0xYgXBK2QymlWWA+RWnYhskLBv2vmE+hBMCtbA7KX5drWyRT/2JsqZ2IvfB9Y4bWDNMFbJRFmC9E74SoS0CqulwjkC0+5bpcV1CZ8NMej4pjy0U+doDQsGyo1hzVJttIjhQ7GnBtRFN1UarUlH8F3xict+HY07rEzoUGPlWcjRFRr4/gChZgc3ZL2d8oAAAAASUVORK5CYII=) !important
}

#toast-container.toast-bottom-center>div,
#toast-container.toast-top-center>div {
    width: 300px;
    margin-left: auto;
    margin-right: auto
}

#toast-container.toast-bottom-full-width>div,
#toast-container.toast-top-full-width>div {
    width: 96%;
    margin-left: auto;
    margin-right: auto
}

.toast {
    background-color: #030303
}

.toast-success {
    background-color: #51a351
}

.toast-error {
    background-color: #bd362f
}

.toast-info {
    background-color: #2f96b4
}

.toast-warning {
    background-color: #f89406
}

.toast-progress {
    position: absolute;
    left: 0;
    bottom: 0;
    height: 4px;
    background-color: #000;
    opacity: .4
}

@media all and (max-width:240px) {
    #toast-container>div {
        padding: 8px 8px 8px 50px;
        width: 11em
    }
    #toast-container>div.rtl {
        padding: 8px 50px 8px 8px
    }
    #toast-container .toast-close-button {
        right: -.2em;
        top: -.2em
    }
    #toast-container .rtl .toast-close-button {
        left: -.2em;
        right: .2em
    }
}

@media all and (min-width:241px) and (max-width:480px) {
    #toast-container>div {
        padding: 8px 8px 8px 50px;
        width: 18em
    }
    #toast-container>div.rtl {
        padding: 8px 50px 8px 8px
    }
    #toast-container .toast-close-button {
        right: -.2em;
        top: -.2em
    }
    #toast-container .rtl .toast-close-button {
        left: -.2em;
        right: .2em
    }
}

@media all and (min-width:481px) and (max-width:768px) {
    #toast-container>div {
        padding: 15px 15px 15px 50px;
        width: 25em
    }
    #toast-container>div.rtl {
        padding: 15px 50px 15px 15px
    }
}

/*!
 * bootstrap-fileinput v4.4.3
 * http://plugins.krajee.com/file-input
 *
 * Krajee default styling for bootstrap-fileinput.
 *
 * Author: Kartik Visweswaran
 * Copyright: 2014 - 2017, Kartik Visweswaran, Krajee.com
 *
 * Licensed under the BSD 3-Clause
 * https://github.com/kartik-v/bootstrap-fileinput/blob/master/LICENSE.md
 */

.file-drop-zone,
.krajee-default .file-preview-audio audio,
.krajee-default .file-preview-image,
.krajee-default .file-preview-other {
    vertical-align: middle
}

.file-loading {
    top: 0;
    right: 0;
    width: 25px;
    height: 25px;
    font-size: 999px;
    text-align: right;
    color: #fff;
    background: url(../img/loading.gif) top left no-repeat;
    border: none
}

.file-object {
    margin: 0 0 -5px;
    padding: 0
}

.btn-file {
    position: relative;
    overflow: hidden
}

.btn-file input[type=file] {
    position: absolute;
    top: 0;
    right: 0;
    min-width: 100%;
    min-height: 100%;
    text-align: right;
    opacity: 0;
    background: 0 0;
    cursor: inherit;
    display: block
}

.file-caption-name {
    display: inline-block;
    overflow: hidden;
    height: 20px;
    word-break: break-all
}

.input-group-lg .file-caption-name {
    height: 25px
}

.file-zoom-dialog {
    text-align: left
}

.file-error-message {
    color: #a94442;
    background-color: #f2dede;
    margin: 5px;
    border: 1px solid #ebccd1;
    border-radius: 4px;
    padding: 15px
}

.file-error-message pre,
.file-error-message ul {
    margin: 0;
    text-align: left
}

.file-error-message pre {
    margin: 5px 0
}

.file-caption-disabled {
    background-color: #eee;
    cursor: not-allowed;
    opacity: 1
}

.file-preview {
    border-radius: 5px;
    border: 1px solid #ddd;
    padding: 5px;
    width: 100%;
    margin-bottom: 5px
}

.file-preview-image {
    font: 40px Impact, Charcoal, sans-serif;
    color: green
}

.krajee-default.file-preview-frame {
    position: relative;
    display: table;
    margin: 8px;
    border: 1px solid #ddd;
    box-shadow: 1px 1px 5px 0 #a2958a;
    padding: 6px;
    float: left;
    text-align: center
}

.krajee-default.file-preview-frame:not(.file-preview-error):hover {
    box-shadow: 3px 3px 5px 0 #333
}

.krajee-default.file-preview-frame .kv-file-content {
    height: 170px
}

.krajee-default.file-preview-frame .file-thumbnail-footer {
    height: 70px
}

.krajee-default .file-preview-text {
    display: block;
    color: #428bca;
    border: 1px solid #ddd;
    font-family: Menlo, Monaco, Consolas, "Courier New", monospace;
    outline: 0;
    padding: 8px;
    resize: none
}

.krajee-default .file-preview-html {
    border: 1px solid #ddd;
    padding: 8px;
    overflow: auto
}

.krajee-default[data-template=audio] .file-preview-audio {
    display: table-cell;
    vertical-align: middle;
    height: 170px;
    border: 1px solid #ddd;
    border-radius: 5px
}

.krajee-default .file-zoom-dialog .file-preview-text {
    font-size: 1.2em
}

.krajee-default .file-preview-other {
    left: 0;
    top: 0;
    right: 0;
    bottom: 0;
    margin: auto;
    text-align: center;
    padding: 10px
}

.krajee-default .file-preview-other:hover {
    opacity: .8
}

.krajee-default .file-actions,
.krajee-default .file-other-error {
    text-align: left
}

.krajee-default .file-other-icon {
    font-size: 8em
}

.krajee-default .file-actions {
    margin-top: 15px
}

.krajee-default .file-footer-buttons {
    float: right
}

.krajee-default .file-footer-caption {
    display: block;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
    width: 160px;
    text-align: center;
    padding-top: 4px;
    font-size: 11px;
    color: #777;
    margin: 5px auto
}

.file-input-ajax-new .fileinput-remove-button,
.file-input-ajax-new .fileinput-upload-button,
.file-input-ajax-new .no-browse .input-group-btn,
.file-input-new .close,
.file-input-new .file-preview,
.file-input-new .fileinput-remove-button,
.file-input-new .fileinput-upload-button,
.file-input-new .glyphicon-file,
.file-input-new .no-browse .input-group-btn,
.hide-content .kv-file-content {
    display: none
}

.krajee-default .file-preview-error {
    opacity: .65;
    box-shadow: none
}

.krajee-default .file-preview-frame:not(.file-preview-error) .file-footer-caption:hover {
    color: #000
}

.krajee-default .file-drag-handle,
.krajee-default .file-upload-indicator {
    position: absolute;
    text-align: center;
    bottom: -6px;
    left: -6px;
    padding: 8px 8px 1px 3px;
    border-left: none;
    border-bottom: none;
    border-right: 1px solid #8a6d3b;
    border-top: 1px solid #8a6d3b;
    border-top-right-radius: 24px;
    font-size: 12px
}

.krajee-default .file-drag-handle {
    background-color: #d9edf7;
    border-color: #bce8f1
}

.krajee-default .file-upload-indicator {
    font-size: 13px;
    background-color: #fcf8e3;
    border-color: #faebcc;
    padding-bottom: 0
}

.krajee-default.file-preview-error .file-upload-indicator {
    background-color: #f2dede;
    border-color: #ebccd1
}

.krajee-default.file-preview-success .file-upload-indicator {
    background-color: #dff0d8;
    border-color: #d6e9c6
}

.krajee-default.file-preview-loading .file-upload-indicator {
    background-color: #e5e5e5;
    border-color: #777
}

.krajee-default .file-thumb-progress .progress,
.krajee-default .file-thumb-progress .progress-bar {
    height: 10px;
    font-size: 9px;
    line-height: 10px
}

.krajee-default .file-thumbnail-footer {
    position: relative
}

.krajee-default .file-thumb-progress {
    height: 10px;
    position: absolute;
    top: 35px;
    left: 0;
    right: 0
}

.krajee-default.kvsortable-ghost {
    background: #e1edf7;
    border: 2px solid #a1abff
}

.file-zoom-dialog .file-other-icon {
    font-size: 22em;
    font-size: 50vmin
}

.file-caption-main {
    width: 100%
}

.file-input-ajax-new .no-browse .form-control,
.file-input-new .no-browse .form-control {
    border-top-right-radius: 4px;
    border-bottom-right-radius: 4px
}

.file-thumb-loading {
    background: url(../img/loading.gif) center center no-repeat content-box !important
}

.file-sortable .file-drag-handle {
    cursor: move;
    cursor: -webkit-grabbing;
    opacity: 1
}

.file-sortable .file-drag-handle:hover {
    opacity: .7
}

.file-drop-zone {
    border: 1px dashed #aaa;
    border-radius: 4px;
    height: 100%;
    text-align: center;
    margin: 12px 15px 12px 12px;
    padding: 5px
}

.file-drop-zone-title {
    color: #aaa;
    font-size: 1.6em;
    padding: 85px 10px;
    cursor: default
}

.clickable .file-drop-zone-title,
.file-preview .clickable {
    cursor: pointer
}

.file-drop-zone.clickable:hover {
    border: 2px dashed #999
}

.file-drop-zone.clickable:focus {
    border: 2px solid #5acde2
}

.file-drop-zone .file-preview-thumbnails {
    cursor: default
}

.file-highlighted {
    border: 2px dashed #999 !important;
    background-color: #f0f0f0
}

.file-uploading {
    background: url(../img/loading-sm.gif) center bottom 10px no-repeat;
    opacity: .65
}

.file-zoom-fullscreen.modal {
    position: fixed;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0
}

.file-zoom-fullscreen .modal-dialog {
    position: fixed;
    margin: 0;
    width: 100%;
    height: 100%;
    padding: 0
}

.file-zoom-fullscreen .modal-content {
    border-radius: 0;
    box-shadow: none
}

.file-zoom-fullscreen .modal-body {
    overflow-y: auto
}

.file-zoom-dialog .modal-body {
    position: relative !important
}

.file-zoom-dialog .btn-navigate {
    position: absolute;
    padding: 0;
    margin: 0;
    background: 0 0;
    text-decoration: none;
    outline: 0;
    opacity: .7;
    top: 45%;
    font-size: 4em;
    color: #1c94c4
}

.file-zoom-dialog .floating-buttons {
    position: absolute;
    top: 5px;
    right: 10px
}

.floating-buttons,
.floating-buttons .btn {
    z-index: 3000
}

.file-zoom-dialog .kv-zoom-actions .btn,
.floating-buttons .btn {
    margin-left: 3px
}

.file-zoom-dialog .btn-navigate:not([disabled]):focus,
.file-zoom-dialog .btn-navigate:not([disabled]):hover {
    outline: 0;
    box-shadow: none;
    opacity: .5
}

.file-zoom-dialog .btn-navigate[disabled] {
    opacity: .3
}

.file-zoom-dialog .btn-prev {
    left: 1px
}

.file-zoom-dialog .btn-next {
    right: 1px
}

.file-zoom-content {
    height: 480px;
    text-align: center
}

.file-zoom-content .file-preview-image,
.file-zoom-content .file-preview-video {
    max-height: 100%
}

.file-zoom-content>.file-object.type-image {
    width: auto;
    height: auto;
    min-height: inherit;
    max-width: 100%;
    max-height: 100%
}

.file-zoom-content>.file-object.type-flash,
.file-zoom-content>.file-object.type-video {
    width: auto;
    height: 100%;
    max-width: 100%;
    max-height: 100%
}

.file-zoom-content>.file-object.type-audio {
    width: auto;
    height: 30px
}

.file-zoom-content>.file-object.type-default,
.file-zoom-content>.file-object.type-html,
.file-zoom-content>.file-object.type-pdf,
.file-zoom-content>.file-object.type-text {
    width: 100%
}

.file-preview-initial.sortable-chosen {
    background-color: #d9edf7
}

.btn-file ::-ms-browse {
    font-size: 10000px;
    width: 100%;
    height: 100%
}

.rotate-2 {
    transform: rotateY(180deg)
}

.rotate-3 {
    transform: rotate(180deg)
}

.rotate-4 {
    transform: rotate(180deg) rotateY(180deg)
}

.rotate-5 {
    transform: rotate(270deg) rotateY(180deg)
}

.rotate-6 {
    transform: rotate(90deg)
}

.rotate-7 {
    transform: rotate(90deg) rotateY(180deg)
}

.rotate-8 {
    transform: rotate(270deg)
}

.file-zoom-content .is-portrait-gt4 {
    margin-top: 60px
}

.skin-blue .main-header .navbar {
    background-color: #3c8dbc
}

.skin-blue .main-header .navbar .nav>li>a {
    color: #fff
}

.skin-blue .main-header .navbar .nav .open>a,
.skin-blue .main-header .navbar .nav .open>a:focus,
.skin-blue .main-header .navbar .nav .open>a:hover,
.skin-blue .main-header .navbar .nav>.active>a,
.skin-blue .main-header .navbar .nav>li>a:active,
.skin-blue .main-header .navbar .nav>li>a:focus,
.skin-blue .main-header .navbar .nav>li>a:hover {
    background: rgba(0, 0, 0, .1);
    color: #f6f6f6
}

.skin-blue .main-header .navbar .sidebar-toggle {
    color: #fff
}

.skin-blue .main-header .navbar .sidebar-toggle:hover {
    color: #f6f6f6;
    background: rgba(0, 0, 0, .1)
}

.skin-blue .main-header .navbar .sidebar-toggle {
    color: #fff
}

.skin-blue .main-header .navbar .sidebar-toggle:hover {
    background-color: #367fa9
}

@media (max-width:767px) {
    .skin-blue .main-header .navbar .dropdown-menu li.divider {
        background-color: rgba(255, 255, 255, .1)
    }
    .skin-blue .main-header .navbar .dropdown-menu li a {
        color: #fff
    }
    .skin-blue .main-header .navbar .dropdown-menu li a:hover {
        background: #367fa9
    }
}

.skin-blue .main-header .logo {
    background-color: #367fa9;
    color: #fff;
    border-bottom: 0 solid transparent
}

.skin-blue .main-header .logo:hover {
    background-color: #357ca5
}

.skin-blue .main-header li.user-header {
    background-color: #3c8dbc
}

.skin-blue .content-header {
    background: 0 0
}

.skin-blue .left-side,
.skin-blue .main-sidebar,
.skin-blue .wrapper {
    background-color: #222d32
}

.skin-blue .user-panel>.info,
.skin-blue .user-panel>.info>a {
    color: #fff
}

.skin-blue .sidebar-menu>li.header {
    color: #4b646f;
    background: #1a2226
}

.skin-blue .sidebar-menu>li>a {
    border-left: 3px solid transparent
}

.skin-blue .sidebar-menu>li.active>a,
.skin-blue .sidebar-menu>li.menu-open>a,
.skin-blue .sidebar-menu>li:hover>a {
    color: #fff;
    background: #1e282c
}

.skin-blue .sidebar-menu>li.active>a {
    border-left-color: #3c8dbc
}

.skin-blue .sidebar-menu>li>.treeview-menu {
    margin: 0 1px;
    background: #2c3b41
}

.skin-blue .sidebar a {
    color: #b8c7ce
}

.skin-blue .sidebar a:hover {
    text-decoration: none
}

.skin-blue .sidebar-menu .treeview-menu>li>a {
    color: #8aa4af
}

.skin-blue .sidebar-menu .treeview-menu>li.active>a,
.skin-blue .sidebar-menu .treeview-menu>li>a:hover {
    color: #fff
}

.skin-blue .sidebar-form {
    border-radius: 3px;
    border: 1px solid #374850;
    margin: 10px 10px
}

.skin-blue .sidebar-form .btn,
.skin-blue .sidebar-form input[type=text] {
    box-shadow: none;
    background-color: #374850;
    border: 1px solid transparent;
    height: 35px
}

.skin-blue .sidebar-form input[type=text] {
    color: #666;
    border-top-left-radius: 2px;
    border-top-right-radius: 0;
    border-bottom-right-radius: 0;
    border-bottom-left-radius: 2px
}

.skin-blue .sidebar-form input[type=text]:focus,
.skin-blue .sidebar-form input[type=text]:focus+.input-group-btn .btn {
    background-color: #fff;
    color: #666
}

.skin-blue .sidebar-form input[type=text]:focus+.input-group-btn .btn {
    border-left-color: #fff
}

.skin-blue .sidebar-form .btn {
    color: #999;
    border-top-left-radius: 0;
    border-top-right-radius: 2px;
    border-bottom-right-radius: 2px;
    border-bottom-left-radius: 0
}

.skin-blue.layout-top-nav .main-header>.logo {
    background-color: #3c8dbc;
    color: #fff;
    border-bottom: 0 solid transparent
}

.skin-blue.layout-top-nav .main-header>.logo:hover {
    background-color: #3b8ab8
}

.skin-blue-light .main-header .navbar {
    background-color: #3c8dbc
}

.skin-blue-light .main-header .navbar .nav>li>a {
    color: #fff
}

.skin-blue-light .main-header .navbar .nav .open>a,
.skin-blue-light .main-header .navbar .nav .open>a:focus,
.skin-blue-light .main-header .navbar .nav .open>a:hover,
.skin-blue-light .main-header .navbar .nav>.active>a,
.skin-blue-light .main-header .navbar .nav>li>a:active,
.skin-blue-light .main-header .navbar .nav>li>a:focus,
.skin-blue-light .main-header .navbar .nav>li>a:hover {
    background: rgba(0, 0, 0, .1);
    color: #f6f6f6
}

.skin-blue-light .main-header .navbar .sidebar-toggle {
    color: #fff
}

.skin-blue-light .main-header .navbar .sidebar-toggle:hover {
    color: #f6f6f6;
    background: rgba(0, 0, 0, .1)
}

.skin-blue-light .main-header .navbar .sidebar-toggle {
    color: #fff
}

.skin-blue-light .main-header .navbar .sidebar-toggle:hover {
    background-color: #367fa9
}

@media (max-width:767px) {
    .skin-blue-light .main-header .navbar .dropdown-menu li.divider {
        background-color: rgba(255, 255, 255, .1)
    }
    .skin-blue-light .main-header .navbar .dropdown-menu li a {
        color: #fff
    }
    .skin-blue-light .main-header .navbar .dropdown-menu li a:hover {
        background: #367fa9
    }
}

.skin-blue-light .main-header .logo {
    background-color: #3c8dbc;
    color: #fff;
    border-bottom: 0 solid transparent
}

.skin-blue-light .main-header .logo:hover {
    background-color: #3b8ab8
}

.skin-blue-light .main-header li.user-header {
    background-color: #3c8dbc
}

.skin-blue-light .content-header {
    background: 0 0
}

.skin-blue-light .left-side,
.skin-blue-light .main-sidebar,
.skin-blue-light .wrapper {
    background-color: #f9fafc
}

.skin-blue-light .main-sidebar {
    border-right: 1px solid #d2d6de
}

.skin-blue-light .user-panel>.info,
.skin-blue-light .user-panel>.info>a {
    color: #444
}

.skin-blue-light .sidebar-menu>li {
    -webkit-transition: border-left-color .3s ease;
    -o-transition: border-left-color .3s ease;
    transition: border-left-color .3s ease
}

.skin-blue-light .sidebar-menu>li.header {
    color: #848484;
    background: #f9fafc
}

.skin-blue-light .sidebar-menu>li>a {
    border-left: 3px solid transparent;
    font-weight: 600
}

.skin-blue-light .sidebar-menu>li.active>a,
.skin-blue-light .sidebar-menu>li:hover>a {
    color: #000;
    background: #f4f4f5
}

.skin-blue-light .sidebar-menu>li.active {
    border-left-color: #3c8dbc
}

.skin-blue-light .sidebar-menu>li.active>a {
    font-weight: 600
}

.skin-blue-light .sidebar-menu>li>.treeview-menu {
    background: #f4f4f5
}

.skin-blue-light .sidebar a {
    color: #444
}

.skin-blue-light .sidebar a:hover {
    text-decoration: none
}

.skin-blue-light .sidebar-menu .treeview-menu>li>a {
    color: #777
}

.skin-blue-light .sidebar-menu .treeview-menu>li.active>a,
.skin-blue-light .sidebar-menu .treeview-menu>li>a:hover {
    color: #000
}

.skin-blue-light .sidebar-menu .treeview-menu>li.active>a {
    font-weight: 600
}

.skin-blue-light .sidebar-form {
    border-radius: 3px;
    border: 1px solid #d2d6de;
    margin: 10px 10px
}

.skin-blue-light .sidebar-form .btn,
.skin-blue-light .sidebar-form input[type=text] {
    box-shadow: none;
    background-color: #fff;
    border: 1px solid transparent;
    height: 35px
}

.skin-blue-light .sidebar-form input[type=text] {
    color: #666;
    border-top-left-radius: 2px;
    border-top-right-radius: 0;
    border-bottom-right-radius: 0;
    border-bottom-left-radius: 2px
}

.skin-blue-light .sidebar-form input[type=text]:focus,
.skin-blue-light .sidebar-form input[type=text]:focus+.input-group-btn .btn {
    background-color: #fff;
    color: #666
}

.skin-blue-light .sidebar-form input[type=text]:focus+.input-group-btn .btn {
    border-left-color: #fff
}

.skin-blue-light .sidebar-form .btn {
    color: #999;
    border-top-left-radius: 0;
    border-top-right-radius: 2px;
    border-bottom-right-radius: 2px;
    border-bottom-left-radius: 0
}

@media (min-width:768px) {
    .skin-blue-light.sidebar-mini.sidebar-collapse .sidebar-menu>li>.treeview-menu {
        border-left: 1px solid #d2d6de
    }
}

.skin-blue-light .main-footer {
    border-top-color: #d2d6de
}

.skin-blue.layout-top-nav .main-header>.logo {
    background-color: #3c8dbc;
    color: #fff;
    border-bottom: 0 solid transparent
}

.skin-blue.layout-top-nav .main-header>.logo:hover {
    background-color: #3b8ab8
}

.skin-black .main-header {
    -webkit-box-shadow: 0 1px 1px rgba(0, 0, 0, .05);
    box-shadow: 0 1px 1px rgba(0, 0, 0, .05)
}

.skin-black .main-header .navbar-toggle {
    color: #333
}

.skin-black .main-header .navbar-brand {
    color: #333;
    border-right: 1px solid #eee
}

.skin-black .main-header .navbar {
    background-color: #fff
}

.skin-black .main-header .navbar .nav>li>a {
    color: #333
}

.skin-black .main-header .navbar .nav .open>a,
.skin-black .main-header .navbar .nav .open>a:focus,
.skin-black .main-header .navbar .nav .open>a:hover,
.skin-black .main-header .navbar .nav>.active>a,
.skin-black .main-header .navbar .nav>li>a:active,
.skin-black .main-header .navbar .nav>li>a:focus,
.skin-black .main-header .navbar .nav>li>a:hover {
    background: #fff;
    color: #999
}

.skin-black .main-header .navbar .sidebar-toggle {
    color: #333
}

.skin-black .main-header .navbar .sidebar-toggle:hover {
    color: #999;
    background: #fff
}

.skin-black .main-header .navbar>.sidebar-toggle {
    color: #333;
    border-right: 1px solid #eee
}

.skin-black .main-header .navbar .navbar-nav>li>a {
    border-right: 1px solid #eee
}

.skin-black .main-header .navbar .navbar-custom-menu .navbar-nav>li>a,
.skin-black .main-header .navbar .navbar-right>li>a {
    border-left: 1px solid #eee;
    border-right-width: 0
}

.skin-black .main-header .logo {
    background-color: #fff;
    color: #333;
    border-bottom: 0 solid transparent;
    border-right: 1px solid #eee
}

.skin-black .main-header .logo:hover {
    background-color: #fcfcfc
}

@media (max-width:767px) {
    .skin-black .main-header .logo {
        background-color: #222;
        color: #fff;
        border-bottom: 0 solid transparent;
        border-right: none
    }
    .skin-black .main-header .logo:hover {
        background-color: #1f1f1f
    }
}

.skin-black .main-header li.user-header {
    background-color: #222
}

.skin-black .content-header {
    background: 0 0;
    box-shadow: none
}

.skin-black .left-side,
.skin-black .main-sidebar,
.skin-black .wrapper {
    background-color: #222d32
}

.skin-black .user-panel>.info,
.skin-black .user-panel>.info>a {
    color: #fff
}

.skin-black .sidebar-menu>li.header {
    color: #4b646f;
    background: #1a2226
}

.skin-black .sidebar-menu>li>a {
    border-left: 3px solid transparent
}

.skin-black .sidebar-menu>li.active>a,
.skin-black .sidebar-menu>li.menu-open>a,
.skin-black .sidebar-menu>li:hover>a {
    color: #fff;
    background: #1e282c
}

.skin-black .sidebar-menu>li.active>a {
    border-left-color: #fff
}

.skin-black .sidebar-menu>li>.treeview-menu {
    margin: 0 1px;
    background: #2c3b41
}

.skin-black .sidebar a {
    color: #b8c7ce
}

.skin-black .sidebar a:hover {
    text-decoration: none
}

.skin-black .sidebar-menu .treeview-menu>li>a {
    color: #8aa4af
}

.skin-black .sidebar-menu .treeview-menu>li.active>a,
.skin-black .sidebar-menu .treeview-menu>li>a:hover {
    color: #fff
}

.skin-black .sidebar-form {
    border-radius: 3px;
    border: 1px solid #374850;
    margin: 10px 10px
}

.skin-black .sidebar-form .btn,
.skin-black .sidebar-form input[type=text] {
    box-shadow: none;
    background-color: #374850;
    border: 1px solid transparent;
    height: 35px
}

.skin-black .sidebar-form input[type=text] {
    color: #666;
    border-top-left-radius: 2px;
    border-top-right-radius: 0;
    border-bottom-right-radius: 0;
    border-bottom-left-radius: 2px
}

.skin-black .sidebar-form input[type=text]:focus,
.skin-black .sidebar-form input[type=text]:focus+.input-group-btn .btn {
    background-color: #fff;
    color: #666
}

.skin-black .sidebar-form input[type=text]:focus+.input-group-btn .btn {
    border-left-color: #fff
}

.skin-black .sidebar-form .btn {
    color: #999;
    border-top-left-radius: 0;
    border-top-right-radius: 2px;
    border-bottom-right-radius: 2px;
    border-bottom-left-radius: 0
}

.skin-black .pace .pace-progress {
    background: #222
}

.skin-black .pace .pace-activity {
    border-top-color: #222;
    border-left-color: #222
}

.skin-black-light .main-header {
    -webkit-box-shadow: 0 1px 1px rgba(0, 0, 0, .05);
    box-shadow: 0 1px 1px rgba(0, 0, 0, .05)
}

.skin-black-light .main-header .navbar-toggle {
    color: #333
}

.skin-black-light .main-header .navbar-brand {
    color: #333;
    border-right: 1px solid #d2d6de
}

.skin-black-light .main-header .navbar {
    background-color: #fff
}

.skin-black-light .main-header .navbar .nav>li>a {
    color: #333
}

.skin-black-light .main-header .navbar .nav .open>a,
.skin-black-light .main-header .navbar .nav .open>a:focus,
.skin-black-light .main-header .navbar .nav .open>a:hover,
.skin-black-light .main-header .navbar .nav>.active>a,
.skin-black-light .main-header .navbar .nav>li>a:active,
.skin-black-light .main-header .navbar .nav>li>a:focus,
.skin-black-light .main-header .navbar .nav>li>a:hover {
    background: #fff;
    color: #999
}

.skin-black-light .main-header .navbar .sidebar-toggle {
    color: #333
}

.skin-black-light .main-header .navbar .sidebar-toggle:hover {
    color: #999;
    background: #fff
}

.skin-black-light .main-header .navbar>.sidebar-toggle {
    color: #333;
    border-right: 1px solid #d2d6de
}

.skin-black-light .main-header .navbar .navbar-nav>li>a {
    border-right: 1px solid #d2d6de
}

.skin-black-light .main-header .navbar .navbar-custom-menu .navbar-nav>li>a,
.skin-black-light .main-header .navbar .navbar-right>li>a {
    border-left: 1px solid #d2d6de;
    border-right-width: 0
}

.skin-black-light .main-header .logo {
    background-color: #fff;
    color: #333;
    border-bottom: 0 solid transparent;
    border-right: 1px solid #d2d6de
}

.skin-black-light .main-header .logo:hover {
    background-color: #fcfcfc
}

@media (max-width:767px) {
    .skin-black-light .main-header .logo {
        background-color: #222;
        color: #fff;
        border-bottom: 0 solid transparent;
        border-right: none
    }
    .skin-black-light .main-header .logo:hover {
        background-color: #1f1f1f
    }
}

.skin-black-light .main-header li.user-header {
    background-color: #222
}

.skin-black-light .content-header {
    background: 0 0;
    box-shadow: none
}

.skin-black-light .left-side,
.skin-black-light .main-sidebar,
.skin-black-light .wrapper {
    background-color: #f9fafc
}

.skin-black-light .main-sidebar {
    border-right: 1px solid #d2d6de
}

.skin-black-light .user-panel>.info,
.skin-black-light .user-panel>.info>a {
    color: #444
}

.skin-black-light .sidebar-menu>li {
    -webkit-transition: border-left-color .3s ease;
    -o-transition: border-left-color .3s ease;
    transition: border-left-color .3s ease
}

.skin-black-light .sidebar-menu>li.header {
    color: #848484;
    background: #f9fafc
}

.skin-black-light .sidebar-menu>li>a {
    border-left: 3px solid transparent;
    font-weight: 600
}

.skin-black-light .sidebar-menu>li.active>a,
.skin-black-light .sidebar-menu>li:hover>a {
    color: #000;
    background: #f4f4f5
}

.skin-black-light .sidebar-menu>li.active {
    border-left-color: #fff
}

.skin-black-light .sidebar-menu>li.active>a {
    font-weight: 600
}

.skin-black-light .sidebar-menu>li>.treeview-menu {
    background: #f4f4f5
}

.skin-black-light .sidebar a {
    color: #444
}

.skin-black-light .sidebar a:hover {
    text-decoration: none
}

.skin-black-light .sidebar-menu .treeview-menu>li>a {
    color: #777
}

.skin-black-light .sidebar-menu .treeview-menu>li.active>a,
.skin-black-light .sidebar-menu .treeview-menu>li>a:hover {
    color: #000
}

.skin-black-light .sidebar-menu .treeview-menu>li.active>a {
    font-weight: 600
}

.skin-black-light .sidebar-form {
    border-radius: 3px;
    border: 1px solid #d2d6de;
    margin: 10px 10px
}

.skin-black-light .sidebar-form .btn,
.skin-black-light .sidebar-form input[type=text] {
    box-shadow: none;
    background-color: #fff;
    border: 1px solid transparent;
    height: 35px
}

.skin-black-light .sidebar-form input[type=text] {
    color: #666;
    border-top-left-radius: 2px;
    border-top-right-radius: 0;
    border-bottom-right-radius: 0;
    border-bottom-left-radius: 2px
}

.skin-black-light .sidebar-form input[type=text]:focus,
.skin-black-light .sidebar-form input[type=text]:focus+.input-group-btn .btn {
    background-color: #fff;
    color: #666
}

.skin-black-light .sidebar-form input[type=text]:focus+.input-group-btn .btn {
    border-left-color: #fff
}

.skin-black-light .sidebar-form .btn {
    color: #999;
    border-top-left-radius: 0;
    border-top-right-radius: 2px;
    border-bottom-right-radius: 2px;
    border-bottom-left-radius: 0
}

@media (min-width:768px) {
    .skin-black-light.sidebar-mini.sidebar-collapse .sidebar-menu>li>.treeview-menu {
        border-left: 1px solid #d2d6de
    }
}

.skin-green .main-header .navbar {
    background-color: #00a65a
}

.skin-green .main-header .navbar .nav>li>a {
    color: #fff
}

.skin-green .main-header .navbar .nav .open>a,
.skin-green .main-header .navbar .nav .open>a:focus,
.skin-green .main-header .navbar .nav .open>a:hover,
.skin-green .main-header .navbar .nav>.active>a,
.skin-green .main-header .navbar .nav>li>a:active,
.skin-green .main-header .navbar .nav>li>a:focus,
.skin-green .main-header .navbar .nav>li>a:hover {
    background: rgba(0, 0, 0, .1);
    color: #f6f6f6
}

.skin-green .main-header .navbar .sidebar-toggle {
    color: #fff
}

.skin-green .main-header .navbar .sidebar-toggle:hover {
    color: #f6f6f6;
    background: rgba(0, 0, 0, .1)
}

.skin-green .main-header .navbar .sidebar-toggle {
    color: #fff
}

.skin-green .main-header .navbar .sidebar-toggle:hover {
    background-color: #008d4c
}

@media (max-width:767px) {
    .skin-green .main-header .navbar .dropdown-menu li.divider {
        background-color: rgba(255, 255, 255, .1)
    }
    .skin-green .main-header .navbar .dropdown-menu li a {
        color: #fff
    }
    .skin-green .main-header .navbar .dropdown-menu li a:hover {
        background: #008d4c
    }
}

.skin-green .main-header .logo {
    background-color: #008d4c;
    color: #fff;
    border-bottom: 0 solid transparent
}

.skin-green .main-header .logo:hover {
    background-color: #008749
}

.skin-green .main-header li.user-header {
    background-color: #00a65a
}

.skin-green .content-header {
    background: 0 0
}

.skin-green .left-side,
.skin-green .main-sidebar,
.skin-green .wrapper {
    background-color: #222d32
}

.skin-green .user-panel>.info,
.skin-green .user-panel>.info>a {
    color: #fff
}

.skin-green .sidebar-menu>li.header {
    color: #4b646f;
    background: #1a2226
}

.skin-green .sidebar-menu>li>a {
    border-left: 3px solid transparent
}

.skin-green .sidebar-menu>li.active>a,
.skin-green .sidebar-menu>li.menu-open>a,
.skin-green .sidebar-menu>li:hover>a {
    color: #fff;
    background: #1e282c
}

.skin-green .sidebar-menu>li.active>a {
    border-left-color: #00a65a
}

.skin-green .sidebar-menu>li>.treeview-menu {
    margin: 0 1px;
    background: #2c3b41
}

.skin-green .sidebar a {
    color: #b8c7ce
}

.skin-green .sidebar a:hover {
    text-decoration: none
}

.skin-green .sidebar-menu .treeview-menu>li>a {
    color: #8aa4af
}

.skin-green .sidebar-menu .treeview-menu>li.active>a,
.skin-green .sidebar-menu .treeview-menu>li>a:hover {
    color: #fff
}

.skin-green .sidebar-form {
    border-radius: 3px;
    border: 1px solid #374850;
    margin: 10px 10px
}

.skin-green .sidebar-form .btn,
.skin-green .sidebar-form input[type=text] {
    box-shadow: none;
    background-color: #374850;
    border: 1px solid transparent;
    height: 35px
}

.skin-green .sidebar-form input[type=text] {
    color: #666;
    border-top-left-radius: 2px;
    border-top-right-radius: 0;
    border-bottom-right-radius: 0;
    border-bottom-left-radius: 2px
}

.skin-green .sidebar-form input[type=text]:focus,
.skin-green .sidebar-form input[type=text]:focus+.input-group-btn .btn {
    background-color: #fff;
    color: #666
}

.skin-green .sidebar-form input[type=text]:focus+.input-group-btn .btn {
    border-left-color: #fff
}

.skin-green .sidebar-form .btn {
    color: #999;
    border-top-left-radius: 0;
    border-top-right-radius: 2px;
    border-bottom-right-radius: 2px;
    border-bottom-left-radius: 0
}

.skin-green-light .main-header .navbar {
    background-color: #00a65a
}

.skin-green-light .main-header .navbar .nav>li>a {
    color: #fff
}

.skin-green-light .main-header .navbar .nav .open>a,
.skin-green-light .main-header .navbar .nav .open>a:focus,
.skin-green-light .main-header .navbar .nav .open>a:hover,
.skin-green-light .main-header .navbar .nav>.active>a,
.skin-green-light .main-header .navbar .nav>li>a:active,
.skin-green-light .main-header .navbar .nav>li>a:focus,
.skin-green-light .main-header .navbar .nav>li>a:hover {
    background: rgba(0, 0, 0, .1);
    color: #f6f6f6
}

.skin-green-light .main-header .navbar .sidebar-toggle {
    color: #fff
}

.skin-green-light .main-header .navbar .sidebar-toggle:hover {
    color: #f6f6f6;
    background: rgba(0, 0, 0, .1)
}

.skin-green-light .main-header .navbar .sidebar-toggle {
    color: #fff
}

.skin-green-light .main-header .navbar .sidebar-toggle:hover {
    background-color: #008d4c
}

@media (max-width:767px) {
    .skin-green-light .main-header .navbar .dropdown-menu li.divider {
        background-color: rgba(255, 255, 255, .1)
    }
    .skin-green-light .main-header .navbar .dropdown-menu li a {
        color: #fff
    }
    .skin-green-light .main-header .navbar .dropdown-menu li a:hover {
        background: #008d4c
    }
}

.skin-green-light .main-header .logo {
    background-color: #00a65a;
    color: #fff;
    border-bottom: 0 solid transparent
}

.skin-green-light .main-header .logo:hover {
    background-color: #00a157
}

.skin-green-light .main-header li.user-header {
    background-color: #00a65a
}

.skin-green-light .content-header {
    background: 0 0
}

.skin-green-light .left-side,
.skin-green-light .main-sidebar,
.skin-green-light .wrapper {
    background-color: #f9fafc
}

.skin-green-light .main-sidebar {
    border-right: 1px solid #d2d6de
}

.skin-green-light .user-panel>.info,
.skin-green-light .user-panel>.info>a {
    color: #444
}

.skin-green-light .sidebar-menu>li {
    -webkit-transition: border-left-color .3s ease;
    -o-transition: border-left-color .3s ease;
    transition: border-left-color .3s ease
}

.skin-green-light .sidebar-menu>li.header {
    color: #848484;
    background: #f9fafc
}

.skin-green-light .sidebar-menu>li>a {
    border-left: 3px solid transparent;
    font-weight: 600
}

.skin-green-light .sidebar-menu>li.active>a,
.skin-green-light .sidebar-menu>li:hover>a {
    color: #000;
    background: #f4f4f5
}

.skin-green-light .sidebar-menu>li.active {
    border-left-color: #00a65a
}

.skin-green-light .sidebar-menu>li.active>a {
    font-weight: 600
}

.skin-green-light .sidebar-menu>li>.treeview-menu {
    background: #f4f4f5
}

.skin-green-light .sidebar a {
    color: #444
}

.skin-green-light .sidebar a:hover {
    text-decoration: none
}

.skin-green-light .sidebar-menu .treeview-menu>li>a {
    color: #777
}

.skin-green-light .sidebar-menu .treeview-menu>li.active>a,
.skin-green-light .sidebar-menu .treeview-menu>li>a:hover {
    color: #000
}

.skin-green-light .sidebar-menu .treeview-menu>li.active>a {
    font-weight: 600
}

.skin-green-light .sidebar-form {
    border-radius: 3px;
    border: 1px solid #d2d6de;
    margin: 10px 10px
}

.skin-green-light .sidebar-form .btn,
.skin-green-light .sidebar-form input[type=text] {
    box-shadow: none;
    background-color: #fff;
    border: 1px solid transparent;
    height: 35px
}

.skin-green-light .sidebar-form input[type=text] {
    color: #666;
    border-top-left-radius: 2px;
    border-top-right-radius: 0;
    border-bottom-right-radius: 0;
    border-bottom-left-radius: 2px
}

.skin-green-light .sidebar-form input[type=text]:focus,
.skin-green-light .sidebar-form input[type=text]:focus+.input-group-btn .btn {
    background-color: #fff;
    color: #666
}

.skin-green-light .sidebar-form input[type=text]:focus+.input-group-btn .btn {
    border-left-color: #fff
}

.skin-green-light .sidebar-form .btn {
    color: #999;
    border-top-left-radius: 0;
    border-top-right-radius: 2px;
    border-bottom-right-radius: 2px;
    border-bottom-left-radius: 0
}

@media (min-width:768px) {
    .skin-green-light.sidebar-mini.sidebar-collapse .sidebar-menu>li>.treeview-menu {
        border-left: 1px solid #d2d6de
    }
}

.skin-red .main-header .navbar {
    background-color: #dd4b39
}

.skin-red .main-header .navbar .nav>li>a {
    color: #fff
}

.skin-red .main-header .navbar .nav .open>a,
.skin-red .main-header .navbar .nav .open>a:focus,
.skin-red .main-header .navbar .nav .open>a:hover,
.skin-red .main-header .navbar .nav>.active>a,
.skin-red .main-header .navbar .nav>li>a:active,
.skin-red .main-header .navbar .nav>li>a:focus,
.skin-red .main-header .navbar .nav>li>a:hover {
    background: rgba(0, 0, 0, .1);
    color: #f6f6f6
}

.skin-red .main-header .navbar .sidebar-toggle {
    color: #fff
}

.skin-red .main-header .navbar .sidebar-toggle:hover {
    color: #f6f6f6;
    background: rgba(0, 0, 0, .1)
}

.skin-red .main-header .navbar .sidebar-toggle {
    color: #fff
}

.skin-red .main-header .navbar .sidebar-toggle:hover {
    background-color: #d73925
}

@media (max-width:767px) {
    .skin-red .main-header .navbar .dropdown-menu li.divider {
        background-color: rgba(255, 255, 255, .1)
    }
    .skin-red .main-header .navbar .dropdown-menu li a {
        color: #fff
    }
    .skin-red .main-header .navbar .dropdown-menu li a:hover {
        background: #d73925
    }
}

.skin-red .main-header .logo {
    background-color: #d73925;
    color: #fff;
    border-bottom: 0 solid transparent
}

.skin-red .main-header .logo:hover {
    background-color: #d33724
}

.skin-red .main-header li.user-header {
    background-color: #dd4b39
}

.skin-red .content-header {
    background: 0 0
}

.skin-red .left-side,
.skin-red .main-sidebar,
.skin-red .wrapper {
    background-color: #222d32
}

.skin-red .user-panel>.info,
.skin-red .user-panel>.info>a {
    color: #fff
}

.skin-red .sidebar-menu>li.header {
    color: #4b646f;
    background: #1a2226
}

.skin-red .sidebar-menu>li>a {
    border-left: 3px solid transparent
}

.skin-red .sidebar-menu>li.active>a,
.skin-red .sidebar-menu>li.menu-open>a,
.skin-red .sidebar-menu>li:hover>a {
    color: #fff;
    background: #1e282c
}

.skin-red .sidebar-menu>li.active>a {
    border-left-color: #dd4b39
}

.skin-red .sidebar-menu>li>.treeview-menu {
    margin: 0 1px;
    background: #2c3b41
}

.skin-red .sidebar a {
    color: #b8c7ce
}

.skin-red .sidebar a:hover {
    text-decoration: none
}

.skin-red .sidebar-menu .treeview-menu>li>a {
    color: #8aa4af
}

.skin-red .sidebar-menu .treeview-menu>li.active>a,
.skin-red .sidebar-menu .treeview-menu>li>a:hover {
    color: #fff
}

.skin-red .sidebar-form {
    border-radius: 3px;
    border: 1px solid #374850;
    margin: 10px 10px
}

.skin-red .sidebar-form .btn,
.skin-red .sidebar-form input[type=text] {
    box-shadow: none;
    background-color: #374850;
    border: 1px solid transparent;
    height: 35px
}

.skin-red .sidebar-form input[type=text] {
    color: #666;
    border-top-left-radius: 2px;
    border-top-right-radius: 0;
    border-bottom-right-radius: 0;
    border-bottom-left-radius: 2px
}

.skin-red .sidebar-form input[type=text]:focus,
.skin-red .sidebar-form input[type=text]:focus+.input-group-btn .btn {
    background-color: #fff;
    color: #666
}

.skin-red .sidebar-form input[type=text]:focus+.input-group-btn .btn {
    border-left-color: #fff
}

.skin-red .sidebar-form .btn {
    color: #999;
    border-top-left-radius: 0;
    border-top-right-radius: 2px;
    border-bottom-right-radius: 2px;
    border-bottom-left-radius: 0
}

.skin-red-light .main-header .navbar {
    background-color: #dd4b39
}

.skin-red-light .main-header .navbar .nav>li>a {
    color: #fff
}

.skin-red-light .main-header .navbar .nav .open>a,
.skin-red-light .main-header .navbar .nav .open>a:focus,
.skin-red-light .main-header .navbar .nav .open>a:hover,
.skin-red-light .main-header .navbar .nav>.active>a,
.skin-red-light .main-header .navbar .nav>li>a:active,
.skin-red-light .main-header .navbar .nav>li>a:focus,
.skin-red-light .main-header .navbar .nav>li>a:hover {
    background: rgba(0, 0, 0, .1);
    color: #f6f6f6
}

.skin-red-light .main-header .navbar .sidebar-toggle {
    color: #fff
}

.skin-red-light .main-header .navbar .sidebar-toggle:hover {
    color: #f6f6f6;
    background: rgba(0, 0, 0, .1)
}

.skin-red-light .main-header .navbar .sidebar-toggle {
    color: #fff
}

.skin-red-light .main-header .navbar .sidebar-toggle:hover {
    background-color: #d73925
}

@media (max-width:767px) {
    .skin-red-light .main-header .navbar .dropdown-menu li.divider {
        background-color: rgba(255, 255, 255, .1)
    }
    .skin-red-light .main-header .navbar .dropdown-menu li a {
        color: #fff
    }
    .skin-red-light .main-header .navbar .dropdown-menu li a:hover {
        background: #d73925
    }
}

.skin-red-light .main-header .logo {
    background-color: #dd4b39;
    color: #fff;
    border-bottom: 0 solid transparent
}

.skin-red-light .main-header .logo:hover {
    background-color: #dc4735
}

.skin-red-light .main-header li.user-header {
    background-color: #dd4b39
}

.skin-red-light .content-header {
    background: 0 0
}

.skin-red-light .left-side,
.skin-red-light .main-sidebar,
.skin-red-light .wrapper {
    background-color: #f9fafc
}

.skin-red-light .main-sidebar {
    border-right: 1px solid #d2d6de
}

.skin-red-light .user-panel>.info,
.skin-red-light .user-panel>.info>a {
    color: #444
}

.skin-red-light .sidebar-menu>li {
    -webkit-transition: border-left-color .3s ease;
    -o-transition: border-left-color .3s ease;
    transition: border-left-color .3s ease
}

.skin-red-light .sidebar-menu>li.header {
    color: #848484;
    background: #f9fafc
}

.skin-red-light .sidebar-menu>li>a {
    border-left: 3px solid transparent;
    font-weight: 600
}

.skin-red-light .sidebar-menu>li.active>a,
.skin-red-light .sidebar-menu>li:hover>a {
    color: #000;
    background: #f4f4f5
}

.skin-red-light .sidebar-menu>li.active {
    border-left-color: #dd4b39
}

.skin-red-light .sidebar-menu>li.active>a {
    font-weight: 600
}

.skin-red-light .sidebar-menu>li>.treeview-menu {
    background: #f4f4f5
}

.skin-red-light .sidebar a {
    color: #444
}

.skin-red-light .sidebar a:hover {
    text-decoration: none
}

.skin-red-light .sidebar-menu .treeview-menu>li>a {
    color: #777
}

.skin-red-light .sidebar-menu .treeview-menu>li.active>a,
.skin-red-light .sidebar-menu .treeview-menu>li>a:hover {
    color: #000
}

.skin-red-light .sidebar-menu .treeview-menu>li.active>a {
    font-weight: 600
}

.skin-red-light .sidebar-form {
    border-radius: 3px;
    border: 1px solid #d2d6de;
    margin: 10px 10px
}

.skin-red-light .sidebar-form .btn,
.skin-red-light .sidebar-form input[type=text] {
    box-shadow: none;
    background-color: #fff;
    border: 1px solid transparent;
    height: 35px
}

.skin-red-light .sidebar-form input[type=text] {
    color: #666;
    border-top-left-radius: 2px;
    border-top-right-radius: 0;
    border-bottom-right-radius: 0;
    border-bottom-left-radius: 2px
}

.skin-red-light .sidebar-form input[type=text]:focus,
.skin-red-light .sidebar-form input[type=text]:focus+.input-group-btn .btn {
    background-color: #fff;
    color: #666
}

.skin-red-light .sidebar-form input[type=text]:focus+.input-group-btn .btn {
    border-left-color: #fff
}

.skin-red-light .sidebar-form .btn {
    color: #999;
    border-top-left-radius: 0;
    border-top-right-radius: 2px;
    border-bottom-right-radius: 2px;
    border-bottom-left-radius: 0
}

@media (min-width:768px) {
    .skin-red-light.sidebar-mini.sidebar-collapse .sidebar-menu>li>.treeview-menu {
        border-left: 1px solid #d2d6de
    }
}

.skin-yellow .main-header .navbar {
    background-color: #f39c12
}

.skin-yellow .main-header .navbar .nav>li>a {
    color: #fff
}

.skin-yellow .main-header .navbar .nav .open>a,
.skin-yellow .main-header .navbar .nav .open>a:focus,
.skin-yellow .main-header .navbar .nav .open>a:hover,
.skin-yellow .main-header .navbar .nav>.active>a,
.skin-yellow .main-header .navbar .nav>li>a:active,
.skin-yellow .main-header .navbar .nav>li>a:focus,
.skin-yellow .main-header .navbar .nav>li>a:hover {
    background: rgba(0, 0, 0, .1);
    color: #f6f6f6
}

.skin-yellow .main-header .navbar .sidebar-toggle {
    color: #fff
}

.skin-yellow .main-header .navbar .sidebar-toggle:hover {
    color: #f6f6f6;
    background: rgba(0, 0, 0, .1)
}

.skin-yellow .main-header .navbar .sidebar-toggle {
    color: #fff
}

.skin-yellow .main-header .navbar .sidebar-toggle:hover {
    background-color: #e08e0b
}

@media (max-width:767px) {
    .skin-yellow .main-header .navbar .dropdown-menu li.divider {
        background-color: rgba(255, 255, 255, .1)
    }
    .skin-yellow .main-header .navbar .dropdown-menu li a {
        color: #fff
    }
    .skin-yellow .main-header .navbar .dropdown-menu li a:hover {
        background: #e08e0b
    }
}

.skin-yellow .main-header .logo {
    background-color: #e08e0b;
    color: #fff;
    border-bottom: 0 solid transparent
}

.skin-yellow .main-header .logo:hover {
    background-color: #db8b0b
}

.skin-yellow .main-header li.user-header {
    background-color: #f39c12
}

.skin-yellow .content-header {
    background: 0 0
}

.skin-yellow .left-side,
.skin-yellow .main-sidebar,
.skin-yellow .wrapper {
    background-color: #222d32
}

.skin-yellow .user-panel>.info,
.skin-yellow .user-panel>.info>a {
    color: #fff
}

.skin-yellow .sidebar-menu>li.header {
    color: #4b646f;
    background: #1a2226
}

.skin-yellow .sidebar-menu>li>a {
    border-left: 3px solid transparent
}

.skin-yellow .sidebar-menu>li.active>a,
.skin-yellow .sidebar-menu>li.menu-open>a,
.skin-yellow .sidebar-menu>li:hover>a {
    color: #fff;
    background: #1e282c
}

.skin-yellow .sidebar-menu>li.active>a {
    border-left-color: #f39c12
}

.skin-yellow .sidebar-menu>li>.treeview-menu {
    margin: 0 1px;
    background: #2c3b41
}

.skin-yellow .sidebar a {
    color: #b8c7ce
}

.skin-yellow .sidebar a:hover {
    text-decoration: none
}

.skin-yellow .sidebar-menu .treeview-menu>li>a {
    color: #8aa4af
}

.skin-yellow .sidebar-menu .treeview-menu>li.active>a,
.skin-yellow .sidebar-menu .treeview-menu>li>a:hover {
    color: #fff
}

.skin-yellow .sidebar-form {
    border-radius: 3px;
    border: 1px solid #374850;
    margin: 10px 10px
}

.skin-yellow .sidebar-form .btn,
.skin-yellow .sidebar-form input[type=text] {
    box-shadow: none;
    background-color: #374850;
    border: 1px solid transparent;
    height: 35px
}

.skin-yellow .sidebar-form input[type=text] {
    color: #666;
    border-top-left-radius: 2px;
    border-top-right-radius: 0;
    border-bottom-right-radius: 0;
    border-bottom-left-radius: 2px
}

.skin-yellow .sidebar-form input[type=text]:focus,
.skin-yellow .sidebar-form input[type=text]:focus+.input-group-btn .btn {
    background-color: #fff;
    color: #666
}

.skin-yellow .sidebar-form input[type=text]:focus+.input-group-btn .btn {
    border-left-color: #fff
}

.skin-yellow .sidebar-form .btn {
    color: #999;
    border-top-left-radius: 0;
    border-top-right-radius: 2px;
    border-bottom-right-radius: 2px;
    border-bottom-left-radius: 0
}

.skin-yellow-light .main-header .navbar {
    background-color: #f39c12
}

.skin-yellow-light .main-header .navbar .nav>li>a {
    color: #fff
}

.skin-yellow-light .main-header .navbar .nav .open>a,
.skin-yellow-light .main-header .navbar .nav .open>a:focus,
.skin-yellow-light .main-header .navbar .nav .open>a:hover,
.skin-yellow-light .main-header .navbar .nav>.active>a,
.skin-yellow-light .main-header .navbar .nav>li>a:active,
.skin-yellow-light .main-header .navbar .nav>li>a:focus,
.skin-yellow-light .main-header .navbar .nav>li>a:hover {
    background: rgba(0, 0, 0, .1);
    color: #f6f6f6
}

.skin-yellow-light .main-header .navbar .sidebar-toggle {
    color: #fff
}

.skin-yellow-light .main-header .navbar .sidebar-toggle:hover {
    color: #f6f6f6;
    background: rgba(0, 0, 0, .1)
}

.skin-yellow-light .main-header .navbar .sidebar-toggle {
    color: #fff
}

.skin-yellow-light .main-header .navbar .sidebar-toggle:hover {
    background-color: #e08e0b
}

@media (max-width:767px) {
    .skin-yellow-light .main-header .navbar .dropdown-menu li.divider {
        background-color: rgba(255, 255, 255, .1)
    }
    .skin-yellow-light .main-header .navbar .dropdown-menu li a {
        color: #fff
    }
    .skin-yellow-light .main-header .navbar .dropdown-menu li a:hover {
        background: #e08e0b
    }
}

.skin-yellow-light .main-header .logo {
    background-color: #f39c12;
    color: #fff;
    border-bottom: 0 solid transparent
}

.skin-yellow-light .main-header .logo:hover {
    background-color: #f39a0d
}

.skin-yellow-light .main-header li.user-header {
    background-color: #f39c12
}

.skin-yellow-light .content-header {
    background: 0 0
}

.skin-yellow-light .left-side,
.skin-yellow-light .main-sidebar,
.skin-yellow-light .wrapper {
    background-color: #f9fafc
}

.skin-yellow-light .main-sidebar {
    border-right: 1px solid #d2d6de
}

.skin-yellow-light .user-panel>.info,
.skin-yellow-light .user-panel>.info>a {
    color: #444
}

.skin-yellow-light .sidebar-menu>li {
    -webkit-transition: border-left-color .3s ease;
    -o-transition: border-left-color .3s ease;
    transition: border-left-color .3s ease
}

.skin-yellow-light .sidebar-menu>li.header {
    color: #848484;
    background: #f9fafc
}

.skin-yellow-light .sidebar-menu>li>a {
    border-left: 3px solid transparent;
    font-weight: 600
}

.skin-yellow-light .sidebar-menu>li.active>a,
.skin-yellow-light .sidebar-menu>li:hover>a {
    color: #000;
    background: #f4f4f5
}

.skin-yellow-light .sidebar-menu>li.active {
    border-left-color: #f39c12
}

.skin-yellow-light .sidebar-menu>li.active>a {
    font-weight: 600
}

.skin-yellow-light .sidebar-menu>li>.treeview-menu {
    background: #f4f4f5
}

.skin-yellow-light .sidebar a {
    color: #444
}

.skin-yellow-light .sidebar a:hover {
    text-decoration: none
}

.skin-yellow-light .sidebar-menu .treeview-menu>li>a {
    color: #777
}

.skin-yellow-light .sidebar-menu .treeview-menu>li.active>a,
.skin-yellow-light .sidebar-menu .treeview-menu>li>a:hover {
    color: #000
}

.skin-yellow-light .sidebar-menu .treeview-menu>li.active>a {
    font-weight: 600
}

.skin-yellow-light .sidebar-form {
    border-radius: 3px;
    border: 1px solid #d2d6de;
    margin: 10px 10px
}

.skin-yellow-light .sidebar-form .btn,
.skin-yellow-light .sidebar-form input[type=text] {
    box-shadow: none;
    background-color: #fff;
    border: 1px solid transparent;
    height: 35px
}

.skin-yellow-light .sidebar-form input[type=text] {
    color: #666;
    border-top-left-radius: 2px;
    border-top-right-radius: 0;
    border-bottom-right-radius: 0;
    border-bottom-left-radius: 2px
}

.skin-yellow-light .sidebar-form input[type=text]:focus,
.skin-yellow-light .sidebar-form input[type=text]:focus+.input-group-btn .btn {
    background-color: #fff;
    color: #666
}

.skin-yellow-light .sidebar-form input[type=text]:focus+.input-group-btn .btn {
    border-left-color: #fff
}

.skin-yellow-light .sidebar-form .btn {
    color: #999;
    border-top-left-radius: 0;
    border-top-right-radius: 2px;
    border-bottom-right-radius: 2px;
    border-bottom-left-radius: 0
}

@media (min-width:768px) {
    .skin-yellow-light.sidebar-mini.sidebar-collapse .sidebar-menu>li>.treeview-menu {
        border-left: 1px solid #d2d6de
    }
}

.skin-purple .main-header .navbar {
    background-color: #605ca8
}

.skin-purple .main-header .navbar .nav>li>a {
    color: #fff
}

.skin-purple .main-header .navbar .nav .open>a,
.skin-purple .main-header .navbar .nav .open>a:focus,
.skin-purple .main-header .navbar .nav .open>a:hover,
.skin-purple .main-header .navbar .nav>.active>a,
.skin-purple .main-header .navbar .nav>li>a:active,
.skin-purple .main-header .navbar .nav>li>a:focus,
.skin-purple .main-header .navbar .nav>li>a:hover {
    background: rgba(0, 0, 0, .1);
    color: #f6f6f6
}

.skin-purple .main-header .navbar .sidebar-toggle {
    color: #fff
}

.skin-purple .main-header .navbar .sidebar-toggle:hover {
    color: #f6f6f6;
    background: rgba(0, 0, 0, .1)
}

.skin-purple .main-header .navbar .sidebar-toggle {
    color: #fff
}

.skin-purple .main-header .navbar .sidebar-toggle:hover {
    background-color: #555299
}

@media (max-width:767px) {
    .skin-purple .main-header .navbar .dropdown-menu li.divider {
        background-color: rgba(255, 255, 255, .1)
    }
    .skin-purple .main-header .navbar .dropdown-menu li a {
        color: #fff
    }
    .skin-purple .main-header .navbar .dropdown-menu li a:hover {
        background: #555299
    }
}

.skin-purple .main-header .logo {
    background-color: #555299;
    color: #fff;
    border-bottom: 0 solid transparent
}

.skin-purple .main-header .logo:hover {
    background-color: #545096
}

.skin-purple .main-header li.user-header {
    background-color: #605ca8
}

.skin-purple .content-header {
    background: 0 0
}

.skin-purple .left-side,
.skin-purple .main-sidebar,
.skin-purple .wrapper {
    background-color: #222d32
}

.skin-purple .user-panel>.info,
.skin-purple .user-panel>.info>a {
    color: #fff
}

.skin-purple .sidebar-menu>li.header {
    color: #4b646f;
    background: #1a2226
}

.skin-purple .sidebar-menu>li>a {
    border-left: 3px solid transparent
}

.skin-purple .sidebar-menu>li.active>a,
.skin-purple .sidebar-menu>li.menu-open>a,
.skin-purple .sidebar-menu>li:hover>a {
    color: #fff;
    background: #1e282c
}

.skin-purple .sidebar-menu>li.active>a {
    border-left-color: #605ca8
}

.skin-purple .sidebar-menu>li>.treeview-menu {
    margin: 0 1px;
    background: #2c3b41
}

.skin-purple .sidebar a {
    color: #b8c7ce
}

.skin-purple .sidebar a:hover {
    text-decoration: none
}

.skin-purple .sidebar-menu .treeview-menu>li>a {
    color: #8aa4af
}

.skin-purple .sidebar-menu .treeview-menu>li.active>a,
.skin-purple .sidebar-menu .treeview-menu>li>a:hover {
    color: #fff
}

.skin-purple .sidebar-form {
    border-radius: 3px;
    border: 1px solid #374850;
    margin: 10px 10px
}

.skin-purple .sidebar-form .btn,
.skin-purple .sidebar-form input[type=text] {
    box-shadow: none;
    background-color: #374850;
    border: 1px solid transparent;
    height: 35px
}

.skin-purple .sidebar-form input[type=text] {
    color: #666;
    border-top-left-radius: 2px;
    border-top-right-radius: 0;
    border-bottom-right-radius: 0;
    border-bottom-left-radius: 2px
}

.skin-purple .sidebar-form input[type=text]:focus,
.skin-purple .sidebar-form input[type=text]:focus+.input-group-btn .btn {
    background-color: #fff;
    color: #666
}

.skin-purple .sidebar-form input[type=text]:focus+.input-group-btn .btn {
    border-left-color: #fff
}

.skin-purple .sidebar-form .btn {
    color: #999;
    border-top-left-radius: 0;
    border-top-right-radius: 2px;
    border-bottom-right-radius: 2px;
    border-bottom-left-radius: 0
}

.skin-purple-light .main-header .navbar {
    background-color: #605ca8
}

.skin-purple-light .main-header .navbar .nav>li>a {
    color: #fff
}

.skin-purple-light .main-header .navbar .nav .open>a,
.skin-purple-light .main-header .navbar .nav .open>a:focus,
.skin-purple-light .main-header .navbar .nav .open>a:hover,
.skin-purple-light .main-header .navbar .nav>.active>a,
.skin-purple-light .main-header .navbar .nav>li>a:active,
.skin-purple-light .main-header .navbar .nav>li>a:focus,
.skin-purple-light .main-header .navbar .nav>li>a:hover {
    background: rgba(0, 0, 0, .1);
    color: #f6f6f6
}

.skin-purple-light .main-header .navbar .sidebar-toggle {
    color: #fff
}

.skin-purple-light .main-header .navbar .sidebar-toggle:hover {
    color: #f6f6f6;
    background: rgba(0, 0, 0, .1)
}

.skin-purple-light .main-header .navbar .sidebar-toggle {
    color: #fff
}

.skin-purple-light .main-header .navbar .sidebar-toggle:hover {
    background-color: #555299
}

@media (max-width:767px) {
    .skin-purple-light .main-header .navbar .dropdown-menu li.divider {
        background-color: rgba(255, 255, 255, .1)
    }
    .skin-purple-light .main-header .navbar .dropdown-menu li a {
        color: #fff
    }
    .skin-purple-light .main-header .navbar .dropdown-menu li a:hover {
        background: #555299
    }
}

.skin-purple-light .main-header .logo {
    background-color: #605ca8;
    color: #fff;
    border-bottom: 0 solid transparent
}

.skin-purple-light .main-header .logo:hover {
    background-color: #5d59a6
}

.skin-purple-light .main-header li.user-header {
    background-color: #605ca8
}

.skin-purple-light .content-header {
    background: 0 0
}

.skin-purple-light .left-side,
.skin-purple-light .main-sidebar,
.skin-purple-light .wrapper {
    background-color: #f9fafc
}

.skin-purple-light .main-sidebar {
    border-right: 1px solid #d2d6de
}

.skin-purple-light .user-panel>.info,
.skin-purple-light .user-panel>.info>a {
    color: #444
}

.skin-purple-light .sidebar-menu>li {
    -webkit-transition: border-left-color .3s ease;
    -o-transition: border-left-color .3s ease;
    transition: border-left-color .3s ease
}

.skin-purple-light .sidebar-menu>li.header {
    color: #848484;
    background: #f9fafc
}

.skin-purple-light .sidebar-menu>li>a {
    border-left: 3px solid transparent;
    font-weight: 600
}

.skin-purple-light .sidebar-menu>li.active>a,
.skin-purple-light .sidebar-menu>li:hover>a {
    color: #000;
    background: #f4f4f5
}

.skin-purple-light .sidebar-menu>li.active {
    border-left-color: #605ca8
}

.skin-purple-light .sidebar-menu>li.active>a {
    font-weight: 600
}

.skin-purple-light .sidebar-menu>li>.treeview-menu {
    background: #f4f4f5
}

.skin-purple-light .sidebar a {
    color: #444
}

.skin-purple-light .sidebar a:hover {
    text-decoration: none
}

.skin-purple-light .sidebar-menu .treeview-menu>li>a {
    color: #777
}

.skin-purple-light .sidebar-menu .treeview-menu>li.active>a,
.skin-purple-light .sidebar-menu .treeview-menu>li>a:hover {
    color: #000
}

.skin-purple-light .sidebar-menu .treeview-menu>li.active>a {
    font-weight: 600
}

.skin-purple-light .sidebar-form {
    border-radius: 3px;
    border: 1px solid #d2d6de;
    margin: 10px 10px
}

.skin-purple-light .sidebar-form .btn,
.skin-purple-light .sidebar-form input[type=text] {
    box-shadow: none;
    background-color: #fff;
    border: 1px solid transparent;
    height: 35px
}

.skin-purple-light .sidebar-form input[type=text] {
    color: #666;
    border-top-left-radius: 2px;
    border-top-right-radius: 0;
    border-bottom-right-radius: 0;
    border-bottom-left-radius: 2px
}

.skin-purple-light .sidebar-form input[type=text]:focus,
.skin-purple-light .sidebar-form input[type=text]:focus+.input-group-btn .btn {
    background-color: #fff;
    color: #666
}

.skin-purple-light .sidebar-form input[type=text]:focus+.input-group-btn .btn {
    border-left-color: #fff
}

.skin-purple-light .sidebar-form .btn {
    color: #999;
    border-top-left-radius: 0;
    border-top-right-radius: 2px;
    border-bottom-right-radius: 2px;
    border-bottom-left-radius: 0
}

@media (min-width:768px) {
    .skin-purple-light.sidebar-mini.sidebar-collapse .sidebar-menu>li>.treeview-menu {
        border-left: 1px solid #d2d6de
    }
}

.daterangepicker {
    position: absolute;
    color: inherit;
    background-color: #fff;
    border-radius: 4px;
    border: 1px solid #ddd;
    width: 278px;
    max-width: none;
    padding: 0;
    margin-top: 7px;
    top: 100px;
    left: 20px;
    z-index: 3001;
    display: none;
    font-family: arial;
    font-size: 15px;
    line-height: 1em
}

.daterangepicker:after,
.daterangepicker:before {
    position: absolute;
    display: inline-block;
    border-bottom-color: rgba(0, 0, 0, .2);
    content: ''
}

.daterangepicker:before {
    top: -7px;
    border-right: 7px solid transparent;
    border-left: 7px solid transparent;
    border-bottom: 7px solid #ccc
}

.daterangepicker:after {
    top: -6px;
    border-right: 6px solid transparent;
    border-bottom: 6px solid #fff;
    border-left: 6px solid transparent
}

.daterangepicker.opensleft:before {
    right: 9px
}

.daterangepicker.opensleft:after {
    right: 10px
}

.daterangepicker.openscenter:before {
    left: 0;
    right: 0;
    width: 0;
    margin-left: auto;
    margin-right: auto
}

.daterangepicker.openscenter:after {
    left: 0;
    right: 0;
    width: 0;
    margin-left: auto;
    margin-right: auto
}

.daterangepicker.opensright:before {
    left: 9px
}

.daterangepicker.opensright:after {
    left: 10px
}

.daterangepicker.drop-up {
    margin-top: -7px
}

.daterangepicker.drop-up:before {
    top: initial;
    bottom: -7px;
    border-bottom: initial;
    border-top: 7px solid #ccc
}

.daterangepicker.drop-up:after {
    top: initial;
    bottom: -6px;
    border-bottom: initial;
    border-top: 6px solid #fff
}

.daterangepicker.single .daterangepicker .ranges,
.daterangepicker.single .drp-calendar {
    float: none
}

.daterangepicker.single .drp-selected {
    display: none
}

.daterangepicker.show-calendar .drp-calendar {
    display: block
}

.daterangepicker.show-calendar .drp-buttons {
    display: block
}

.daterangepicker.auto-apply .drp-buttons {
    display: none
}

.daterangepicker .drp-calendar {
    display: none;
    max-width: 270px
}

.daterangepicker .drp-calendar.left {
    padding: 8px 0 8px 8px
}

.daterangepicker .drp-calendar.right {
    padding: 8px
}

.daterangepicker .drp-calendar.single .calendar-table {
    border: none
}

.daterangepicker .calendar-table .next span,
.daterangepicker .calendar-table .prev span {
    color: #fff;
    border: solid #000;
    border-width: 0 2px 2px 0;
    border-radius: 0;
    display: inline-block;
    padding: 3px
}

.daterangepicker .calendar-table .next span {
    transform: rotate(-45deg);
    -webkit-transform: rotate(-45deg)
}

.daterangepicker .calendar-table .prev span {
    transform: rotate(135deg);
    -webkit-transform: rotate(135deg)
}

.daterangepicker .calendar-table td,
.daterangepicker .calendar-table th {
    white-space: nowrap;
    text-align: center;
    vertical-align: middle;
    min-width: 32px;
    width: 32px;
    height: 24px;
    line-height: 24px;
    font-size: 12px;
    border-radius: 4px;
    border: 1px solid transparent;
    white-space: nowrap;
    cursor: pointer
}

.daterangepicker .calendar-table {
    border: 1px solid #fff;
    border-radius: 4px;
    background-color: #fff
}

.daterangepicker .calendar-table table {
    width: 100%;
    margin: 0;
    border-spacing: 0;
    border-collapse: collapse
}

.daterangepicker td.available:hover,
.daterangepicker th.available:hover {
    background-color: #eee;
    border-color: transparent;
    color: inherit
}

.daterangepicker td.week,
.daterangepicker th.week {
    font-size: 80%;
    color: #ccc
}

.daterangepicker td.off,
.daterangepicker td.off.end-date,
.daterangepicker td.off.in-range,
.daterangepicker td.off.start-date {
    background-color: #fff;
    border-color: transparent;
    color: #999
}

.daterangepicker td.in-range {
    background-color: #ebf4f8;
    border-color: transparent;
    color: #000;
    border-radius: 0
}

.daterangepicker td.start-date {
    border-radius: 4px 0 0 4px
}

.daterangepicker td.end-date {
    border-radius: 0 4px 4px 0
}

.daterangepicker td.start-date.end-date {
    border-radius: 4px
}

.daterangepicker td.active,
.daterangepicker td.active:hover {
    background-color: #357ebd;
    border-color: transparent;
    color: #fff
}

.daterangepicker th.month {
    width: auto
}

.daterangepicker option.disabled,
.daterangepicker td.disabled {
    color: #999;
    cursor: not-allowed;
    text-decoration: line-through
}

.daterangepicker select.monthselect,
.daterangepicker select.yearselect {
    font-size: 12px;
    padding: 1px;
    height: auto;
    margin: 0;
    cursor: default
}

.daterangepicker select.monthselect {
    margin-right: 2%;
    width: 56%
}

.daterangepicker select.yearselect {
    width: 40%
}

.daterangepicker select.ampmselect,
.daterangepicker select.hourselect,
.daterangepicker select.minuteselect,
.daterangepicker select.secondselect {
    width: 50px;
    margin: 0 auto;
    background: #eee;
    border: 1px solid #eee;
    padding: 2px;
    outline: 0;
    font-size: 12px
}

.daterangepicker .calendar-time {
    text-align: center;
    margin: 4px auto 0 auto;
    line-height: 30px;
    position: relative
}

.daterangepicker .calendar-time select.disabled {
    color: #ccc;
    cursor: not-allowed
}

.daterangepicker .drp-buttons {
    clear: both;
    text-align: right;
    padding: 8px;
    border-top: 1px solid #ddd;
    display: none;
    line-height: 12px;
    vertical-align: middle
}

.daterangepicker .drp-selected {
    display: inline-block;
    font-size: 12px;
    padding-right: 8px
}

.daterangepicker .drp-buttons .btn {
    margin-left: 8px;
    font-size: 12px;
    font-weight: 700;
    padding: 4px 8px
}

.daterangepicker.show-ranges.single.rtl .drp-calendar.left {
    border-right: 1px solid #ddd
}

.daterangepicker.show-ranges.single.ltr .drp-calendar.left {
    border-left: 1px solid #ddd
}

.daterangepicker.show-ranges.rtl .drp-calendar.right {
    border-right: 1px solid #ddd
}

.daterangepicker.show-ranges.ltr .drp-calendar.left {
    border-left: 1px solid #ddd
}

.daterangepicker .ranges {
    float: none;
    text-align: left;
    margin: 0
}

.daterangepicker.show-calendar .ranges {
    margin-top: 8px
}

.daterangepicker .ranges ul {
    list-style: none;
    margin: 0 auto;
    padding: 0;
    width: 100%
}

.daterangepicker .ranges li {
    font-size: 12px;
    padding: 8px 12px;
    cursor: pointer
}

.daterangepicker .ranges li:hover {
    background-color: #eee
}

.daterangepicker .ranges li.active {
    background-color: #08c;
    color: #fff
}

@media (min-width:564px) {
    .daterangepicker {
        width: auto
    }
    .daterangepicker .ranges ul {
        width: 140px
    }
    .daterangepicker.single .ranges ul {
        width: 100%
    }
    .daterangepicker.single .drp-calendar.left {
        clear: none
    }
    .daterangepicker.single .drp-calendar,
    .daterangepicker.single .ranges {
        float: left
    }
    .daterangepicker {
        direction: ltr;
        text-align: left
    }
    .daterangepicker .drp-calendar.left {
        clear: left;
        margin-right: 0
    }
    .daterangepicker .drp-calendar.left .calendar-table {
        border-right: none;
        border-top-right-radius: 0;
        border-bottom-right-radius: 0
    }
    .daterangepicker .drp-calendar.right {
        margin-left: 0
    }
    .daterangepicker .drp-calendar.right .calendar-table {
        border-left: none;
        border-top-left-radius: 0;
        border-bottom-left-radius: 0
    }
    .daterangepicker .drp-calendar.left .calendar-table {
        padding-right: 8px
    }
    .daterangepicker .drp-calendar,
    .daterangepicker .ranges {
        float: left
    }
}

@media (min-width:730px) {
    .daterangepicker .ranges {
        width: auto
    }
    .daterangepicker .ranges {
        float: left
    }
    .daterangepicker.rtl .ranges {
        float: right
    }
    .daterangepicker .drp-calendar.left {
        clear: none !important
    }
}

.tour-backdrop {
    position: absolute;
    z-index: 1100;
    background-color: #000;
    opacity: .8
}

.popover[class*=tour-] {
    z-index: 1102
}

.popover[class*=tour-] .popover-navigation {
    padding: 9px 14px;
    overflow: hidden
}

.popover[class*=tour-] .popover-navigation [data-role=end] {
    float: right
}

.popover[class*=tour-] .popover-navigation [data-role=end],
.popover[class*=tour-] .popover-navigation [data-role=next],
.popover[class*=tour-] .popover-navigation [data-role=prev] {
    cursor: pointer
}

.popover[class*=tour-] .popover-navigation [data-role=end].disabled,
.popover[class*=tour-] .popover-navigation [data-role=next].disabled,
.popover[class*=tour-] .popover-navigation [data-role=prev].disabled {
    cursor: default
}

.popover[class*=tour-].orphan {
    position: fixed;
    margin-top: 0
}

.popover[class*=tour-].orphan .arrow {
    display: none
}

#calculator input {
    border: none
}

#calculator button {
    height: 35px;
    width: 35px;
    margin: 2px 1px;
    border: none !important;
    padding: 6px 7px
}

:focus {
    outline: 0 !important
}

#allClear {
    box-shadow: inset 1px 1px 50px #900;
    border: none
}

#clear {
    box-shadow: inset 1px 1px 50px #c60;
    border: none
}

#equals {
    box-shadow: inset 1px 1px 50px #063;
    border: none
}

#blank {
    visibility: hidden
}

#calculator .screen {
    width: 161px;
    height: 36px;
    border-radius: 3px;
    padding: 10px;
    margin: 2px 24px;
    font-size: 15px;
    font-weight: 700;
    background: #8e9eab
}

#calculator small {
    color: #fff;
    font-weight: 700
}

.navbar-custom-menu .popover-content,
.pos-header .popover-content {
    padding: 4px 0
}

/*!
 * Datetimepicker for Bootstrap 3
 * version : 4.17.47
 * https://github.com/Eonasdan/bootstrap-datetimepicker/
 */

.bootstrap-datetimepicker-widget {
    list-style: none
}

.bootstrap-datetimepicker-widget.dropdown-menu {
    display: block;
    margin: 2px 0;
    padding: 4px;
    width: 19em
}

@media (min-width:768px) {
    .bootstrap-datetimepicker-widget.dropdown-menu.timepicker-sbs {
        width: 38em
    }
}

@media (min-width:992px) {
    .bootstrap-datetimepicker-widget.dropdown-menu.timepicker-sbs {
        width: 38em
    }
}

@media (min-width:1200px) {
    .bootstrap-datetimepicker-widget.dropdown-menu.timepicker-sbs {
        width: 38em
    }
}

.bootstrap-datetimepicker-widget.dropdown-menu:after,
.bootstrap-datetimepicker-widget.dropdown-menu:before {
    content: '';
    display: inline-block;
    position: absolute
}

.bootstrap-datetimepicker-widget.dropdown-menu.bottom:before {
    border-left: 7px solid transparent;
    border-right: 7px solid transparent;
    border-bottom: 7px solid #ccc;
    border-bottom-color: rgba(0, 0, 0, .2);
    top: -7px;
    left: 7px
}

.bootstrap-datetimepicker-widget.dropdown-menu.bottom:after {
    border-left: 6px solid transparent;
    border-right: 6px solid transparent;
    border-bottom: 6px solid #fff;
    top: -6px;
    left: 8px
}

.bootstrap-datetimepicker-widget.dropdown-menu.top:before {
    border-left: 7px solid transparent;
    border-right: 7px solid transparent;
    border-top: 7px solid #ccc;
    border-top-color: rgba(0, 0, 0, .2);
    bottom: -7px;
    left: 6px
}

.bootstrap-datetimepicker-widget.dropdown-menu.top:after {
    border-left: 6px solid transparent;
    border-right: 6px solid transparent;
    border-top: 6px solid #fff;
    bottom: -6px;
    left: 7px
}

.bootstrap-datetimepicker-widget.dropdown-menu.pull-right:before {
    left: auto;
    right: 6px
}

.bootstrap-datetimepicker-widget.dropdown-menu.pull-right:after {
    left: auto;
    right: 7px
}

.bootstrap-datetimepicker-widget .list-unstyled {
    margin: 0
}

.bootstrap-datetimepicker-widget a[data-action] {
    padding: 6px 0
}

.bootstrap-datetimepicker-widget a[data-action]:active {
    box-shadow: none
}

.bootstrap-datetimepicker-widget .timepicker-hour,
.bootstrap-datetimepicker-widget .timepicker-minute,
.bootstrap-datetimepicker-widget .timepicker-second {
    width: 54px;
    font-weight: 700;
    font-size: 1.2em;
    margin: 0
}

.bootstrap-datetimepicker-widget button[data-action] {
    padding: 6px
}

.bootstrap-datetimepicker-widget .btn[data-action=incrementHours]::after {
    position: absolute;
    width: 1px;
    height: 1px;
    margin: -1px;
    padding: 0;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    border: 0;
    content: "Increment Hours"
}

.bootstrap-datetimepicker-widget .btn[data-action=incrementMinutes]::after {
    position: absolute;
    width: 1px;
    height: 1px;
    margin: -1px;
    padding: 0;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    border: 0;
    content: "Increment Minutes"
}

.bootstrap-datetimepicker-widget .btn[data-action=decrementHours]::after {
    position: absolute;
    width: 1px;
    height: 1px;
    margin: -1px;
    padding: 0;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    border: 0;
    content: "Decrement Hours"
}

.bootstrap-datetimepicker-widget .btn[data-action=decrementMinutes]::after {
    position: absolute;
    width: 1px;
    height: 1px;
    margin: -1px;
    padding: 0;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    border: 0;
    content: "Decrement Minutes"
}

.bootstrap-datetimepicker-widget .btn[data-action=showHours]::after {
    position: absolute;
    width: 1px;
    height: 1px;
    margin: -1px;
    padding: 0;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    border: 0;
    content: "Show Hours"
}

.bootstrap-datetimepicker-widget .btn[data-action=showMinutes]::after {
    position: absolute;
    width: 1px;
    height: 1px;
    margin: -1px;
    padding: 0;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    border: 0;
    content: "Show Minutes"
}

.bootstrap-datetimepicker-widget .btn[data-action=togglePeriod]::after {
    position: absolute;
    width: 1px;
    height: 1px;
    margin: -1px;
    padding: 0;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    border: 0;
    content: "Toggle AM/PM"
}

.bootstrap-datetimepicker-widget .btn[data-action=clear]::after {
    position: absolute;
    width: 1px;
    height: 1px;
    margin: -1px;
    padding: 0;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    border: 0;
    content: "Clear the picker"
}

.bootstrap-datetimepicker-widget .btn[data-action=today]::after {
    position: absolute;
    width: 1px;
    height: 1px;
    margin: -1px;
    padding: 0;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    border: 0;
    content: "Set the date to today"
}

.bootstrap-datetimepicker-widget .picker-switch {
    text-align: center
}

.bootstrap-datetimepicker-widget .picker-switch::after {
    position: absolute;
    width: 1px;
    height: 1px;
    margin: -1px;
    padding: 0;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    border: 0;
    content: "Toggle Date and Time Screens"
}

.bootstrap-datetimepicker-widget .picker-switch td {
    padding: 0;
    margin: 0;
    height: auto;
    width: auto;
    line-height: inherit
}

.bootstrap-datetimepicker-widget .picker-switch td span {
    line-height: 2.5;
    height: 2.5em;
    width: 100%
}

.bootstrap-datetimepicker-widget table {
    width: 100%;
    margin: 0
}

.bootstrap-datetimepicker-widget table td,
.bootstrap-datetimepicker-widget table th {
    text-align: center;
    border-radius: 4px
}

.bootstrap-datetimepicker-widget table th {
    height: 20px;
    line-height: 20px;
    width: 20px
}

.bootstrap-datetimepicker-widget table th.picker-switch {
    width: 145px
}

.bootstrap-datetimepicker-widget table th.disabled,
.bootstrap-datetimepicker-widget table th.disabled:hover {
    background: 0 0;
    color: #777;
    cursor: not-allowed
}

.bootstrap-datetimepicker-widget table th.prev::after {
    position: absolute;
    width: 1px;
    height: 1px;
    margin: -1px;
    padding: 0;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    border: 0;
    content: "Previous Month"
}

.bootstrap-datetimepicker-widget table th.next::after {
    position: absolute;
    width: 1px;
    height: 1px;
    margin: -1px;
    padding: 0;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    border: 0;
    content: "Next Month"
}

.bootstrap-datetimepicker-widget table thead tr:first-child th {
    cursor: pointer
}

.bootstrap-datetimepicker-widget table thead tr:first-child th:hover {
    background: #eee
}

.bootstrap-datetimepicker-widget table td {
    height: 54px;
    line-height: 54px;
    width: 54px
}

.bootstrap-datetimepicker-widget table td.cw {
    font-size: .8em;
    height: 20px;
    line-height: 20px;
    color: #777
}

.bootstrap-datetimepicker-widget table td.day {
    height: 20px;
    line-height: 20px;
    width: 20px
}

.bootstrap-datetimepicker-widget table td.day:hover,
.bootstrap-datetimepicker-widget table td.hour:hover,
.bootstrap-datetimepicker-widget table td.minute:hover,
.bootstrap-datetimepicker-widget table td.second:hover {
    background: #eee;
    cursor: pointer
}

.bootstrap-datetimepicker-widget table td.new,
.bootstrap-datetimepicker-widget table td.old {
    color: #777
}

.bootstrap-datetimepicker-widget table td.today {
    position: relative
}

.bootstrap-datetimepicker-widget table td.today:before {
    content: '';
    display: inline-block;
    border: solid transparent;
    border-width: 0 0 7px 7px;
    border-bottom-color: #337ab7;
    border-top-color: rgba(0, 0, 0, .2);
    position: absolute;
    bottom: 4px;
    right: 4px
}

.bootstrap-datetimepicker-widget table td.active,
.bootstrap-datetimepicker-widget table td.active:hover {
    background-color: #337ab7;
    color: #fff;
    text-shadow: 0 -1px 0 rgba(0, 0, 0, .25)
}

.bootstrap-datetimepicker-widget table td.active.today:before {
    border-bottom-color: #fff
}

.bootstrap-datetimepicker-widget table td.disabled,
.bootstrap-datetimepicker-widget table td.disabled:hover {
    background: 0 0;
    color: #777;
    cursor: not-allowed
}

.bootstrap-datetimepicker-widget table td span {
    display: inline-block;
    width: 54px;
    height: 54px;
    line-height: 54px;
    margin: 2px 1.5px;
    cursor: pointer;
    border-radius: 4px
}

.bootstrap-datetimepicker-widget table td span:hover {
    background: #eee
}

.bootstrap-datetimepicker-widget table td span.active {
    background-color: #337ab7;
    color: #fff;
    text-shadow: 0 -1px 0 rgba(0, 0, 0, .25)
}

.bootstrap-datetimepicker-widget table td span.old {
    color: #777
}

.bootstrap-datetimepicker-widget table td span.disabled,
.bootstrap-datetimepicker-widget table td span.disabled:hover {
    background: 0 0;
    color: #777;
    cursor: not-allowed
}

.bootstrap-datetimepicker-widget.usetwentyfour td.hour {
    height: 27px;
    line-height: 27px
}

.bootstrap-datetimepicker-widget.wider {
    width: 21em
}

.bootstrap-datetimepicker-widget .datepicker-decades .decade {
    line-height: 1.8em !important
}

.input-group.date .input-group-addon {
    cursor: pointer
}

.sr-only {
    position: absolute;
    width: 1px;
    height: 1px;
    margin: -1px;
    padding: 0;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    border: 0
}

@-webkit-keyframes passing-through {
    0% {
        opacity: 0;
        -webkit-transform: translateY(40px);
        -moz-transform: translateY(40px);
        -ms-transform: translateY(40px);
        -o-transform: translateY(40px);
        transform: translateY(40px)
    }
    30%,
    70% {
        opacity: 1;
        -webkit-transform: translateY(0);
        -moz-transform: translateY(0);
        -ms-transform: translateY(0);
        -o-transform: translateY(0);
        transform: translateY(0)
    }
    100% {
        opacity: 0;
        -webkit-transform: translateY(-40px);
        -moz-transform: translateY(-40px);
        -ms-transform: translateY(-40px);
        -o-transform: translateY(-40px);
        transform: translateY(-40px)
    }
}

@-moz-keyframes passing-through {
    0% {
        opacity: 0;
        -webkit-transform: translateY(40px);
        -moz-transform: translateY(40px);
        -ms-transform: translateY(40px);
        -o-transform: translateY(40px);
        transform: translateY(40px)
    }
    30%,
    70% {
        opacity: 1;
        -webkit-transform: translateY(0);
        -moz-transform: translateY(0);
        -ms-transform: translateY(0);
        -o-transform: translateY(0);
        transform: translateY(0)
    }
    100% {
        opacity: 0;
        -webkit-transform: translateY(-40px);
        -moz-transform: translateY(-40px);
        -ms-transform: translateY(-40px);
        -o-transform: translateY(-40px);
        transform: translateY(-40px)
    }
}

@keyframes passing-through {
    0% {
        opacity: 0;
        -webkit-transform: translateY(40px);
        -moz-transform: translateY(40px);
        -ms-transform: translateY(40px);
        -o-transform: translateY(40px);
        transform: translateY(40px)
    }
    30%,
    70% {
        opacity: 1;
        -webkit-transform: translateY(0);
        -moz-transform: translateY(0);
        -ms-transform: translateY(0);
        -o-transform: translateY(0);
        transform: translateY(0)
    }
    100% {
        opacity: 0;
        -webkit-transform: translateY(-40px);
        -moz-transform: translateY(-40px);
        -ms-transform: translateY(-40px);
        -o-transform: translateY(-40px);
        transform: translateY(-40px)
    }
}

@-webkit-keyframes slide-in {
    0% {
        opacity: 0;
        -webkit-transform: translateY(40px);
        -moz-transform: translateY(40px);
        -ms-transform: translateY(40px);
        -o-transform: translateY(40px);
        transform: translateY(40px)
    }
    30% {
        opacity: 1;
        -webkit-transform: translateY(0);
        -moz-transform: translateY(0);
        -ms-transform: translateY(0);
        -o-transform: translateY(0);
        transform: translateY(0)
    }
}

@-moz-keyframes slide-in {
    0% {
        opacity: 0;
        -webkit-transform: translateY(40px);
        -moz-transform: translateY(40px);
        -ms-transform: translateY(40px);
        -o-transform: translateY(40px);
        transform: translateY(40px)
    }
    30% {
        opacity: 1;
        -webkit-transform: translateY(0);
        -moz-transform: translateY(0);
        -ms-transform: translateY(0);
        -o-transform: translateY(0);
        transform: translateY(0)
    }
}

@keyframes slide-in {
    0% {
        opacity: 0;
        -webkit-transform: translateY(40px);
        -moz-transform: translateY(40px);
        -ms-transform: translateY(40px);
        -o-transform: translateY(40px);
        transform: translateY(40px)
    }
    30% {
        opacity: 1;
        -webkit-transform: translateY(0);
        -moz-transform: translateY(0);
        -ms-transform: translateY(0);
        -o-transform: translateY(0);
        transform: translateY(0)
    }
}

@-webkit-keyframes pulse {
    0% {
        -webkit-transform: scale(1);
        -moz-transform: scale(1);
        -ms-transform: scale(1);
        -o-transform: scale(1);
        transform: scale(1)
    }
    10% {
        -webkit-transform: scale(1.1);
        -moz-transform: scale(1.1);
        -ms-transform: scale(1.1);
        -o-transform: scale(1.1);
        transform: scale(1.1)
    }
    20% {
        -webkit-transform: scale(1);
        -moz-transform: scale(1);
        -ms-transform: scale(1);
        -o-transform: scale(1);
        transform: scale(1)
    }
}

@-moz-keyframes pulse {
    0% {
        -webkit-transform: scale(1);
        -moz-transform: scale(1);
        -ms-transform: scale(1);
        -o-transform: scale(1);
        transform: scale(1)
    }
    10% {
        -webkit-transform: scale(1.1);
        -moz-transform: scale(1.1);
        -ms-transform: scale(1.1);
        -o-transform: scale(1.1);
        transform: scale(1.1)
    }
    20% {
        -webkit-transform: scale(1);
        -moz-transform: scale(1);
        -ms-transform: scale(1);
        -o-transform: scale(1);
        transform: scale(1)
    }
}

@keyframes pulse {
    0% {
        -webkit-transform: scale(1);
        -moz-transform: scale(1);
        -ms-transform: scale(1);
        -o-transform: scale(1);
        transform: scale(1)
    }
    10% {
        -webkit-transform: scale(1.1);
        -moz-transform: scale(1.1);
        -ms-transform: scale(1.1);
        -o-transform: scale(1.1);
        transform: scale(1.1)
    }
    20% {
        -webkit-transform: scale(1);
        -moz-transform: scale(1);
        -ms-transform: scale(1);
        -o-transform: scale(1);
        transform: scale(1)
    }
}

.dropzone,
.dropzone * {
    box-sizing: border-box
}

.dropzone {
    min-height: 150px;
    border: 2px solid rgba(0, 0, 0, .3);
    background: #fff;
    padding: 20px 20px
}

.dropzone.dz-clickable {
    cursor: pointer
}

.dropzone.dz-clickable * {
    cursor: default
}

.dropzone.dz-clickable .dz-message,
.dropzone.dz-clickable .dz-message * {
    cursor: pointer
}

.dropzone.dz-started .dz-message {
    display: none
}

.dropzone.dz-drag-hover {
    border-style: solid
}

.dropzone.dz-drag-hover .dz-message {
    opacity: .5
}

.dropzone .dz-message {
    text-align: center;
    margin: 2em 0
}

.dropzone .dz-preview {
    position: relative;
    display: inline-block;
    vertical-align: top;
    margin: 16px;
    min-height: 100px
}

.dropzone .dz-preview:hover {
    z-index: 1000
}

.dropzone .dz-preview:hover .dz-details {
    opacity: 1
}

.dropzone .dz-preview.dz-file-preview .dz-image {
    border-radius: 20px;
    background: #999;
    background: linear-gradient(to bottom, #eee, #ddd)
}

.dropzone .dz-preview.dz-file-preview .dz-details {
    opacity: 1
}

.dropzone .dz-preview.dz-image-preview {
    background: #fff
}

.dropzone .dz-preview.dz-image-preview .dz-details {
    -webkit-transition: opacity .2s linear;
    -moz-transition: opacity .2s linear;
    -ms-transition: opacity .2s linear;
    -o-transition: opacity .2s linear;
    transition: opacity .2s linear
}

.dropzone .dz-preview .dz-remove {
    font-size: 14px;
    text-align: center;
    display: block;
    cursor: pointer;
    border: none
}

.dropzone .dz-preview .dz-remove:hover {
    text-decoration: underline
}

.dropzone .dz-preview:hover .dz-details {
    opacity: 1
}

.dropzone .dz-preview .dz-details {
    z-index: 20;
    position: absolute;
    top: 0;
    left: 0;
    opacity: 0;
    font-size: 13px;
    min-width: 100%;
    max-width: 100%;
    padding: 2em 1em;
    text-align: center;
    color: rgba(0, 0, 0, .9);
    line-height: 150%
}

.dropzone .dz-preview .dz-details .dz-size {
    margin-bottom: 1em;
    font-size: 16px
}

.dropzone .dz-preview .dz-details .dz-filename {
    white-space: nowrap
}

.dropzone .dz-preview .dz-details .dz-filename:hover span {
    border: 1px solid rgba(200, 200, 200, .8);
    background-color: rgba(255, 255, 255, .8)
}

.dropzone .dz-preview .dz-details .dz-filename:not(:hover) {
    overflow: hidden;
    text-overflow: ellipsis
}

.dropzone .dz-preview .dz-details .dz-filename:not(:hover) span {
    border: 1px solid transparent
}

.dropzone .dz-preview .dz-details .dz-filename span,
.dropzone .dz-preview .dz-details .dz-size span {
    background-color: rgba(255, 255, 255, .4);
    padding: 0 .4em;
    border-radius: 3px
}

.dropzone .dz-preview:hover .dz-image img {
    -webkit-transform: scale(1.05, 1.05);
    -moz-transform: scale(1.05, 1.05);
    -ms-transform: scale(1.05, 1.05);
    -o-transform: scale(1.05, 1.05);
    transform: scale(1.05, 1.05);
    -webkit-filter: blur(8px);
    filter: blur(8px)
}

.dropzone .dz-preview .dz-image {
    border-radius: 20px;
    overflow: hidden;
    width: 120px;
    height: 120px;
    position: relative;
    display: block;
    z-index: 10
}

.dropzone .dz-preview .dz-image img {
    display: block
}

.dropzone .dz-preview.dz-success .dz-success-mark {
    -webkit-animation: passing-through 3s cubic-bezier(.77, 0, .175, 1);
    -moz-animation: passing-through 3s cubic-bezier(.77, 0, .175, 1);
    -ms-animation: passing-through 3s cubic-bezier(0.77, 0, 0.175, 1);
    -o-animation: passing-through 3s cubic-bezier(.77, 0, .175, 1);
    animation: passing-through 3s cubic-bezier(.77, 0, .175, 1)
}

.dropzone .dz-preview.dz-error .dz-error-mark {
    opacity: 1;
    -webkit-animation: slide-in 3s cubic-bezier(.77, 0, .175, 1);
    -moz-animation: slide-in 3s cubic-bezier(.77, 0, .175, 1);
    -ms-animation: slide-in 3s cubic-bezier(0.77, 0, 0.175, 1);
    -o-animation: slide-in 3s cubic-bezier(.77, 0, .175, 1);
    animation: slide-in 3s cubic-bezier(.77, 0, .175, 1)
}

.dropzone .dz-preview .dz-error-mark,
.dropzone .dz-preview .dz-success-mark {
    pointer-events: none;
    opacity: 0;
    z-index: 500;
    position: absolute;
    display: block;
    top: 50%;
    left: 50%;
    margin-left: -27px;
    margin-top: -27px
}

.dropzone .dz-preview .dz-error-mark svg,
.dropzone .dz-preview .dz-success-mark svg {
    display: block;
    width: 54px;
    height: 54px
}

.dropzone .dz-preview.dz-processing .dz-progress {
    opacity: 1;
    -webkit-transition: all .2s linear;
    -moz-transition: all .2s linear;
    -ms-transition: all .2s linear;
    -o-transition: all .2s linear;
    transition: all .2s linear
}

.dropzone .dz-preview.dz-complete .dz-progress {
    opacity: 0;
    -webkit-transition: opacity .4s ease-in;
    -moz-transition: opacity .4s ease-in;
    -ms-transition: opacity .4s ease-in;
    -o-transition: opacity .4s ease-in;
    transition: opacity .4s ease-in
}

.dropzone .dz-preview:not(.dz-processing) .dz-progress {
    -webkit-animation: pulse 6s ease infinite;
    -moz-animation: pulse 6s ease infinite;
    -ms-animation: pulse 6s ease infinite;
    -o-animation: pulse 6s ease infinite;
    animation: pulse 6s ease infinite
}

.dropzone .dz-preview .dz-progress {
    opacity: 1;
    z-index: 1000;
    pointer-events: none;
    position: absolute;
    height: 16px;
    left: 50%;
    top: 50%;
    margin-top: -8px;
    width: 80px;
    margin-left: -40px;
    background: rgba(255, 255, 255, .9);
    -webkit-transform: scale(1);
    border-radius: 8px;
    overflow: hidden
}

.dropzone .dz-preview .dz-progress .dz-upload {
    background: #333;
    background: linear-gradient(to bottom, #666, #444);
    position: absolute;
    top: 0;
    left: 0;
    bottom: 0;
    width: 0;
    -webkit-transition: width .3s ease-in-out;
    -moz-transition: width .3s ease-in-out;
    -ms-transition: width .3s ease-in-out;
    -o-transition: width .3s ease-in-out;
    transition: width .3s ease-in-out
}

.dropzone .dz-preview.dz-error .dz-error-message {
    display: block
}

.dropzone .dz-preview.dz-error:hover .dz-error-message {
    opacity: 1;
    pointer-events: auto
}

.dropzone .dz-preview .dz-error-message {
    pointer-events: none;
    z-index: 1000;
    position: absolute;
    display: block;
    display: none;
    opacity: 0;
    -webkit-transition: opacity .3s ease;
    -moz-transition: opacity .3s ease;
    -ms-transition: opacity .3s ease;
    -o-transition: opacity .3s ease;
    transition: opacity .3s ease;
    border-radius: 8px;
    font-size: 13px;
    top: 130px;
    left: -10px;
    width: 140px;
    background: #be2626;
    background: linear-gradient(to bottom, #be2626, #a92222);
    padding: .5em 1.2em;
    color: #fff
}

.dropzone .dz-preview .dz-error-message:after {
    content: '';
    position: absolute;
    top: -6px;
    left: 64px;
    width: 0;
    height: 0;
    border-left: 6px solid transparent;
    border-right: 6px solid transparent;
    border-bottom: 6px solid #be2626
}

.tabcontrol,
.wizard {
    display: block;
    width: 100%;
    overflow: hidden
}

.tabcontrol a,
.wizard a {
    outline: 0
}

.tabcontrol ul,
.wizard ul {
    list-style: none !important;
    padding: 0;
    margin: 0
}

.tabcontrol ul>li,
.wizard ul>li {
    display: block;
    padding: 0
}

.tabcontrol>.steps .current-info,
.wizard>.steps .current-info {
    position: absolute;
    left: -999em
}

.tabcontrol>.content>.title,
.wizard>.content>.title {
    position: absolute;
    left: -999em
}

.wizard>.steps {
    position: relative;
    display: block;
    width: 100%
}

.wizard.vertical>.steps {
    display: inline;
    float: left;
    width: 30%
}

.wizard>.steps .number {
    font-size: 1.429em
}

.wizard>.steps>ul>li {
    width: 25%
}

.wizard>.actions>ul>li,
.wizard>.steps>ul>li {
    float: left
}

.wizard.vertical>.steps>ul>li {
    float: none;
    width: 100%
}

.wizard>.steps a,
.wizard>.steps a:active,
.wizard>.steps a:hover {
    display: block;
    width: auto;
    margin: 0 .5em .5em;
    padding: 1em 1em;
    text-decoration: none;
    -webkit-border-radius: 5px;
    -moz-border-radius: 5px;
    border-radius: 5px
}

.wizard>.steps .disabled a,
.wizard>.steps .disabled a:active,
.wizard>.steps .disabled a:hover {
    background: #eee;
    color: #aaa;
    cursor: default
}

.wizard>.steps .current a,
.wizard>.steps .current a:active,
.wizard>.steps .current a:hover {
    background: #2184be;
    color: #fff;
    cursor: default
}

.wizard>.steps .done a,
.wizard>.steps .done a:active,
.wizard>.steps .done a:hover {
    background: #9dc8e2;
    color: #fff
}

.wizard>.steps .error a,
.wizard>.steps .error a:active,
.wizard>.steps .error a:hover {
    background: #d9534f;
    color: #fff
}

.wizard>.content {
    background: #eee;
    display: block;
    margin: .5em;
    min-height: 35em;
    overflow: hidden;
    position: relative;
    width: auto;
    -webkit-border-radius: 5px;
    -moz-border-radius: 5px;
    border-radius: 5px
}

.wizard.vertical>.content {
    display: inline;
    float: left;
    margin: 0 2.5% .5em 2.5%;
    width: 65%
}

.wizard>.content>.body {
    float: left;
    position: relative;
    width: 95%;
    height: 95%;
    padding: 2.5%
}

.wizard>.content>.body ul {
    list-style: disc !important
}

.wizard>.content>.body ul>li {
    display: list-item
}

.wizard>.content>.body>iframe {
    border: 0 none;
    width: 100%;
    height: 100%
}

.wizard>.content>.body input {
    display: block;
    border: 1px solid #ccc
}

.wizard>.content>.body input[type=checkbox] {
    display: inline-block
}

.wizard>.content>.body input.error {
    border: 1px solid #fbc2c4;
    color: #8a1f11
}

.wizard>.content>.body label {
    display: inline-block;
    margin-bottom: .5em
}

.wizard>.content>.body label.error {
    color: #8a1f11;
    display: inline-block;
    margin-left: 1.5em
}

.wizard>.actions {
    position: relative;
    display: block;
    text-align: right;
    width: 100%
}

.wizard.vertical>.actions {
    display: inline;
    float: right;
    margin: 0 2.5%;
    width: 95%
}

.wizard>.actions>ul {
    display: inline-block;
    text-align: right
}

.wizard>.actions>ul>li {
    margin: 0 .5em
}

.wizard.vertical>.actions>ul>li {
    margin: 0 0 0 1em
}

.wizard>.actions a,
.wizard>.actions a:active,
.wizard>.actions a:hover {
    background: #2184be;
    color: #fff;
    display: block;
    padding: .5em 1em;
    text-decoration: none;
    -webkit-border-radius: 5px;
    -moz-border-radius: 5px;
    border-radius: 5px
}

.wizard>.actions .disabled a,
.wizard>.actions .disabled a:active,
.wizard>.actions .disabled a:hover {
    background: #eee;
    color: #aaa
}

.tabcontrol>.steps {
    position: relative;
    display: block;
    width: 100%
}

.tabcontrol>.steps>ul {
    position: relative;
    margin: 6px 0 0 0;
    top: 1px;
    z-index: 1
}

.tabcontrol>.steps>ul>li {
    float: left;
    margin: 5px 2px 0 0;
    padding: 1px;
    -webkit-border-top-left-radius: 5px;
    -webkit-border-top-right-radius: 5px;
    -moz-border-radius-topleft: 5px;
    -moz-border-radius-topright: 5px;
    border-top-left-radius: 5px;
    border-top-right-radius: 5px
}

.tabcontrol>.steps>ul>li:hover {
    background: #edecec;
    border: 1px solid #bbb;
    padding: 0
}

.tabcontrol>.steps>ul>li.current {
    background: #fff;
    border: 1px solid #bbb;
    border-bottom: 0 none;
    padding: 0 0 1px 0;
    margin-top: 0
}

.tabcontrol>.steps>ul>li>a {
    color: #5f5f5f;
    display: inline-block;
    border: 0 none;
    margin: 0;
    padding: 10px 30px;
    text-decoration: none
}

.tabcontrol>.steps>ul>li>a:hover {
    text-decoration: none
}

.tabcontrol>.steps>ul>li.current>a {
    padding: 15px 30px 10px 30px
}

.tabcontrol>.content {
    position: relative;
    display: inline-block;
    width: 100%;
    height: 35em;
    overflow: hidden;
    border-top: 1px solid #bbb;
    padding-top: 20px
}

.tabcontrol>.content>.body {
    float: left;
    position: absolute;
    width: 95%;
    height: 95%;
    padding: 2.5%
}

.tabcontrol>.content>.body ul {
    list-style: disc !important
}

.tabcontrol>.content>.body ul>li {
    display: list-item
}

body {
    color: #525f7f
}

.h1,
.h2,
.h3,
.h4,
.h5,
.h6,
h1,
h2,
h3,
h4,
h5,
h6 {
    color: #32325d
}

.main-header {
    max-height: unset
}

.main-header .logo {
    height: 62px;
    line-height: 62px
}

.main-header .navbar {
    height: 62px;
    border-bottom: 1px solid rgba(255, 255, 255, .1) !important
}

.main-header .navbar .nav>li>a {
    transition: all .3s
}

.main-header .navbar .nav>li>a:hover {
    border-radius: 5px
}

.main-header .navbar-custom-menu,
.main-header .navbar-right,
.main-header .sidebar-toggle {
    height: 62px;
    display: flex;
    align-items: center
}

.main-sidebar {
    box-shadow: 0 0 2rem 0 rgba(136, 152, 170, .15) !important;
    padding-top: 62px
}

.main-sidebar .logo {
    width: 100%;
    height: 62px;
    line-height: 62px;
    text-align: center;
    font-size: 20px;
    font-weight: 300;
    display: none
}

.main-sidebar hr {
    border-top: 1px solid rgba(0, 0, 0, .1);
    margin: 20px 24px
}

.control-sidebar {
    padding-top: 62px
}

.sidebar-menu li.header {
    background: 0 0 !important;
    padding: 6px 24px;
    text-transform: uppercase;
    letter-spacing: .04em;
    font-weight: 700;
    margin-bottom: 8px
}

.sidebar-menu li.active>a {
    font-weight: 800 !important
}

.sidebar-menu>li>a {
    font-weight: 400 !important;
    padding: 10px 16px 10px 24px
}

.sidebar-menu>li>a>.fa,
.sidebar-menu>li>a>.glyphicon,
.sidebar-menu>li>a>.ion,
.treeview-menu>li>a>.fa,
.treeview-menu>li>a>.glyphicon,
.treeview-menu>li>a>.ion {
    width: 25px;
    font-size: 16px
}

.sidebar-collapse .sidebar-menu>li>a {
    padding: 12px 5px 12px 15px
}

.navbar-nav>.messages-menu>.dropdown-menu>li .menu>li>a>h4 span {
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
    display: block;
    max-width: 125px;
    font-size: 13px
}

.navbar-nav>.messages-menu>.dropdown-menu>li .menu>li>a {
    padding: 16px 12px
}

.navbar-nav>.messages-menu>.dropdown-menu>li .menu>li>a>p {
    word-wrap: break-word;
    overflow: hidden;
    margin-top: 6px;
    white-space: normal
}

.navbar-nav>.messages-menu>.dropdown-menu,
.navbar-nav>.notifications-menu>.dropdown-menu,
.navbar-nav>.tasks-menu>.dropdown-menu {
    width: 325px !important
}

.navbar-nav>.messages-menu>.dropdown-menu>li .menu,
.navbar-nav>.notifications-menu>.dropdown-menu>li .menu,
.navbar-nav>.tasks-menu>.dropdown-menu>li .menu {
    max-height: 230px
}

.navbar-nav>.dropdown>.dropdown-menu {
    margin-top: 0;
    border-width: 0;
    border-radius: 5px !important;
    box-shadow: 0 50px 100px rgba(50, 50, 93, .1), 0 15px 35px rgba(50, 50, 93, .15), 0 5px 15px rgba(0, 0, 0, .1)
}

.navbar-nav>.dropdown>.dropdown-menu .header {
    padding: 16px !important;
    color: #8898aa !important;
    font-weight: 600
}

.navbar-nav>.dropdown>.dropdown-menu>li.footer {
    padding: 6px;
    border-top: 1px solid #f4f4f4
}

.navbar-nav>.dropdown>.dropdown-menu>li.footer>a,
.navbar-nav>.dropdown>.dropdown-menu>li.footer>a:hover {
    border: 0 !important;
    color: #5e72e4 !important;
    font-size: 14px;
    font-weight: 600
}

.navbar-nav>.notifications-menu>.dropdown-menu>li .menu>li>a {
    color: #525f7f;
    font-size: 13px;
    border-bottom: 0
}

.navbar-nav>.notifications-menu>.dropdown-menu>li .menu>li>a:hover {
    background: #f4f4f5
}

.notifications-menu .notif-info {
    font-size: 13px;
    margin-bottom: 3px
}

.notifications-menu .time {
    display: block;
    color: #7d8c95;
    font-size: 11px;
    margin-top: 4px;
    margin-left: 52px
}

.notifications-menu .unread {
    background: #f4f4f4
}

.notifications-menu .unread .notif-info {
    font-weight: 600;
    color: #000
}

.dropdown-menu .unread {
    background: #f4f4f5
}

.user-box {
    display: flex;
    padding: .5rem 1rem
}

.user-box .image img {
    width: 3.75rem;
    height: 3.75rem
}

.user-box .u-text {
    padding: 0 10px
}

.user-box .u-text h4 {
    margin-bottom: 5px;
    margin-top: 4px;
    font-size: 14px;
    font-weight: 400;
    line-height: 1
}

.user-box .u-text .text-muted {
    font-size: 12px;
    margin-bottom: 5px
}

.user-box .u-text .btn {
    font-size: 11px
}

.dropdown-user {
    padding-bottom: 8px !important
}

.dropdown-divider {
    height: 0;
    margin: .5rem 0;
    overflow: hidden;
    border-top: 1px solid #e9ecef
}

.dropdown-item {
    display: block;
    width: 100%;
    padding: .25rem 1.5rem;
    clear: both;
    font-weight: 400;
    color: #212529 !important;
    text-align: inherit;
    white-space: nowrap;
    background-color: transparent;
    border: 0
}

.notif-icon {
    float: left;
    width: 40px !important;
    height: 40px;
    border-radius: 50%;
    text-align: center;
    line-height: 40px !important;
    margin-right: 12px
}

.content-wrapper {
    background-color: #f8f9fe
}

.content-wrapper .content,
.content-wrapper .content-header {
    padding: 15px
}

.content-wrapper .content-header {
    padding-bottom: 0
}

.main-footer {
    background: #f8f9fe;
    border-top: 0;
    padding: 0 15px 15px
}

.bg-light-blue,
.label-primary,
.modal-primary .modal-body,
.progress-bar {
    background-color: #1572e8 !important
}

.alert-danger,
.alert-error,
.bg-red,
.callout.callout-danger,
.label-danger,
.modal-danger .modal-body,
.progress-bar-danger,
.progress-bar-red {
    background-color: #f5365c !important
}

.alert-info,
.bg-aqua,
.callout.callout-info,
.label-info,
.modal-info .modal-body,
.progress-bar-aqua,
.progress-bar-info {
    background-color: #11cdef !important
}

.alert-warning,
.bg-yellow,
.callout.callout-warning,
.label-warning,
.modal-warning .modal-body,
.progress-bar-warning,
.progress-bar-yellow {
    background-color: #ffad46 !important
}

.alert-success,
.bg-green,
.callout.callout-success,
.label-success,
.modal-success .modal-body,
.progress-bar-green,
.progress-bar-success {
    background-color: #2dce89 !important
}

.text-light-blue,
.text-primary {
    color: #1572e8 !important
}

.text-danger,
.text-red {
    color: #f5365c !important
}

.text-aqua,
.text-info {
    color: #11cdef !important
}

.text-warning,
.text-yellow {
    color: #ffad46 !important
}

.text-green,
.text-success {
    color: #2dce89 !important
}

.text-white {
    color: #fff !important
}

.box,
.info-box {
    margin-bottom: 30px;
    box-shadow: 2px 2px 4px rgba(136, 152, 170, .15) !important;
    border-radius: 5px
}

.box .box-body,
.box .box-footer,
.box .box-header {
    padding: 20px 24px
}

.row-custom {
    display: flex;
    flex-wrap: wrap
}

.row-custom .col-custom {
    display: flex
}

.info-box {
    overflow: hidden
}

.info-box .progress {
    background: rgba(0, 0, 0, .08);
    margin: 5px -16px 5px -16px;
    height: 2px
}

.info-box-text {
    color: #8898aa;
    font-weight: 600;
    font-size: 13px;
    margin-bottom: 2px
}

.info-box-number {
    font-size: 20px;
    word-wrap: break-word
}

.info-box-content {
    padding: 12px 16px
}

.info-box-icon {
    background: rgba(0, 0, 0, .08);
    margin-bottom: -99999px;
    padding-bottom: 99999px
}

.info-box-new-style {
    padding: 12px !important;
    padding-right: 0 !important;
    transform: perspective(1500px) rotateY(0);
    transition: transform 1s ease 0s;
    box-shadow: 2px 2px 4px rgba(0, 0, 0, .3)
}

.info-box-new-style:hover {
    transform: perspective(3000px) rotateY(15deg)
}

.info-box-new-style .info-box-icon {
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 64px;
    margin-bottom: 0;
    padding-bottom: 0;
    height: 64px;
    width: 64px;
    line-height: 64px;
    font-size: unset;
    box-shadow: 0 0 2rem 0 rgba(136, 152, 170, .15) !important
}

.info-box-new-style .info-box-icon i {
    font-size: 32px
}

.info-box-new-style .info-box-icon i.fa {
    font-size: 26px
}

.info-box-new-style .info-box-content {
    padding: 6px 0 6px 12px;
    margin-left: 64px
}

.btn .btn-label {
    display: inline-block
}

.btn .btn-label i {
    font-size: 16px;
    vertical-align: middle;
    margin-right: 2px;
    margin-left: -2px;
    line-height: 0;
    margin-top: -2.5px
}

.btn .btn-label.just-icon i {
    margin-left: 0 !important;
    margin-right: 0 !important
}

.btn-icon {
    font-size: .9375rem;
    height: 2.5125rem;
    line-height: normal;
    min-width: 2.5125rem;
    overflow: hidden;
    padding: 0;
    position: relative;
    width: 2.5125rem
}

.btn-round {
    border-radius: 50px !important
}

.btn-primary {
    background: #1572e8;
    border-color: #1367d1
}

.btn-primary:hover {
    background: #1367d1;
    border-color: #115bb9
}

.btn-success {
    background: #2dce89;
    border-color: #28b97b
}

.btn-success:hover {
    background: #28b97b;
    border-color: #24a46d
}

.btn-info {
    background: #11cdef;
    border-color: #0fb9d8
}

.btn-info:hover {
    background: #0fb9d8;
    border-color: #0da5c0
}

.btn-danger {
    background: #f5365c;
    border-color: #f41e48
}

.btn-danger:hover {
    background: #f41e48;
    border-color: #ec0c38
}

.btn-warning {
    background: #ffad46;
    border-color: #ffa22d
}

.btn-warning:hover {
    background: #ffa22d;
    border-color: #ff9613
}

.btn-border-primary {
    background: 0 0 !important;
    border-color: #1572e8;
    color: #1572e8
}

.btn-border-primary:hover {
    background: 0 0 !important;
    border-color: #115bb9;
    color: #115bb9
}

.btn-border-success {
    background: 0 0 !important;
    border-color: #2dce89;
    color: #2dce89
}

.btn-border-success:hover {
    background: 0 0 !important;
    border-color: #24a46d;
    color: #24a46d
}

.btn-border-info {
    background: 0 0 !important;
    border-color: #11cdef;
    color: #11cdef
}

.btn-border-info:hover {
    background: 0 0 !important;
    border-color: #0da5c0;
    color: #0da5c0
}

.btn-border-danger {
    background: 0 0 !important;
    border-color: #f5365c;
    color: #f5365c
}

.btn-border-danger:hover {
    background: 0 0 !important;
    border-color: #ec0c38;
    color: #ec0c38
}

.btn-border-warning {
    background: 0 0 !important;
    border-color: #ffad46;
    color: #ffad46
}

.btn-border-warning:hover {
    background: 0 0 !important;
    border-color: #ff9613;
    color: #ff9613
}

.box-table thead th {
    background-color: #f6f9fc;
    color: #8898aa;
    border-color: #e9ecef
}

.box-table td,
.box-table th {
    padding: .8rem 1.5rem !important
}

.skin-black .main-sidebar,
.skin-blue .main-sidebar,
.skin-green .main-sidebar,
.skin-purple .main-sidebar,
.skin-red .main-sidebar,
.skin-yellow .main-sidebar {
    background: #21243d !important;
    border-right: 0px !important
}

.skin-black .sidebar-menu>li.active>a,
.skin-black .sidebar-menu>li.menu-open>a,
.skin-black .sidebar-menu>li:hover>a,
.skin-blue .sidebar-menu>li.active>a,
.skin-blue .sidebar-menu>li.menu-open>a,
.skin-blue .sidebar-menu>li:hover>a,
.skin-green .sidebar-menu>li.active>a,
.skin-green .sidebar-menu>li.menu-open>a,
.skin-green .sidebar-menu>li:hover>a,
.skin-purple .sidebar-menu>li.active>a,
.skin-purple .sidebar-menu>li.menu-open>a,
.skin-purple .sidebar-menu>li:hover>a,
.skin-red .sidebar-menu>li.active>a,
.skin-red .sidebar-menu>li.menu-open>a,
.skin-red .sidebar-menu>li:hover>a,
.skin-yellow .sidebar-menu>li.active>a,
.skin-yellow .sidebar-menu>li.menu-open>a,
.skin-yellow .sidebar-menu>li:hover>a {
    background: #1d1f33 !important
}

.skin-black .sidebar-menu>li>.treeview-menu,
.skin-blue .sidebar-menu>li>.treeview-menu,
.skin-green .sidebar-menu>li>.treeview-menu,
.skin-purple .sidebar-menu>li>.treeview-menu,
.skin-red .sidebar-menu>li>.treeview-menu,
.skin-yellow .sidebar-menu>li>.treeview-menu {
    background: #1d1f33 !important
}

.skin-black-light .main-sidebar,
.skin-blue-light .main-sidebar,
.skin-green-light .main-sidebar,
.skin-purple-light .main-sidebar,
.skin-red-light .main-sidebar,
.skin-yellow-light .main-sidebar {
    background: #fff !important;
    border-right: 0px !important
}

.skin-black-light .sidebar-menu>li.active>a,
.skin-black-light .sidebar-menu>li.menu-open>a,
.skin-black-light .sidebar-menu>li:hover>a,
.skin-blue-light .sidebar-menu>li.active>a,
.skin-blue-light .sidebar-menu>li.menu-open>a,
.skin-blue-light .sidebar-menu>li:hover>a,
.skin-green-light .sidebar-menu>li.active>a,
.skin-green-light .sidebar-menu>li.menu-open>a,
.skin-green-light .sidebar-menu>li:hover>a,
.skin-purple-light .sidebar-menu>li.active>a,
.skin-purple-light .sidebar-menu>li.menu-open>a,
.skin-purple-light .sidebar-menu>li:hover>a,
.skin-red-light .sidebar-menu>li.active>a,
.skin-red-light .sidebar-menu>li.menu-open>a,
.skin-red-light .sidebar-menu>li:hover>a,
.skin-yellow-light .sidebar-menu>li.active>a,
.skin-yellow-light .sidebar-menu>li.menu-open>a,
.skin-yellow-light .sidebar-menu>li:hover>a {
    background: #f4f4f5 !important;
    color: rgba(0, 0, 0, .9)
}

.skin-black-light .sidebar-menu>li>.treeview-menu,
.skin-blue-light .sidebar-menu>li>.treeview-menu,
.skin-green-light .sidebar-menu>li>.treeview-menu,
.skin-purple-light .sidebar-menu>li>.treeview-menu,
.skin-red-light .sidebar-menu>li>.treeview-menu,
.skin-yellow-light .sidebar-menu>li>.treeview-menu {
    background: #f4f4f5 !important
}

.skin-black-light .sidebar-menu>li.active>a,
.skin-blue-light .sidebar-menu>li.active>a,
.skin-green-light .sidebar-menu>li.active>a,
.skin-purple-light .sidebar-menu>li.active>a,
.skin-red-light .sidebar-menu>li.active>a,
.skin-yellow-light .sidebar-menu>li.active>a {
    border-color: inherit
}

.skin-blue .main-header .logo,
.skin-blue-light .main-header .logo {
    background: #1572e8
}

.skin-blue .main-header .logo:hover,
.skin-blue-light .main-header .logo:hover {
    background: #1572e8
}

.skin-blue .main-header .navbar,
.skin-blue-light .main-header .navbar {
    background-color: #2b80ec;
    background-image: linear-gradient(to right, #2b80ec, #1d1f33)
}

.skin-blue .main-header li.user-header,
.skin-blue-light .main-header li.user-header {
    background-color: #2b80ec
}

.skin-blue .main-sidebar .logo,
.skin-blue-light .main-sidebar .logo {
    background: #1572e8;
    color: #fff
}

.skin-blue .main-sidebar .logo:hover,
.skin-blue-light .main-sidebar .logo:hover {
    background: #1572e8
}

.skin-blue .content-wrapper .content-header-custom,
.skin-blue-light .content-wrapper .content-header-custom {
    background-color: #2b80ec;
    background-image: linear-gradient(to right, #2b80ec, #1d1f33);
    color: #fff !important;
    padding: 15px 15px 200px
}

.skin-blue .content-wrapper .content-header-custom a,
.skin-blue .content-wrapper .content-header-custom h1,
.skin-blue .content-wrapper .content-header-custom small,
.skin-blue-light .content-wrapper .content-header-custom a,
.skin-blue-light .content-wrapper .content-header-custom h1,
.skin-blue-light .content-wrapper .content-header-custom small {
    color: #fff !important
}

.skin-blue .content-wrapper .content-header-custom .breadcrumb,
.skin-blue-light .content-wrapper .content-header-custom .breadcrumb {
    color: #fff
}

.skin-blue .content-wrapper .content-header-custom .breadcrumb>.active,
.skin-blue-light .content-wrapper .content-header-custom .breadcrumb>.active {
    color: #fff
}

.skin-blue .content-wrapper .content-custom,
.skin-blue-light .content-wrapper .content-custom {
    margin-top: -210px
}

.skin-red .main-header .logo,
.skin-red-light .main-header .logo {
    background: #f5365c
}

.skin-red .main-header .logo:hover,
.skin-red-light .main-header .logo:hover {
    background: #f5365c
}

.skin-red .main-header .navbar,
.skin-red-light .main-header .navbar {
    background-color: #f64e70;
    background-image: linear-gradient(to right, #f64e70, #245b80)
}

.skin-red .main-header li.user-header,
.skin-red-light .main-header li.user-header {
    background-color: #f64e70
}

.skin-red .main-sidebar .logo,
.skin-red-light .main-sidebar .logo {
    background: #f5365c;
    color: #fff
}

.skin-red .main-sidebar .logo:hover,
.skin-red-light .main-sidebar .logo:hover {
    background: #f5365c
}

.skin-red .content-wrapper .content-header-custom,
.skin-red-light .content-wrapper .content-header-custom {
    background-color: #f64e70;
    background-image: linear-gradient(to right, #f64e70, #245b80);
    color: #fff !important;
    padding: 15px 15px 200px
}

.skin-red .content-wrapper .content-header-custom a,
.skin-red .content-wrapper .content-header-custom h1,
.skin-red .content-wrapper .content-header-custom small,
.skin-red-light .content-wrapper .content-header-custom a,
.skin-red-light .content-wrapper .content-header-custom h1,
.skin-red-light .content-wrapper .content-header-custom small {
    color: #fff !important
}

.skin-red .content-wrapper .content-header-custom .breadcrumb,
.skin-red-light .content-wrapper .content-header-custom .breadcrumb {
    color: #fff
}

.skin-red .content-wrapper .content-header-custom .breadcrumb>.active,
.skin-red-light .content-wrapper .content-header-custom .breadcrumb>.active {
    color: #fff
}

.skin-red .content-wrapper .content-custom,
.skin-red-light .content-wrapper .content-custom {
    margin-top: -210px
}

.skin-purple .main-header .logo,
.skin-purple-light .main-header .logo {
    background: #605ca8
}

.skin-purple .main-header .logo:hover,
.skin-purple-light .main-header .logo:hover {
    background: #605ca8
}

.skin-purple .main-header .navbar,
.skin-purple-light .main-header .navbar {
    background-color: #706db1;
    background-image: linear-gradient(to right, #706db1, #245b80)
}

.skin-purple .main-header li.user-header,
.skin-purple-light .main-header li.user-header {
    background-color: #706db1
}

.skin-purple .main-sidebar .logo,
.skin-purple-light .main-sidebar .logo {
    background: #605ca8;
    color: #fff
}

.skin-purple .main-sidebar .logo:hover,
.skin-purple-light .main-sidebar .logo:hover {
    background: #605ca8
}

.skin-purple .content-wrapper .content-header-custom,
.skin-purple-light .content-wrapper .content-header-custom {
    background-color: #706db1;
    background-image: linear-gradient(to right, #706db1, #245b80);
    color: #fff !important;
    padding: 15px 15px 200px
}

.skin-purple .content-wrapper .content-header-custom a,
.skin-purple .content-wrapper .content-header-custom h1,
.skin-purple .content-wrapper .content-header-custom small,
.skin-purple-light .content-wrapper .content-header-custom a,
.skin-purple-light .content-wrapper .content-header-custom h1,
.skin-purple-light .content-wrapper .content-header-custom small {
    color: #fff !important
}

.skin-purple .content-wrapper .content-header-custom .breadcrumb,
.skin-purple-light .content-wrapper .content-header-custom .breadcrumb {
    color: #fff
}

.skin-purple .content-wrapper .content-header-custom .breadcrumb>.active,
.skin-purple-light .content-wrapper .content-header-custom .breadcrumb>.active {
    color: #fff
}

.skin-purple .content-wrapper .content-custom,
.skin-purple-light .content-wrapper .content-custom {
    margin-top: -210px
}

.skin-green .main-header .logo,
.skin-green-light .main-header .logo {
    background: #2dce89
}

.skin-green .main-header .logo:hover,
.skin-green-light .main-header .logo:hover {
    background: #2dce89
}

.skin-green .main-header .navbar,
.skin-green-light .main-header .navbar {
    background-color: #3fd595;
    background-image: linear-gradient(to right, #3fd595, #1b9aaa)
}

.skin-green .main-header li.user-header,
.skin-green-light .main-header li.user-header {
    background-color: #3fd595
}

.skin-green .main-sidebar .logo,
.skin-green-light .main-sidebar .logo {
    background: #2dce89;
    color: #fff
}

.skin-green .main-sidebar .logo:hover,
.skin-green-light .main-sidebar .logo:hover {
    background: #2dce89
}

.skin-green .content-wrapper .content-header-custom,
.skin-green-light .content-wrapper .content-header-custom {
    background-color: #3fd595;
    background-image: linear-gradient(to right, #3fd595, #1b9aaa);
    color: #fff !important;
    padding: 15px 15px 200px
}

.skin-green .content-wrapper .content-header-custom a,
.skin-green .content-wrapper .content-header-custom h1,
.skin-green .content-wrapper .content-header-custom small,
.skin-green-light .content-wrapper .content-header-custom a,
.skin-green-light .content-wrapper .content-header-custom h1,
.skin-green-light .content-wrapper .content-header-custom small {
    color: #fff !important
}

.skin-green .content-wrapper .content-header-custom .breadcrumb,
.skin-green-light .content-wrapper .content-header-custom .breadcrumb {
    color: #fff
}

.skin-green .content-wrapper .content-header-custom .breadcrumb>.active,
.skin-green-light .content-wrapper .content-header-custom .breadcrumb>.active {
    color: #fff
}

.skin-green .content-wrapper .content-custom,
.skin-green-light .content-wrapper .content-custom {
    margin-top: -210px
}

.skin-yellow .main-header .logo,
.skin-yellow-light .main-header .logo {
    background: #ffad46
}

.skin-yellow .main-header .logo:hover,
.skin-yellow-light .main-header .logo:hover {
    background: #ffad46
}

.skin-yellow .main-header .navbar,
.skin-yellow-light .main-header .navbar {
    background-color: #ffb860;
    background-image: linear-gradient(to right, #ffb860, #245b80)
}

.skin-yellow .main-header li.user-header,
.skin-yellow-light .main-header li.user-header {
    background-color: #ffb860
}

.skin-yellow .main-sidebar .logo,
.skin-yellow-light .main-sidebar .logo {
    background: #ffad46;
    color: #fff
}

.skin-yellow .main-sidebar .logo:hover,
.skin-yellow-light .main-sidebar .logo:hover {
    background: #ffad46
}

.skin-yellow .content-wrapper .content-header-custom,
.skin-yellow-light .content-wrapper .content-header-custom {
    background-color: #ffb860;
    background-image: linear-gradient(to right, #ffb860, #245b80);
    color: #fff !important;
    padding: 15px 15px 200px
}

.skin-yellow .content-wrapper .content-header-custom a,
.skin-yellow .content-wrapper .content-header-custom h1,
.skin-yellow .content-wrapper .content-header-custom small,
.skin-yellow-light .content-wrapper .content-header-custom a,
.skin-yellow-light .content-wrapper .content-header-custom h1,
.skin-yellow-light .content-wrapper .content-header-custom small {
    color: #fff !important
}

.skin-yellow .content-wrapper .content-header-custom .breadcrumb,
.skin-yellow-light .content-wrapper .content-header-custom .breadcrumb {
    color: #fff
}

.skin-yellow .content-wrapper .content-header-custom .breadcrumb>.active,
.skin-yellow-light .content-wrapper .content-header-custom .breadcrumb>.active {
    color: #fff
}

.skin-yellow .content-wrapper .content-custom,
.skin-yellow-light .content-wrapper .content-custom {
    margin-top: -210px
}

.skin-black .main-header .logo,
.skin-black-light .main-header .logo {
    background: #313140
}

.skin-black .main-header .logo:hover,
.skin-black-light .main-header .logo:hover {
    background: #313140
}

.skin-black .main-header .navbar,
.skin-black-light .main-header .navbar {
    background-color: #3c3c4e;
    background-image: linear-gradient(to right, #3c3c4e, #245b80)
}

.skin-black .main-header li.user-header,
.skin-black-light .main-header li.user-header {
    background-color: #3c3c4e
}

.skin-black .main-sidebar .logo,
.skin-black-light .main-sidebar .logo {
    background: #313140;
    color: #fff
}

.skin-black .main-sidebar .logo:hover,
.skin-black-light .main-sidebar .logo:hover {
    background: #313140
}

.skin-black .content-wrapper .content-header-custom,
.skin-black-light .content-wrapper .content-header-custom {
    background-color: #3c3c4e;
    background-image: linear-gradient(to right, #3c3c4e, #245b80);
    color: #fff !important;
    padding: 15px 15px 200px
}

.skin-black .content-wrapper .content-header-custom a,
.skin-black .content-wrapper .content-header-custom h1,
.skin-black .content-wrapper .content-header-custom small,
.skin-black-light .content-wrapper .content-header-custom a,
.skin-black-light .content-wrapper .content-header-custom h1,
.skin-black-light .content-wrapper .content-header-custom small {
    color: #fff !important
}

.skin-black .content-wrapper .content-header-custom .breadcrumb,
.skin-black-light .content-wrapper .content-header-custom .breadcrumb {
    color: #fff
}

.skin-black .content-wrapper .content-header-custom .breadcrumb>.active,
.skin-black-light .content-wrapper .content-header-custom .breadcrumb>.active {
    color: #fff
}

.skin-black .content-wrapper .content-custom,
.skin-black-light .content-wrapper .content-custom {
    margin-top: -210px
}

.skin-black .main-header,
.skin-black-light .main-header {
    color: #fff !important
}

.skin-black .main-header .logo,
.skin-black-light .main-header .logo {
    color: #fff;
    border-right: 0px
}

.skin-black .main-header .navbar>.sidebar-toggle,
.skin-black-light .main-header .navbar>.sidebar-toggle {
    color: #fff !important
}

.skin-black .main-header .navbar .nav>li>a,
.skin-black-light .main-header .navbar .nav>li>a {
    color: #fff !important
}

.skin-black-light .main-header .navbar .nav .open>a,
.skin-black-light .main-header .navbar .nav .open>a:focus,
.skin-black-light .main-header .navbar .nav .open>a:hover,
.skin-black-light .main-header .navbar .nav>.active>a,
.skin-black-light .main-header .navbar .nav>li>a:active,
.skin-black-light .main-header .navbar .nav>li>a:focus,
.skin-black-light .main-header .navbar .nav>li>a:hover,
.skin-black-light .main-header .navbar .sidebar-toggle:hover {
    background: #000
}

.skin-black .main-header .navbar>.sidebar-toggle,
.skin-black-light .main-header .navbar>.sidebar-toggle {
    border-right: 0px
}

.skin-black .main-header .navbar .navbar-custom-menu .navbar-nav>li>a,
.skin-black .main-header .navbar .navbar-right>li>a,
.skin-black-light .main-header .navbar .navbar-custom-menu .navbar-nav>li>a,
.skin-black-light .main-header .navbar .navbar-right>li>a {
    border-left: 0
}

@media screen and (max-width:767px) {
    .main-header .logo {
        display: none
    }
    .main-sidebar .logo {
        display: block
    }
}

@media screen and (max-width:576px) {
    .main-header {
        transition: transform .3s ease-in-out, margin .3s ease-in-out
    }
    .main-header .navbar-custom-menu .dropdown-menu {
        width: calc(100% - 30px);
        left: 0 !important;
        margin-left: 15px;
        margin-right: 15px;
        right: 0 !important
    }
    .main-sidebar {
        padding-top: 0
    }
    .navbar-nav>.messages-menu>.dropdown-menu>li .menu,
    .navbar-nav>.notifications-menu>.dropdown-menu>li .menu,
    .navbar-nav>.tasks-menu>.dropdown-menu>li .menu {
        max-height: unset
    }
    .sidebar-open .main-header {
        -webkit-transform: translate(230px, 0);
        -ms-transform: translate(230px, 0);
        -o-transform: translate(230px, 0);
        transform: translate(230px, 0)
    }
}

/*!
 * FullCalendar v3.10.2
 * Docs & License: https://fullcalendar.io/
 * (c) 2019 Adam Shaw
 */

.fc button,
.fc table,
body .fc {
    font-size: 1em
}

.fc .fc-axis,
.fc button,
.fc-day-grid-event .fc-content,
.fc-list-item-marker,
.fc-list-item-time,
.fc-time-grid-event .fc-time,
.fc-time-grid-event.fc-short .fc-content {
    white-space: nowrap
}

.fc-event,
.fc-event:hover,
.fc-state-hover,
.fc.fc-bootstrap3 a,
.ui-widget .fc-event,
a.fc-more {
    text-decoration: none
}

.fc {
    direction: ltr;
    text-align: left
}

.fc-rtl {
    text-align: right
}

.fc th,
.fc-basic-view .fc-day-top .fc-week-number,
.fc-basic-view td.fc-week-number,
.fc-icon,
.fc-toolbar {
    text-align: center
}

.fc-highlight {
    background: #bce8f1;
    opacity: .3
}

.fc-bgevent {
    background: #8fdf82;
    opacity: .3
}

.fc-nonbusiness {
    background: #d7d7d7
}

.fc button {
    -moz-box-sizing: border-box;
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
    margin: 0;
    height: 2.1em;
    padding: 0 .6em;
    cursor: pointer
}

.fc button::-moz-focus-inner {
    margin: 0;
    padding: 0
}

.fc-state-default {
    border: 1px solid;
    background-color: #f5f5f5;
    background-image: -moz-linear-gradient(top, #fff, #e6e6e6);
    background-image: -webkit-gradient(linear, 0 0, 0 100%, from(#fff), to(#e6e6e6));
    background-image: -webkit-linear-gradient(top, #fff, #e6e6e6);
    background-image: -o-linear-gradient(top, #fff, #e6e6e6);
    background-image: linear-gradient(to bottom, #fff, #e6e6e6);
    background-repeat: repeat-x;
    border-color: #e6e6e6 #e6e6e6 #bfbfbf;
    border-color: rgba(0, 0, 0, .1) rgba(0, 0, 0, .1) rgba(0, 0, 0, .25);
    color: #333;
    text-shadow: 0 1px 1px rgba(255, 255, 255, .75);
    box-shadow: inset 0 1px 0 rgba(255, 255, 255, .2), 0 1px 2px rgba(0, 0, 0, .05)
}

.fc-state-default.fc-corner-left {
    border-top-left-radius: 4px;
    border-bottom-left-radius: 4px
}

.fc-state-default.fc-corner-right {
    border-top-right-radius: 4px;
    border-bottom-right-radius: 4px
}

.fc button .fc-icon {
    position: relative;
    top: -.05em;
    margin: 0 .2em;
    vertical-align: middle
}

.fc-state-active,
.fc-state-disabled,
.fc-state-down,
.fc-state-hover {
    color: #333;
    background-color: #e6e6e6
}

.fc-state-hover {
    color: #333;
    background-position: 0 -15px;
    -webkit-transition: background-position .1s linear;
    -moz-transition: background-position .1s linear;
    -o-transition: background-position .1s linear;
    transition: background-position .1s linear
}

.fc-state-active,
.fc-state-down {
    background-color: #ccc;
    background-image: none;
    box-shadow: inset 0 2px 4px rgba(0, 0, 0, .15), 0 1px 2px rgba(0, 0, 0, .05)
}

.fc-state-disabled {
    cursor: default;
    background-image: none;
    opacity: .65;
    box-shadow: none
}

.fc-event.fc-draggable,
.fc-event[href],
.fc-popover .fc-header .fc-close,
a[data-goto] {
    cursor: pointer
}

.fc-button-group {
    display: inline-block
}

.fc .fc-button-group>* {
    float: left;
    margin: 0 0 0 -1px
}

.fc .fc-button-group>:first-child {
    margin-left: 0
}

.fc-popover {
    position: absolute;
    box-shadow: 0 2px 6px rgba(0, 0, 0, .15)
}

.fc-popover .fc-header {
    padding: 2px 4px
}

.fc-popover .fc-header .fc-title {
    margin: 0 2px
}

.fc-ltr .fc-popover .fc-header .fc-title,
.fc-rtl .fc-popover .fc-header .fc-close {
    float: left
}

.fc-ltr .fc-popover .fc-header .fc-close,
.fc-rtl .fc-popover .fc-header .fc-title {
    float: right
}

.fc-divider {
    border-style: solid;
    border-width: 1px
}

hr.fc-divider {
    height: 0;
    margin: 0;
    padding: 0 0 2px;
    border-width: 1px 0
}

.fc-bg table,
.fc-row .fc-bgevent-skeleton table,
.fc-row .fc-highlight-skeleton table {
    height: 100%
}

.fc-clear {
    clear: both
}

.fc-bg,
.fc-bgevent-skeleton,
.fc-helper-skeleton,
.fc-highlight-skeleton {
    position: absolute;
    top: 0;
    left: 0;
    right: 0
}

.fc-bg {
    bottom: 0
}

.fc table {
    width: 100%;
    box-sizing: border-box;
    table-layout: fixed;
    border-collapse: collapse;
    border-spacing: 0
}

.fc td,
.fc th {
    border-style: solid;
    border-width: 1px;
    padding: 0;
    vertical-align: top
}

.fc td.fc-today {
    border-style: double
}

a[data-goto]:hover {
    text-decoration: underline
}

.fc .fc-row {
    border-style: solid;
    border-width: 0
}

.fc-row table {
    border-left: 0 hidden transparent;
    border-right: 0 hidden transparent;
    border-bottom: 0 hidden transparent
}

.fc-row:first-child table {
    border-top: 0 hidden transparent
}

.fc-row {
    position: relative
}

.fc-row .fc-bg {
    z-index: 1
}

.fc-row .fc-bgevent-skeleton,
.fc-row .fc-highlight-skeleton {
    bottom: 0
}

.fc-row .fc-bgevent-skeleton td,
.fc-row .fc-highlight-skeleton td {
    border-color: transparent
}

.fc-row .fc-bgevent-skeleton {
    z-index: 2
}

.fc-row .fc-highlight-skeleton {
    z-index: 3
}

.fc-row .fc-content-skeleton {
    position: relative;
    z-index: 4;
    padding-bottom: 2px
}

.fc-row .fc-helper-skeleton {
    z-index: 5
}

.fc .fc-row .fc-content-skeleton table,
.fc .fc-row .fc-content-skeleton td,
.fc .fc-row .fc-helper-skeleton td {
    background: 0 0;
    border-color: transparent
}

.fc-row .fc-content-skeleton td,
.fc-row .fc-helper-skeleton td {
    border-bottom: 0
}

.fc-row .fc-content-skeleton tbody td,
.fc-row .fc-helper-skeleton tbody td {
    border-top: 0
}

.fc-scroller {
    -webkit-overflow-scrolling: touch
}

.fc-day-grid-event .fc-content,
.fc-icon,
.fc-row.fc-rigid,
.fc-time-grid-event {
    overflow: hidden
}

.fc-scroller>.fc-day-grid,
.fc-scroller>.fc-time-grid {
    position: relative;
    width: 100%
}

.fc-event {
    position: relative;
    display: block;
    font-size: .85em;
    line-height: 1.3;
    border-radius: 3px;
    border: 1px solid #3a87ad
}

.fc-event,
.fc-event-dot {
    background-color: #3a87ad
}

.fc-event,
.fc-event:hover {
    color: #fff
}

.fc-not-allowed,
.fc-not-allowed .fc-event {
    cursor: not-allowed
}

.fc-event .fc-bg {
    z-index: 1;
    background: #fff;
    opacity: .25
}

.fc-event .fc-content {
    position: relative;
    z-index: 2
}

.fc-event .fc-resizer {
    position: absolute;
    z-index: 4;
    display: none
}

.fc-event.fc-allow-mouse-resize .fc-resizer,
.fc-event.fc-selected .fc-resizer {
    display: block
}

.fc-event.fc-selected .fc-resizer:before {
    content: "";
    position: absolute;
    z-index: 9999;
    top: 50%;
    left: 50%;
    width: 40px;
    height: 40px;
    margin-left: -20px;
    margin-top: -20px
}

.fc-event.fc-selected {
    z-index: 9999 !important;
    box-shadow: 0 2px 5px rgba(0, 0, 0, .2)
}

.fc-event.fc-selected.fc-dragging {
    box-shadow: 0 2px 7px rgba(0, 0, 0, .3)
}

.fc-h-event.fc-selected:before {
    content: "";
    position: absolute;
    z-index: 3;
    top: -10px;
    bottom: -10px;
    left: 0;
    right: 0
}

.fc-ltr .fc-h-event.fc-not-start,
.fc-rtl .fc-h-event.fc-not-end {
    margin-left: 0;
    border-left-width: 0;
    padding-left: 1px;
    border-top-left-radius: 0;
    border-bottom-left-radius: 0
}

.fc-ltr .fc-h-event.fc-not-end,
.fc-rtl .fc-h-event.fc-not-start {
    margin-right: 0;
    border-right-width: 0;
    padding-right: 1px;
    border-top-right-radius: 0;
    border-bottom-right-radius: 0
}

.fc-ltr .fc-h-event .fc-start-resizer,
.fc-rtl .fc-h-event .fc-end-resizer {
    cursor: w-resize;
    left: -1px
}

.fc-ltr .fc-h-event .fc-end-resizer,
.fc-rtl .fc-h-event .fc-start-resizer {
    cursor: e-resize;
    right: -1px
}

.fc-h-event.fc-allow-mouse-resize .fc-resizer {
    width: 7px;
    top: -1px;
    bottom: -1px
}

.fc-h-event.fc-selected .fc-resizer {
    border-radius: 4px;
    border-width: 1px;
    width: 6px;
    height: 6px;
    border-style: solid;
    border-color: inherit;
    background: #fff;
    top: 50%;
    margin-top: -4px
}

.fc-ltr .fc-h-event.fc-selected .fc-start-resizer,
.fc-rtl .fc-h-event.fc-selected .fc-end-resizer {
    margin-left: -4px
}

.fc-ltr .fc-h-event.fc-selected .fc-end-resizer,
.fc-rtl .fc-h-event.fc-selected .fc-start-resizer {
    margin-right: -4px
}

.fc-day-grid-event {
    margin: 1px 2px 0;
    padding: 0 1px
}

tr:first-child>td>.fc-day-grid-event {
    margin-top: 2px
}

.fc-day-grid-event.fc-selected:after {
    content: "";
    position: absolute;
    z-index: 1;
    top: -1px;
    right: -1px;
    bottom: -1px;
    left: -1px;
    background: #000;
    opacity: .25
}

.fc-day-grid-event .fc-time {
    font-weight: 700
}

.fc-ltr .fc-day-grid-event.fc-allow-mouse-resize .fc-start-resizer,
.fc-rtl .fc-day-grid-event.fc-allow-mouse-resize .fc-end-resizer {
    margin-left: -2px
}

.fc-ltr .fc-day-grid-event.fc-allow-mouse-resize .fc-end-resizer,
.fc-rtl .fc-day-grid-event.fc-allow-mouse-resize .fc-start-resizer {
    margin-right: -2px
}

a.fc-more {
    margin: 1px 3px;
    font-size: .85em;
    cursor: pointer
}

a.fc-more:hover {
    text-decoration: underline
}

.fc-limited {
    display: none
}

.fc-day-grid .fc-row {
    z-index: 1
}

.fc-more-popover {
    z-index: 2;
    width: 220px
}

.fc-more-popover .fc-event-container {
    padding: 10px
}

.fc-bootstrap3 .fc-popover .panel-body,
.fc-bootstrap4 .fc-popover .card-body {
    padding: 0
}

.fc-now-indicator {
    position: absolute;
    border: 0 solid red
}

.fc-bootstrap3 .fc-today.alert,
.fc-bootstrap4 .fc-today.alert {
    border-radius: 0
}

.fc-unselectable {
    -webkit-user-select: none;
    -khtml-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
    -webkit-touch-callout: none;
    -webkit-tap-highlight-color: transparent
}

.fc-unthemed .fc-content,
.fc-unthemed .fc-divider,
.fc-unthemed .fc-list-heading td,
.fc-unthemed .fc-list-view,
.fc-unthemed .fc-popover,
.fc-unthemed .fc-row,
.fc-unthemed tbody,
.fc-unthemed td,
.fc-unthemed th,
.fc-unthemed thead {
    border-color: #ddd
}

.fc-unthemed .fc-popover {
    background-color: #fff;
    border-width: 1px;
    border-style: solid
}

.fc-unthemed .fc-divider,
.fc-unthemed .fc-list-heading td,
.fc-unthemed .fc-popover .fc-header {
    background: #eee
}

.fc-unthemed td.fc-today {
    background: #fcf8e3
}

.fc-unthemed .fc-disabled-day {
    background: #d7d7d7;
    opacity: .3
}

.fc-icon {
    display: inline-block;
    height: 1em;
    line-height: 1em;
    font-size: 1em;
    font-family: "Courier New", Courier, monospace;
    -webkit-touch-callout: none;
    -webkit-user-select: none;
    -khtml-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none
}

.fc-icon:after {
    position: relative
}

.fc-icon-left-single-arrow:after {
    content: "\2039";
    font-weight: 700;
    font-size: 200%;
    top: -7%
}

.fc-icon-right-single-arrow:after {
    content: "\203A";
    font-weight: 700;
    font-size: 200%;
    top: -7%
}

.fc-icon-left-double-arrow:after {
    content: "\AB";
    font-size: 160%;
    top: -7%
}

.fc-icon-right-double-arrow:after {
    content: "\BB";
    font-size: 160%;
    top: -7%
}

.fc-icon-left-triangle:after {
    content: "\25C4";
    font-size: 125%;
    top: 3%
}

.fc-icon-right-triangle:after {
    content: "\25BA";
    font-size: 125%;
    top: 3%
}

.fc-icon-down-triangle:after {
    content: "\25BC";
    font-size: 125%;
    top: 2%
}

.fc-icon-x:after {
    content: "\D7";
    font-size: 200%;
    top: 6%
}

.fc-unthemed .fc-popover .fc-header .fc-close {
    color: #666;
    font-size: .9em;
    margin-top: 2px
}

.fc-unthemed .fc-list-item:hover td {
    background-color: #f5f5f5
}

.ui-widget .fc-disabled-day {
    background-image: none
}

.fc-bootstrap3 .fc-time-grid .fc-slats table,
.fc-bootstrap4 .fc-time-grid .fc-slats table,
.fc-time-grid .fc-slats .ui-widget-content {
    background: 0 0
}

.fc-popover>.ui-widget-header+.ui-widget-content {
    border-top: 0
}

.fc-bootstrap3 hr.fc-divider,
.fc-bootstrap4 hr.fc-divider {
    border-color: inherit
}

.ui-widget .fc-event {
    color: #fff;
    font-weight: 400
}

.ui-widget td.fc-axis {
    font-weight: 400
}

.fc.fc-bootstrap3 a[data-goto]:hover {
    text-decoration: underline
}

.fc.fc-bootstrap4 a {
    text-decoration: none
}

.fc.fc-bootstrap4 a[data-goto]:hover {
    text-decoration: underline
}

.fc-bootstrap4 a.fc-event:not([href]):not([tabindex]) {
    color: #fff
}

.fc-bootstrap4 .fc-popover.card {
    position: absolute
}

.fc-toolbar.fc-header-toolbar {
    margin-bottom: 1em
}

.fc-toolbar.fc-footer-toolbar {
    margin-top: 1em
}

.fc-toolbar .fc-left {
    float: left
}

.fc-toolbar .fc-right {
    float: right
}

.fc-toolbar .fc-center {
    display: inline-block
}

.fc .fc-toolbar>*>* {
    float: left;
    margin-left: .75em
}

.fc .fc-toolbar>*>:first-child {
    margin-left: 0
}

.fc-toolbar h2 {
    margin: 0
}

.fc-toolbar button {
    position: relative
}

.fc-toolbar .fc-state-hover,
.fc-toolbar .ui-state-hover {
    z-index: 2
}

.fc-toolbar .fc-state-down {
    z-index: 3
}

.fc-toolbar .fc-state-active,
.fc-toolbar .ui-state-active {
    z-index: 4
}

.fc-toolbar button:focus {
    z-index: 5
}

.fc-view-container *,
.fc-view-container :after,
.fc-view-container :before {
    -webkit-box-sizing: content-box;
    -moz-box-sizing: content-box;
    box-sizing: content-box
}

.fc-view,
.fc-view>table {
    position: relative;
    z-index: 1
}

.fc-basicDay-view .fc-content-skeleton,
.fc-basicWeek-view .fc-content-skeleton {
    padding-bottom: 1em
}

.fc-basic-view .fc-body .fc-row {
    min-height: 4em
}

.fc-row.fc-rigid .fc-content-skeleton {
    position: absolute;
    top: 0;
    left: 0;
    right: 0
}

.fc-day-top.fc-other-month {
    opacity: .3
}

.fc-basic-view .fc-day-number,
.fc-basic-view .fc-week-number {
    padding: 2px
}

.fc-basic-view th.fc-day-number,
.fc-basic-view th.fc-week-number {
    padding: 0 2px
}

.fc-ltr .fc-basic-view .fc-day-top .fc-day-number {
    float: right
}

.fc-rtl .fc-basic-view .fc-day-top .fc-day-number {
    float: left
}

.fc-ltr .fc-basic-view .fc-day-top .fc-week-number {
    float: left;
    border-radius: 0 0 3px
}

.fc-rtl .fc-basic-view .fc-day-top .fc-week-number {
    float: right;
    border-radius: 0 0 0 3px
}

.fc-basic-view .fc-day-top .fc-week-number {
    min-width: 1.5em;
    background-color: #f2f2f2;
    color: grey
}

.fc-basic-view td.fc-week-number>* {
    display: inline-block;
    min-width: 1.25em
}

.fc-agenda-view .fc-day-grid {
    position: relative;
    z-index: 2
}

.fc-agenda-view .fc-day-grid .fc-row {
    min-height: 3em
}

.fc-agenda-view .fc-day-grid .fc-row .fc-content-skeleton {
    padding-bottom: 1em
}

.fc .fc-axis {
    vertical-align: middle;
    padding: 0 4px
}

.fc-ltr .fc-axis {
    text-align: right
}

.fc-rtl .fc-axis {
    text-align: left
}

.fc-time-grid,
.fc-time-grid-container {
    position: relative;
    z-index: 1
}

.fc-time-grid {
    min-height: 100%
}

.fc-time-grid table {
    border: 0 hidden transparent
}

.fc-time-grid>.fc-bg {
    z-index: 1
}

.fc-time-grid .fc-slats,
.fc-time-grid>hr {
    position: relative;
    z-index: 2
}

.fc-time-grid .fc-content-col {
    position: relative
}

.fc-time-grid .fc-content-skeleton {
    position: absolute;
    z-index: 3;
    top: 0;
    left: 0;
    right: 0
}

.fc-time-grid .fc-business-container {
    position: relative;
    z-index: 1
}

.fc-time-grid .fc-bgevent-container {
    position: relative;
    z-index: 2
}

.fc-time-grid .fc-highlight-container {
    z-index: 3;
    position: relative
}

.fc-time-grid .fc-event-container {
    position: relative;
    z-index: 4
}

.fc-time-grid .fc-now-indicator-line {
    z-index: 5
}

.fc-time-grid .fc-helper-container {
    position: relative;
    z-index: 6
}

.fc-time-grid .fc-slats td {
    height: 1.5em;
    border-bottom: 0
}

.fc-time-grid .fc-slats .fc-minor td {
    border-top-style: dotted
}

.fc-time-grid .fc-highlight {
    position: absolute;
    left: 0;
    right: 0
}

.fc-ltr .fc-time-grid .fc-event-container {
    margin: 0 2.5% 0 2px
}

.fc-rtl .fc-time-grid .fc-event-container {
    margin: 0 2px 0 2.5%
}

.fc-time-grid .fc-bgevent,
.fc-time-grid .fc-event {
    position: absolute;
    z-index: 1
}

.fc-time-grid .fc-bgevent {
    left: 0;
    right: 0
}

.fc-v-event.fc-not-start {
    border-top-width: 0;
    padding-top: 1px;
    border-top-left-radius: 0;
    border-top-right-radius: 0
}

.fc-v-event.fc-not-end {
    border-bottom-width: 0;
    padding-bottom: 1px;
    border-bottom-left-radius: 0;
    border-bottom-right-radius: 0
}

.fc-time-grid-event.fc-selected {
    overflow: visible
}

.fc-time-grid-event.fc-selected .fc-bg {
    display: none
}

.fc-time-grid-event .fc-content {
    overflow: hidden
}

.fc-time-grid-event .fc-time,
.fc-time-grid-event .fc-title {
    padding: 0 1px
}

.fc-time-grid-event .fc-time {
    font-size: .85em
}

.fc-time-grid-event.fc-short .fc-time,
.fc-time-grid-event.fc-short .fc-title {
    display: inline-block;
    vertical-align: top
}

.fc-time-grid-event.fc-short .fc-time span {
    display: none
}

.fc-time-grid-event.fc-short .fc-time:before {
    content: attr(data-start)
}

.fc-time-grid-event.fc-short .fc-time:after {
    content: "\A0-\A0"
}

.fc-time-grid-event.fc-short .fc-title {
    font-size: .85em;
    padding: 0
}

.fc-time-grid-event.fc-allow-mouse-resize .fc-resizer {
    left: 0;
    right: 0;
    bottom: 0;
    height: 8px;
    overflow: hidden;
    line-height: 8px;
    font-size: 11px;
    font-family: monospace;
    text-align: center;
    cursor: s-resize
}

.fc-time-grid-event.fc-allow-mouse-resize .fc-resizer:after {
    content: "="
}

.fc-time-grid-event.fc-selected .fc-resizer {
    border-radius: 5px;
    border-width: 1px;
    width: 8px;
    height: 8px;
    border-style: solid;
    border-color: inherit;
    background: #fff;
    left: 50%;
    margin-left: -5px;
    bottom: -5px
}

.fc-time-grid .fc-now-indicator-line {
    border-top-width: 1px;
    left: 0;
    right: 0
}

.fc-time-grid .fc-now-indicator-arrow {
    margin-top: -5px
}

.fc-ltr .fc-time-grid .fc-now-indicator-arrow {
    left: 0;
    border-width: 5px 0 5px 6px;
    border-top-color: transparent;
    border-bottom-color: transparent
}

.fc-rtl .fc-time-grid .fc-now-indicator-arrow {
    right: 0;
    border-width: 5px 6px 5px 0;
    border-top-color: transparent;
    border-bottom-color: transparent
}

.fc-event-dot {
    display: inline-block;
    width: 10px;
    height: 10px;
    border-radius: 5px
}

.fc-rtl .fc-list-view {
    direction: rtl
}

.fc-list-view {
    border-width: 1px;
    border-style: solid
}

.fc .fc-list-table {
    table-layout: auto
}

.fc-list-table td {
    border-width: 1px 0 0;
    padding: 8px 14px
}

.fc-list-table tr:first-child td {
    border-top-width: 0
}

.fc-list-heading {
    border-bottom-width: 1px
}

.fc-list-heading td {
    font-weight: 700
}

.fc-ltr .fc-list-heading-main {
    float: left
}

.fc-ltr .fc-list-heading-alt,
.fc-rtl .fc-list-heading-main {
    float: right
}

.fc-rtl .fc-list-heading-alt {
    float: left
}

.fc-list-item.fc-has-url {
    cursor: pointer
}

.fc-list-item-marker,
.fc-list-item-time {
    width: 1px
}

.fc-ltr .fc-list-item-marker {
    padding-right: 0
}

.fc-rtl .fc-list-item-marker {
    padding-left: 0
}

.fc-list-item-title a {
    text-decoration: none;
    color: inherit
}

.fc-list-item-title a[href]:hover {
    text-decoration: underline
}

.fc-list-empty-wrap2 {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0
}

.fc-list-empty-wrap1 {
    width: 100%;
    height: 100%;
    display: table
}

.fc-list-empty {
    display: table-cell;
    vertical-align: middle;
    text-align: center
}

.fc-unthemed .fc-list-empty {
    background-color: #eee
}

/*!
 * Bootstrap Colorpicker v2.5.2
 * https://itsjavi.com/bootstrap-colorpicker/
 *
 * Originally written by (c) 2012 Stefan Petre
 * Licensed under the Apache License v2.0
 * http://www.apache.org/licenses/LICENSE-2.0.txt
 *
 */

.colorpicker-saturation {
    width: 100px;
    height: 100px;
    background-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAGQAAABkCAQAAADa613fAAAP9klEQVR4XnRWC47rNgwcKjlA0bv2VL1Qi/YELRav7203iS1ppqZoiXCAhuBHVLI74xFtG3/Hz2joIOjRGuR5eMYuRn9YA1fds859KX8ZvczLr9/pImiR3Rqky9/wlajRIdVE/1Rufeu/0No3/ASgBZAJUkwgi0iCaEatekJJoEqiTQncd67/gyOfRCZshTed0Nl8LbLj8D6qxtoq9/7kJz/aH/3Xfu8VwI5+AUH8DxE7gUyiIpZ5LwiGzUqE3CScJsCDQHAsvBnxWpkbC0QMHmBp6latWS0bnvrCN/x1+xPfce+Ij0GAyeAGGz15sOiax2UylPhKrFaMPnVWClwepKh07hdhkVDsK2uoyEIySergjdbY2VBtV8VLr8Mf9mF/4wMb7kR8FOhzFWZZe7HIZD9JRIbee28eJKBweTB6TwjYkAgWaUmtDveGw1Wx3zZ76YlPPfQd/+gTTUFkiGiJ+NQAszU1EPT/QJEgufolAMPkNU4CVOyUIBLg4xglEZHGQnTFOFV0VaulYddBhA986ge/7N/yQi/3flFgwfQq2ibLnTDBRl9TmUHyJASPV/eoN0UISIr+ICQKIFV4EpljSjV1uFVUq9hRtet5e9gXvuyHPW0zMhQxWaoBBa9Tg8vsCEhww23Smd0CKjIkmPIoxWrUBDgJqFCyESF43ctQxLUoHN7Q1KyVhqrNNm3cy2vMyQNPVKjc29Rh5SSU+giWdRJHkLnQG71FQEuNyNGBTDdBQQAKCuGiEUS/jcyGbkMPq931OIzb/dUPGuVlG7f+slqkO5NAAlzTMdcq0NkzmsEBmAQkbI+pSHbiqnuWIA6lijhvqwIxMyWxMGZiPU669XJE1tADDTs2HWpwKxuqdnTpOiOR42xlzLtm3pXGel3xd8/oTs8Xy0MV8GM1RlsC2Y3Wy3wut3M+2mEVux0Gt9fhzTWyLvGiiJYaqY5DWRFIwAiQ5r6gB9GpQihJw4I9j5Mkscj3BnzGjBhv8xna5P1Jo428o6IOPY5KFZtVOkEKqUjqQY9Gi+jrIOFwJUDzRtA9xyoIrGGmkNRmxVAnZoK+TkUIeUYni5wEzgOG5iZX5HCr2JyQNqdk++G0rgb1ochSIGutTj4P7F0PuRUAolmh5sCzAHn1BYyaADh6bgFeoBx6vst091CEvcSLWBBpqGq384jZ5llVHSwEShLx+D4d0mU3D5eEAJQ9KEhOZUYnDENV2qKgmIlQhWfdvcoXYaegPp/n1oKIOgYFqxrzQSciqNhv/5FqPpy6b0UcX2vf13DfWySRSEgkEYlEJJGQSyKJSEQSCYlEEpHexIVO3XOevffze2a+PfPv9x1rne1c3b3Mmlmz9mE++zuzngfnw/E+Dlc4LL4NwHdFy7u3KGPVmZ6/4eeMoDyre3i/KHADIHYO04w9zO0mAotuKnrc7XaPjvu66bNe5cDT7RlPepEnfS2X8dF1/utDvD+OwGDBxEgQywLCvIMYWBY+DShwAAORAdv9PswhDAqOUCi5+71AbFcDMR4xBDNfhySKXPXZ1+Vub+Q1Ltf5z7eC0AjVldHI26rIFdKIAyYBJCFVUhVDwttAnM52B3Ect1TFQXzJ0z33lOuib/QO8g+CuO0gKBRU80A8hkeJ0b1KRQWmFQVSh8mf3lpUpNaRulzN5NArrmKKGMijXgzk7w5ijdFVgT8f1IdFNjVWjDWicUYWEEMmSFDtILdzHW5XueHp7p+yuS54ep5/c5BE2Gw/gWPNYU4/PZaak2VGEsFjSbOf8irea6KQgojGCk0KxZY31tWWgzwayF8N5KYyo3VADVicWWrhwzr3ZqIOa5xW5zbqMPPMiyDURHDIHQTeWq7KFXcQPOqzPOL5Ov/iIDEDy7DHEwx0PTgjO8SS0fOEHcZNMt+XKEFMj8Q4QUSvPu6HPuvd4N9/x12RPwcIVRCAakSOUzHgsUSMFWYzDQ+PiOJqAOuYc9jh5TecnA+xHfFyOYhebeTH89P80wrCJzUjlsx7euIV0g4zQFUSiBPioIWBACFC7GgDj8P91ZSJOQmQP74MAnQo8H5RIe8kZ0kBcQCMAlEpRDiKROBxbR0ksdhWFq0gR9q9uQzkDzuIFQSPqAgRCAsCaVNF2ZAAhxvtzcqcnDk6tpXxSsayqXLIgSOb6zqeH+fvO0i9XEu5EVV+OZehRZJ6BGTeaRhCkTzVIZeAzaWGAFfErIPogQI5CuR3HQQx7DzBB16R3s7e0MBUPedjWutgG/JUTPqMeAQNEiytJRnJearWUgdwFNxN7rtBoECuj/O3BMHaTIxQ0a4GctireElTJHJvLTaalih5kvBCGMvkdESUMAdCFaI4yG8SpDfRWAptqkAJUwCG6B7lOREFSZBqKs57MEHqVJEBwHa2lp0OiKtiQ18gx9P89QrSXyc0vObBM4vPmBADqJZLAo/yzK7qPSZstCy+fDSZlhrm+Zkyjsf5q2otdC14zkLjHLf0me9wjNqQo0B1a6wBJRaIEgC2Qw9oby/cRHA+xHCQy/xlB1HVSV3Y/5yVhsc7dBi2UoIWCMcbELZWgxNCGUZ5y4ceBaLlE8dAfrEosrYT+z8ya3sxXndFBxuQivNGEHFCbLGBlBLKGYHZoeoQpcjtMn/uICPefcxecpuDOEemg9S/44cflZPIlWolyHkLrEpgbS9IQRlAgZgi0WDjsEiPh+PN/Fkogq4GdzPtarlRGW2tJwEK1RMTEvdVdmhAKHO1pdUuGQsVcX+rSfGzDbwGyE8NRPQc83HCaOkTZwPqABZBdFq8zAN1gue0FPO8wYUFBE1WkMwVzM1iQ4BItFh+H36Qy/yJg0DRQICmBl+tbKUC5cCj3yXI+SUFBS78ZAcBtHt+e9lBuiqpTNh9zTvIjzuIWxVYGQJpAZY+VWS3QKh84iSZbwuIdiDpc4KztQa/sjhMaDJEJDSZ8mZ+kCBdC0JpKVNQzZdKu+EsOeFCosrngVAkDS/uy6iGnW7UxmMpkB8FyFKo6iQW8z1HuBdMu1pdkZdB8jWTjlFtNaiJRYniIDcD+eECMqFLS9ED6DgxzCMKnRD3HYYA2uMCJUh70OK8G0EUnJV8lqe8nj84QdqLhdoJskNlEw1ivajM8LtPBhIeN99LESXI9xcQIHFQudHngZjUhXOQeGlUYmAddh5pxMhzV0M1vMAtMFIVmfp6fq+DgEWefjQVenstaqUy3bJQAiVlEihDghCDINFQg8oUhoQPkO8SBEM7SFQ72VYBwPuE7k8uYF5LNwg/TEd2zkuKjIIhTiJRlYrDfNS1QL7DYUcbcCyKJNwOwucVCVSwBBj/DwghXA2hQtACgCBBPprfXkAIFIYRXhONQARFU00Tsh6LEmmQUbkTImMi9me5qaHDIeBgHeRbdxAIqAJBCDSoCNVQglrciqX/ZCD9RRP6rgpBvhmKAFhg2ForBLXBYPtUjj7vCHPe8SXbYAY47gHB9mKeqjjIg/53fmMD0fR9Bug7SFcHI6EA1OC/E8QTL4NgBSGiCiyTChnI1zcQxmyfRZGM6w701KRybDvsIK3LWDx6mxGkcglEZQLkawnCdppZ6sgCh8trWWBUQaUWCEOlOs7HAenFE45QSu9RQQDAqchXNxDq4orQR44qRIFUQvM+mRJuB6GDEixgCbSBQGXghEEbdn1P/zO/QhAWCsWsmRhLa2VFkSZIgSVKmgEQhvk6K8YKMRZl7Dwg4amOUYvFBfLlE4RasOCB5S9PXKq0AqGDMiYIReXF0mYctITWBmqR5F38X5Y7yJfeCtKBzNbWYm5XpsMpf3dRZD3jPDesvdVCOs6KYQXIFw1E4fcE8dHWOepZBXpLJcACWUZVMRZbfvgXR4Ak8A7VVSKSVuu9p6/mFxyE7cOWavtLp952O8huK83+gmHzHaAsVXLgAvl8gPCvHzAFsM8GNXGKPH5cmN02sXTLa8QdKRXMzHv67/k5A9k1UIx36UH/VlWWtuKssNiRapB6BaLXl6MA+ayDcNS3v/sYXgCL620F1kk8QhKAEOvKu4DvajDO5zkHc4fBg76anyEIIcamBPex5EK8AoVHhMW7QAqWrYD1204CJB1hCfOAV/PTBPH0zBmJmsZZKCEaAmdqm4zMcYxYLN0JuHThIAjirAnp3px7TRgD+ZSD/K92M1CNIgbC8Ex7FkSEIlQEEUQEQQQBRBABEUQQEQTx3X0Evap9AhP39jL5OvuzAWuvbDaTTDIzX2aypUCJ0i7nAigoQAk9gUIUSxXEoCFyyVIuL9ZQcMZoArnwr4D0OLS8jGNGTgGnsZQWMYrcOARoIReAALBeWhf+RUCAIEsECFQHLkwR5zj4JW3t5WOUU5djvgQIawD53EDsctmYz8xGaZGPBUR3qNkiGwqDICUYIFpqBgRaayCfFiAWR2wWvoobmzxdF8N5kyxXmvap/sgGcLF/aoBosbG+lE395R8zCA4BqUYgOgYq+HtvBrT0LK15X8lZwx5f9klCX0rdgXzIIGbdhXMqZtHzJhuptEjmsFc4KzmN5IFPtfM7gWw2kPczSIqQSPUDYKYBMamsBCpKphW0iA5H8AbMDPJOQYjLZg1Vk4G49GlCYNYAkdOd0kwRQ8FCyAHydgLZ6Z2AqrVtjDUQ7hCEmrkEooDAsB2YnBCvkBpZ6yBvJpCd7Mn5zJ6C4QF2BUQPgHEIGUrGnHzQ8rlMekBeTyAzwDJksxwM4+w3BY02B8mIl0CmFRm+ZscxAuSnvwqQsECTIGSV6FEoJFTygVuzB5xAsKqBvAQE3+nkVoJDI1BJIaPBWik7ZSu5NIp5A3mRQaTFvLgkO9fVgEgMqqeVfb+p55tijWH+Kea71ubq4v8Sl8089sZKbKEZNq+VUfISJJF7j79WrbYgS994ZEf+nIz0pNFRWqapSmK6P45i3OQuItIiPDyg6RnxZ4D0g+CFPxAzluoRsWsaA6I6JOqVWCisDvJ0BgHTzMSRgMi0vmi8R+sR6tg/XUh7kCc7kMRqSNkTBDx0OkAUegFcMazciBXNpm798R6klXap/WZz49TQwBHqEcj4oCToUPjUuP9lfxcbyKMAwT6bTf1qqIIQDl3i5oCERNmVm0wgW4A8BGRxMX3hWh8bEV5Rvfp4DS5F3djWH2ztDNWKW7OBjgjIwsDWaKRknJjqMsh9QCa1p608lLovFkBE969DYtYelSzwSRcg535vAsFeNU9SzRCYZb4LDmxmFQKkwYGM+5y/G7b1uxMIylLdyE5yxIyYsoXWhQIpzQhYPi3JkJoKkB9+BxD0OMuyOEBe36DgyPSrxscmATldgKj8PxrkA/kA5PYMgkrocwIQ6GSRGmF0VaNqBKQZ5FYDEZSDzFTzq9mBQjAayE1A+ryDTzcQZe0Ibbxj7EwpAmTrJwEimZR9CCPtODhzxuNtY19Zd2Lf/fjCTnEiDAOg62j1utb/dv9mZ/aHCj4AyOHbsW3/As0BTzIgeJU7AAAAAElFTkSuQmCC);
    cursor: crosshair;
    float: left
}

.colorpicker-saturation i {
    display: block;
    height: 5px;
    width: 5px;
    border: 1px solid #000;
    -webkit-border-radius: 5px;
    -moz-border-radius: 5px;
    border-radius: 5px;
    position: absolute;
    top: 0;
    left: 0;
    margin: -4px 0 0 -4px
}

.colorpicker-saturation i b {
    display: block;
    height: 5px;
    width: 5px;
    border: 1px solid #fff;
    -webkit-border-radius: 5px;
    -moz-border-radius: 5px;
    border-radius: 5px
}

.colorpicker-alpha,
.colorpicker-hue {
    width: 15px;
    height: 100px;
    float: left;
    cursor: row-resize;
    margin-left: 4px;
    margin-bottom: 4px
}

.colorpicker-alpha i,
.colorpicker-hue i {
    display: block;
    height: 1px;
    background: #000;
    border-top: 1px solid #fff;
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    margin-top: -1px
}

.colorpicker-hue {
    background-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAABkCAMAAABw8qpSAAABLFBMVEXqFBb/ABH/ACL/ADH/AEH/AFD/AGD/AG7/AH7/AI3/AJ3/AKz/ALz/AMr/ANv/AOr/APr2AP/mAP/XAP/HAP+4AP+oAP+aAP+JAP97AP9rAP9cAP9MAP8+AP8tAP8fAP8PAP8BAv8AEP8AH/8AL/8APv8ATv8AXP8Abf8Ae/8Ai/8Amv8Aqv8AuP8Ayf8A1/8A5/8A9/8A//gA/+kA/9kA/8oA/7oA/6wA/5sA/40A/30A/24A/14A/1AA/z8A/zEA/yEA/xEB/wMN/wAd/wAs/wA8/wBK/wBb/wBp/wB5/wCI/wCY/wCm/wC3/wDF/wDV/wDk/wD1/wD/+gD/7AD/3AD/zAD/vgD/rQD/nwD/jgD/gAD/cAD/YgD/UQD/QwD/MgD/JAD/FAD4Eg42qAedAAAAh0lEQVR4XgXAg3EDAAAAwI9to7Zt27a1/w49BASFhEVExcQlJKWkZWTl5BUUlZRVVNXUNTS1tHXo1KVbj159+g0YNGTYiFFjxk2YNGXajFlz5i1YtGTZilVr1m3YtGXbjl179h04dOTYiVNnzl24dOXajVt37j149OTZi1dv3n349OXbj19//wOxE1dQ8reGAAAAAElFTkSuQmCC)
}

.colorpicker-alpha {
    background-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAoAAABkCAQAAAAVxWkcAAABr0lEQVR4Xo2VwU0DQQxF7dmRuNIFlzlSAR3QAaXQQdIBJVABFXDcOVAAd67cjJLR07dkhcSrkZKfb/t7bG88rFo3B5gZPMNycItu2xloGV7MWHzM9zuzFWCkmA0nK6AszCUJDW6+mG6R03ncw5v8EMTEvZ2O3AliYjpslblc0RF9LmZYWxURU6aKytWZYsoWCAe+xwOZp1GsEukGiIkYxcQCHck99+gRgB7JncyIB5SGEhP3Yh5P6JwX+u6AnYot104d8DJT7uH7M9JH6OZbimj0vfMVaYnJIZFJDBW9kHlerL2C6JV4mSt7uuo2N57RxnZ+usQjn0R1jwBJBrNO3evJpVYUWsJ/E3UiXRlv24/7YZ04xmEdWlzcKS+B/eapeyMvFd2k0+hRk/T0AmTW8h69s2sjYMsdPntECiILhAeIMZAeH4QvUwfn6ijC0tTV+fT9ky8jM9nK2g7Ly1VjSpKYq6IvsAm7MtNu1orEqa/K3KNvgMFdhfquPfJmp2dbh0/8Gzb6Y22ViaNr6n5410zXdngVhbu6XqdOtWOuin5hjABGp4a2uotZ71MVCfwDBt2/v37yo6AAAAAASUVORK5CYII=);
    display: none
}

.colorpicker-alpha,
.colorpicker-hue,
.colorpicker-saturation {
    background-size: contain
}

.colorpicker {
    padding: 4px;
    min-width: 130px;
    margin-top: 1px;
    -webkit-border-radius: 4px;
    -moz-border-radius: 4px;
    border-radius: 4px;
    z-index: 2500
}

.colorpicker:after,
.colorpicker:before {
    display: table;
    content: "";
    line-height: 0
}

.colorpicker:after {
    clear: both
}

.colorpicker:before {
    content: '';
    display: inline-block;
    border-left: 7px solid transparent;
    border-right: 7px solid transparent;
    border-bottom: 7px solid #ccc;
    border-bottom-color: rgba(0, 0, 0, .2);
    position: absolute;
    top: -7px;
    left: 6px
}

.colorpicker:after {
    content: '';
    display: inline-block;
    border-left: 6px solid transparent;
    border-right: 6px solid transparent;
    border-bottom: 6px solid #fff;
    position: absolute;
    top: -6px;
    left: 7px
}

.colorpicker div {
    position: relative
}

.colorpicker.colorpicker-with-alpha {
    min-width: 140px
}

.colorpicker.colorpicker-with-alpha .colorpicker-alpha {
    display: block
}

.colorpicker-color {
    height: 10px;
    margin-top: 5px;
    clear: both;
    background-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAoAAABkCAQAAAAVxWkcAAABr0lEQVR4Xo2VwU0DQQxF7dmRuNIFlzlSAR3QAaXQQdIBJVABFXDcOVAAd67cjJLR07dkhcSrkZKfb/t7bG88rFo3B5gZPMNycItu2xloGV7MWHzM9zuzFWCkmA0nK6AszCUJDW6+mG6R03ncw5v8EMTEvZ2O3AliYjpslblc0RF9LmZYWxURU6aKytWZYsoWCAe+xwOZp1GsEukGiIkYxcQCHck99+gRgB7JncyIB5SGEhP3Yh5P6JwX+u6AnYot104d8DJT7uH7M9JH6OZbimj0vfMVaYnJIZFJDBW9kHlerL2C6JV4mSt7uuo2N57RxnZ+usQjn0R1jwBJBrNO3evJpVYUWsJ/E3UiXRlv24/7YZ04xmEdWlzcKS+B/eapeyMvFd2k0+hRk/T0AmTW8h69s2sjYMsdPntECiILhAeIMZAeH4QvUwfn6ijC0tTV+fT9ky8jM9nK2g7Ly1VjSpKYq6IvsAm7MtNu1orEqa/K3KNvgMFdhfquPfJmp2dbh0/8Gzb6Y22ViaNr6n5410zXdngVhbu6XqdOtWOuin5hjABGp4a2uotZ71MVCfwDBt2/v37yo6AAAAAASUVORK5CYII=);
    background-position: 0 100%
}

.colorpicker-color div {
    height: 10px
}

.colorpicker-selectors {
    display: none;
    height: 10px;
    margin-top: 5px;
    clear: both
}

.colorpicker-selectors i {
    cursor: pointer;
    float: left;
    height: 10px;
    width: 10px
}

.colorpicker-selectors i+i {
    margin-left: 3px
}

.colorpicker-element .add-on i,
.colorpicker-element .input-group-addon i {
    display: inline-block;
    cursor: pointer;
    height: 16px;
    vertical-align: text-top;
    width: 16px
}

.colorpicker.colorpicker-inline {
    position: relative;
    display: inline-block;
    float: none;
    z-index: auto
}

.colorpicker.colorpicker-horizontal {
    width: 110px;
    min-width: 110px;
    height: auto
}

.colorpicker.colorpicker-horizontal .colorpicker-saturation {
    margin-bottom: 4px
}

.colorpicker.colorpicker-horizontal .colorpicker-color {
    width: 100px
}

.colorpicker.colorpicker-horizontal .colorpicker-alpha,
.colorpicker.colorpicker-horizontal .colorpicker-hue {
    width: 100px;
    height: 15px;
    float: left;
    cursor: col-resize;
    margin-left: 0;
    margin-bottom: 4px
}

.colorpicker.colorpicker-horizontal .colorpicker-alpha i,
.colorpicker.colorpicker-horizontal .colorpicker-hue i {
    display: block;
    height: 15px;
    background: #fff;
    position: absolute;
    top: 0;
    left: 0;
    width: 1px;
    border: none;
    margin-top: 0
}

.colorpicker.colorpicker-horizontal .colorpicker-hue {
    background-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAGQAAAABCAMAAAAfBfuPAAABLFBMVEXqFBb/ABH/ACL/ADH/AEH/AFD/AGD/AG7/AH7/AI3/AJ3/AKz/ALz/AMr/ANv/AOr/APr2AP/mAP/XAP/HAP+4AP+oAP+aAP+JAP97AP9rAP9cAP9MAP8+AP8tAP8fAP8PAP8BAv8AEP8AH/8AL/8APv8ATv8AXP8Abf8Ae/8Ai/8Amv8Aqv8AuP8Ayf8A1/8A5/8A9/8A//gA/+kA/9kA/8oA/7oA/6wA/5sA/40A/30A/24A/14A/1AA/z8A/zEA/yEA/xEB/wMN/wAd/wAs/wA8/wBK/wBb/wBp/wB5/wCI/wCY/wCm/wC3/wDF/wDV/wDk/wD1/wD/+gD/7AD/3AD/zAD/vgD/rQD/nwD/jgD/gAD/cAD/YgD/UQD/QwD/MgD/JAD/FAD4Eg42qAedAAAAbUlEQVR4XgXAghEDsbxtlrZt27ax/w49ACAYQTGcICmaYTleECVZUTXdMC1Wm93hdLk9Xp8/EAyFI9FYPJFMpTPZXL5QLJUr1Vq90Wy1O91efzAcjSfT2XyxXK03293+cDydL9fb/fF8vT/f3x+LfRNXARMbCAAAAABJRU5ErkJggg==)
}

.colorpicker.colorpicker-horizontal .colorpicker-alpha {
    background-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAGQAAAAKCAQAAADoFTP1AAAB9ElEQVR4XoWTQW4VMRBEu9qWEimL7DhEMp8NF+ASnJJLcAQgE1bcgBUSkYKUuHCrZ9pjeqSU5Yn9LPu7umJQBIIv+k7vIOrtK66L4lmr3pVOrOv3otp619KZ0/KjdNI79L52Uo09FBQWrU0vfe5trezU+hLsoUKd3Repovte+0vbq/7Lj5XbaHECKasR9G4MPlbp+gzZxd6koPEJCkAYC5SjcOTAIIOK90Dja1IfIZ8Z+zAY9jm3b5Ia+MT5sFcqRJrR2AYYA8Kua5BzYRrFPNmD4PQMegGJMOffJJUsWiI3nCHZZjInNdffLWOufzbc3JaboCAVxwmnRHbhLSPwRJ4wU0BRSc6HkECYYVw95nMKgJOcylxrJttE5Ibzf9Xq9GPvP+WX3MiV/MGHfRu/SentRQrfG1GzsIrytdNXucSRKxQNIGHM9YhGFQJcdjNcBZvfJayuYe4Sia1CzwW+19mWOhe37HsxJWKwbu/jluEU15QzAQjAqCEbhMJc78GYV2E0kooHDubUImWkTOhGpgv8PoT8DJG/bzxna4BZ0eOFSOaLADGeSpFsg5AzeaDZIDQQXjZ4y/8ryfzUXBwdELRjTjCNvOeT0rNlrJz90vwy6N9pXXQEluX0inElpPWokSdiLCfiNJJjMKQ8Qsh8GEKQKMo/eiHrNbI9UksAAAAASUVORK5CYII=)
}

.colorpicker-right:before {
    left: auto;
    right: 6px
}

.colorpicker-right:after {
    left: auto;
    right: 7px
}

.colorpicker-no-arrow:before {
    border-right: 0;
    border-left: 0
}

.colorpicker-no-arrow:after {
    border-right: 0;
    border-left: 0
}

.colorpicker-alpha.colorpicker-visible,
.colorpicker-hue.colorpicker-visible,
.colorpicker-saturation.colorpicker-visible,
.colorpicker-selectors.colorpicker-visible,
.colorpicker.colorpicker-visible {
    display: block
}

.colorpicker-alpha.colorpicker-hidden,
.colorpicker-hue.colorpicker-hidden,
.colorpicker-saturation.colorpicker-hidden,
.colorpicker-selectors.colorpicker-hidden,
.colorpicker.colorpicker-hidden {
    display: none
}

.colorpicker-inline.colorpicker-visible {
    display: inline-block
}

.kanban-board {
    width: 500px;
    margin-left: 5px;
    margin-right: 5px;
    background: #e2e4e6
}

.kanban-container {
    width: 1320px
}

.meta-tasks {
    height: 100%;
    padding: 15px 0;
    position: relative;
    overflow-y: auto
}

.meta-tasks .kanban-board-header {
    position: relative;
    padding: 15px
}

.kanban-item {
    background: #fff
}

.card-action {
    font-size: 12px;
    border: none;
    border-radius: 4px;
    padding: 1px 4px;
    display: inline-block;
    background: 0 0;
    color: rgba(0, 0, 0, .4)
}

.card-action:hover {
    background: rgba(0, 0, 0, .2);
    color: rgba(0, 0, 0, .6)
}

.page {
    display: -webkit-box;
    display: flex;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    flex-direction: column;
    height: 100%
}

.page .main {
    -webkit-box-flex: 1;
    flex-grow: 1;
    height: 550px
}

.page .footer {
    background: #e7e7e7;
    border-top: 1px solid #ddd;
    padding: 4px 10px 5px;
    text-align: center;
    font-weight: 300;
    font-size: 14px
}

.meta-tasks-wrapper {
    height: 100%;
    position: relative
}

.meta-tasks-wrapper::before {
    content: "";
    position: absolute;
    bottom: 0;
    left: 0;
    top: 0;
    width: 5px;
    background: -webkit-gradient(linear, right top, left top, from(transparent), color-stop(66%, #fff));
    background: linear-gradient(to left, transparent, #fff 66%);
    z-index: 1;
    pointer-events: none
}

.meta-tasks-wrapper::after {
    content: "";
    position: absolute;
    bottom: 0;
    right: 0;
    top: 0;
    width: 5px;
    background: -webkit-gradient(linear, left top, right top, from(transparent), color-stop(66%, #fff));
    background: linear-gradient(to right, transparent, #fff 66%);
    pointer-events: none
}

.meta-tasks .kanban-board {
    overflow-y: hidden
}

.meta-tasks .kanban-board footer {
    position: relative
}

.meta-tasks .kanban-board footer a {
    display: block;
    padding: 10px 15px;
    color: #666;
    text-decoration: none
}

.meta-tasks .kanban-board footer a:hover {
    color: #333;
    background: rgba(0, 0, 0, .1)
}

.meta-tasks .kanban-board footer a:active {
    background: rgba(0, 0, 0, .2)
}

.meta-tasks .kanban-board footer::before {
    content: "";
    position: absolute;
    top: -10px;
    left: 0;
    right: 0;
    height: 10px;
    background: -webkit-gradient(linear, left top, left bottom, from(rgba(226, 228, 230, 0)), color-stop(66%, #e2e4e6));
    background: linear-gradient(rgba(226, 228, 230, 0), #e2e4e6 66%);
    pointer-events: none
}

.meta-tasks .kanban-board-header::after {
    content: "";
    position: absolute;
    bottom: -10px;
    left: 0;
    right: 0;
    height: 10px;
    background: -webkit-gradient(linear, left bottom, left top, from(rgba(226, 228, 230, 0)), color-stop(66%, #e2e4e6));
    background: linear-gradient(to top, rgba(226, 228, 230, 0), #e2e4e6 66%);
    pointer-events: none;
    z-index: 1
}

.meta-tasks .kanban-board-header .kanban-title-board {
    display: -webkit-box;
    display: flex;
    -webkit-box-orient: horizontal;
    -webkit-box-direction: normal;
    flex-direction: row;
    text-shadow: 1px 1px 0 rgba(255, 255, 255, .3), -1px -1px 0 rgba(0, 0, 0, .3)
}

.meta-tasks .kanban-board-header .kanban-title-board .board-title {
    -webkit-box-flex: 1;
    flex-grow: 1
}

.meta-tasks .kanban-board-header .kanban-title-board .board-actions {
    margin-left: auto;
    margin-top: -5px
}

.meta-tasks .kanban-board-header .kanban-title-board .board-actions .action {
    background: 0 0;
    color: rgba(0, 0, 0, .4);
    border: none;
    border-radius: 4px
}

.meta-tasks .kanban-board-header .kanban-title-board .board-actions .action:hover {
    background: rgba(0, 0, 0, .2);
    color: rgba(0, 0, 0, .6)
}

.meta-tasks .kanban-board-header .kanban-title-board .board-actions .action:active {
    background: rgba(0, 0, 0, .4);
    color: rgba(0, 0, 0, .8)
}

.meta-tasks .kanban-item {
    margin-top: 10px;
    margin-bottom: 10px;
    padding: 10px;
    box-shadow: 0 1px 3px rgba(0, 0, 0, .12), 0 1px 2px rgba(0, 0, 0, .24);
    -webkit-transition: all .3s cubic-bezier(.25, .8, .25, 1);
    transition: all .3s cubic-bezier(.25, .8, .25, 1);
    position: relative
}

.meta-tasks .kanban-item:hover {
    cursor: pointer;
    box-shadow: 0 3px 9px rgba(0, 0, 0, .25), 0 3px 6px rgba(0, 0, 0, .22)
}

.meta-tasks .kanban-item:hover::before {
    content: "";
    position: absolute;
    left: 0;
    top: 0;
    bottom: 0;
    width: 6px;
    background: red
}

.meta-tasks .kanban-item:hover .card-actions {
    display: block;
    background: rgba(255, 255, 255, .9);
    padding-left: 5px
}

.meta-tasks .kanban-item:hover .card-actions .action {
    font-size: 12px
}

.meta-tasks .kanban-item:hover .card-title {
    max-height: unset
}

.meta-tasks .kanban-item .card-title {
    max-height: 8.8em;
    margin-bottom: 0;
    font-size: 14px;
    line-height: 20px
}

.meta-tasks .kanban-item .card-title:last-child {
    margin-bottom: 0
}

.meta-tasks .kanban-item .card-actions {
    margin-left: auto;
    text-align: right;
    display: none;
    position: absolute;
    right: 0;
    top: 10px;
    right: 10px
}

.meta-tasks .kanban-item .card-actions .action {
    background: 0 0;
    color: rgba(0, 0, 0, .4);
    border: none;
    border-radius: 4px;
    padding: 1px 6px;
    display: inline-block
}

.meta-tasks .kanban-item .card-actions .action:hover {
    background: rgba(0, 0, 0, .2);
    color: rgba(0, 0, 0, .6)
}

.meta-tasks .kanban-item .card-actions .action:active {
    background: rgba(0, 0, 0, .4);
    color: rgba(0, 0, 0, .8)
}

.meta-tasks .kanban-item .card-tags {
    margin-bottom: -10px;
    padding-top: 5px;
    padding-bottom: 5px;
    background: -webkit-gradient(linear, left top, left bottom, from(transparent), color-stop(15%, #fff));
    background: linear-gradient(to bottom, transparent, #fff 15%);
    position: relative;
    font-size: 14px;
    line-height: 20px
}

.meta-tasks .kanban-item .card-tags .badge {
    font-size: 12px;
    line-height: 14px
}

.meta-tasks .kanban-container {
    display: -webkit-box;
    display: flex;
    -webkit-box-align: start;
    align-items: flex-start;
    height: 100%;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none
}

.meta-tasks .kanban-container .kanban-board {
    float: none;
    display: -webkit-box;
    display: flex;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    flex-direction: column;
    max-height: 100%;
    border-radius: 4px
}

.meta-tasks .kanban-container .kanban-board .kanban-drag {
    overflow-y: auto;
    min-height: 100px;
    position: relative;
    padding: 0 10px 35px
}

.meta-tasks .kanban-container .kanban-board .kanban-drag .ps__rail-x {
    display: none !important
}

.meta-tasks .kanban-container .kanban-board .kanban-drag .ps__rail-y {
    z-index: 1;
    opacity: 1;
    border-radius: 7px;
    background: rgba(0, 0, 0, .1);
    width: 7px;
    right: 4px !important
}

.meta-tasks .kanban-container .kanban-board .kanban-drag .ps__rail-y .ps__thumb-y {
    right: 0;
    width: 100%
}

.meta-tasks .card-tags>:not(:last-child) {
    margin-right: 4px;
    font-weight: 400
}

.meta-tasks .kanban-board-header .board-title {
    font-size: 16px;
    font-weight: 500;
    line-height: 1.2
}

.meta-tasks .kanban-board-header.success {
    background: #00b961
}

.meta-tasks .kanban-board-header.success+.kanban-drag .kanban-item:hover::before {
    background: #00b961
}

.meta-tasks .kanban-board-header.info {
    background: #2a92bf
}

.meta-tasks .kanban-board-header.info+.kanban-drag .kanban-item:hover::before {
    background: #2a92bf
}

.meta-tasks .kanban-board-header.warning {
    background: #f4ce46
}

.meta-tasks .kanban-board-header.warning+.kanban-drag .kanban-item:hover::before {
    background: #f4ce46
}

.meta-tasks .kanban-board-header.error {
    background: #fb7d44
}

.meta-tasks .kanban-board-header.error+.kanban-drag .kanban-item:hover::before {
    background: #fb7d44
}

.meta-tasks .kanban-board-header.new {
    background: #f1e5e5;
    color: #c83131
}

.meta-tasks .kanban-board-header.new+.kanban-drag .kanban-item:hover::before {
    background: #c83131
}

.kanban-item.dragging .card-actions,
.kanban-item.dragging:hover .card-actions {
    display: none !important
}

.switch-light span span,
.switch-toggle a {
    display: none
}

@media only screen {
    .switch-light {
        position: relative;
        display: block
    }
    .switch-light::after {
        clear: both;
        content: '';
        display: table
    }
    .switch-light *,
    .switch-light :after,
    .switch-light :before {
        box-sizing: border-box
    }
    .switch-light a {
        display: block;
        transition: all .2s ease-out
    }
    .switch-light label,
    .switch-light>span {
        line-height: 2em
    }
    .switch-light input:focus+label,
    .switch-light input:focus~span a {
        outline-width: 2px;
        outline-style: solid;
        outline-color: Highlight
    }
}

@media only screen and (-webkit-min-device-pixel-ratio:0) {
    .switch-light input:focus+label,
    .switch-light input:focus~span a {
        outline-color: -webkit-focus-ring-color;
        outline-style: auto
    }
}

@media only screen {
    .switch-light input {
        position: absolute;
        opacity: 0;
        z-index: 3
    }
    .switch-light input:checked~span a {
        right: 0
    }
    .switch-light strong {
        font-weight: inherit
    }
    .switch-light>span {
        position: relative;
        overflow: hidden;
        display: block;
        min-height: 2em;
        padding: 0;
        text-align: left
    }
    .switch-light span span {
        position: relative;
        z-index: 2;
        display: block;
        float: left;
        width: 50%;
        text-align: center;
        user-select: none
    }
    .switch-light a {
        position: absolute;
        right: 50%;
        top: 0;
        z-index: 1;
        display: block;
        width: 50%;
        height: 100%;
        padding: 0
    }
    .switch-light.row {
        display: flex
    }
    .switch-light .alert-light {
        color: #333
    }
    .switch-toggle {
        position: relative;
        display: block;
        padding: 0 !important
    }
    .switch-toggle::after {
        clear: both;
        content: '';
        display: table
    }
    .switch-toggle *,
    .switch-toggle :after,
    .switch-toggle :before {
        box-sizing: border-box
    }
    .switch-toggle a {
        display: block;
        transition: all .2s ease-out
    }
    .switch-toggle label,
    .switch-toggle>span {
        line-height: 2em
    }
    .switch-toggle input:focus+label,
    .switch-toggle input:focus~span a {
        outline-width: 2px;
        outline-style: solid;
        outline-color: Highlight
    }
}

@media only screen and (-webkit-min-device-pixel-ratio:0) {
    .switch-toggle input:focus+label,
    .switch-toggle input:focus~span a {
        outline-color: -webkit-focus-ring-color;
        outline-style: auto
    }
}

@media only screen {
    .switch-toggle input {
        position: absolute;
        left: 0;
        opacity: 0
    }
    .switch-toggle input+label {
        position: relative;
        z-index: 2;
        display: block;
        float: left;
        padding: 0 .5em;
        margin: 0;
        text-align: center
    }
    .switch-toggle a {
        position: absolute;
        top: 0;
        left: 0;
        padding: 0;
        z-index: 1;
        width: 10px;
        height: 100%
    }
    .switch-toggle label:nth-child(2):nth-last-child(4),
    .switch-toggle label:nth-child(2):nth-last-child(4)~a,
    .switch-toggle label:nth-child(2):nth-last-child(4)~label {
        width: 50%
    }
    .switch-toggle label:nth-child(2):nth-last-child(4)~input:checked:nth-child(3)+label~a {
        left: 50%
    }
    .switch-toggle label:nth-child(2):nth-last-child(6),
    .switch-toggle label:nth-child(2):nth-last-child(6)~a,
    .switch-toggle label:nth-child(2):nth-last-child(6)~label {
        width: 33.33%
    }
    .switch-toggle label:nth-child(2):nth-last-child(6)~input:checked:nth-child(3)+label~a {
        left: 33.33%
    }
    .switch-toggle label:nth-child(2):nth-last-child(6)~input:checked:nth-child(5)+label~a {
        left: 66.66%
    }
    .switch-toggle label:nth-child(2):nth-last-child(8),
    .switch-toggle label:nth-child(2):nth-last-child(8)~a,
    .switch-toggle label:nth-child(2):nth-last-child(8)~label {
        width: 25%
    }
    .switch-toggle label:nth-child(2):nth-last-child(8)~input:checked:nth-child(3)+label~a {
        left: 25%
    }
    .switch-toggle label:nth-child(2):nth-last-child(8)~input:checked:nth-child(5)+label~a {
        left: 50%
    }
    .switch-toggle label:nth-child(2):nth-last-child(8)~input:checked:nth-child(7)+label~a {
        left: 75%
    }
    .switch-toggle label:nth-child(2):nth-last-child(10),
    .switch-toggle label:nth-child(2):nth-last-child(10)~a,
    .switch-toggle label:nth-child(2):nth-last-child(10)~label {
        width: 20%
    }
    .switch-toggle label:nth-child(2):nth-last-child(10)~input:checked:nth-child(3)+label~a {
        left: 20%
    }
    .switch-toggle label:nth-child(2):nth-last-child(10)~input:checked:nth-child(5)+label~a {
        left: 40%
    }
    .switch-toggle label:nth-child(2):nth-last-child(10)~input:checked:nth-child(7)+label~a {
        left: 60%
    }
    .switch-toggle label:nth-child(2):nth-last-child(10)~input:checked:nth-child(9)+label~a {
        left: 80%
    }
    .switch-toggle label:nth-child(2):nth-last-child(12),
    .switch-toggle label:nth-child(2):nth-last-child(12)~a,
    .switch-toggle label:nth-child(2):nth-last-child(12)~label {
        width: 16.6%
    }
    .switch-toggle label:nth-child(2):nth-last-child(12)~input:checked:nth-child(3)+label~a {
        left: 16.6%
    }
    .switch-toggle label:nth-child(2):nth-last-child(12)~input:checked:nth-child(5)+label~a {
        left: 33.2%
    }
    .switch-toggle label:nth-child(2):nth-last-child(12)~input:checked:nth-child(7)+label~a {
        left: 49.8%
    }
    .switch-toggle label:nth-child(2):nth-last-child(12)~input:checked:nth-child(9)+label~a {
        left: 66.4%
    }
    .switch-toggle label:nth-child(2):nth-last-child(12)~input:checked:nth-child(11)+label~a {
        left: 83%
    }
    .switch-light.switch-candy>span,
    .switch-toggle.switch-candy {
        background-color: #2d3035;
        border-radius: 3px;
        box-shadow: inset 0 2px 6px rgba(0, 0, 0, .3), 0 1px 0 rgba(255, 255, 255, .2)
    }
    .switch-light.switch-candy input:checked~span span:first-child,
    .switch-light.switch-candy span span,
    .switch-toggle.switch-candy label {
        color: #fff;
        font-weight: 700;
        text-align: center;
        text-shadow: 1px 1px 1px #191b1e
    }
    .switch-candy input:checked+label,
    .switch-light.switch-candy input:checked~span span:nth-child(2),
    .switch-light.switch-candy input~span span:first-child {
        color: #333;
        text-shadow: 0 1px 0 rgba(255, 255, 255, .5)
    }
    .switch-candy a {
        border: 1px solid #333;
        border-radius: 3px;
        box-shadow: 0 1px 1px rgba(0, 0, 0, .2), inset 0 1px 1px rgba(255, 255, 255, .45);
        background-color: #70c66b;
        background-image: linear-gradient(rgba(255, 255, 255, .2), transparent)
    }
    .switch-candy-blue a {
        background-color: #38a3d4
    }
    .switch-candy-yellow a {
        background-color: #f5e560
    }
    .switch-ios.switch-light span span {
        color: #888b92
    }
    .switch-ios.switch-light a {
        left: 0;
        top: 0;
        width: 2em;
        height: 2em;
        background-color: #fff;
        border-radius: 100%;
        border: .25em solid #d8d9db;
        transition: all .2s ease-out
    }
    .switch-ios.switch-light>span {
        display: block;
        width: 100%;
        height: 2em;
        background-color: #d8d9db;
        border-radius: 1.75em;
        transition: all .4s ease-out
    }
    .switch-ios.switch-light>span span {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        opacity: 0;
        line-height: 1.875em;
        vertical-align: middle;
        transition: all .2s ease-out
    }
    .switch-ios.switch-light>span span:first-of-type {
        opacity: 1;
        padding-left: 1.875em
    }
    .switch-ios.switch-light>span span:last-of-type {
        padding-right: 1.875em
    }
    .switch-ios.switch-light input:checked~span a {
        left: 100%;
        border-color: #4bd865;
        margin-left: -2em
    }
    .switch-ios.switch-light input:checked~span {
        border-color: #4bd865;
        box-shadow: inset 0 0 0 30px #4bd865
    }
    .switch-ios.switch-light input:checked~span span:first-of-type {
        opacity: 0
    }
    .switch-ios.switch-light input:checked~span span:last-of-type {
        opacity: 1;
        color: #fff
    }
    .switch-ios.switch-toggle {
        background-color: #d8d9db;
        border-radius: 30px;
        box-shadow: inset rgba(0, 0, 0, .1) 0 1px 0
    }
    .switch-ios.switch-toggle a {
        background-color: #4bd865;
        border: .125em solid #d8d9db;
        border-radius: 1.75em;
        transition: all .12s ease-out
    }
    .switch-ios.switch-toggle label {
        height: 2.4em;
        color: #888b92;
        line-height: 2.4em;
        vertical-align: middle
    }
    .switch-ios input:checked+label {
        color: #3e4043
    }
    .switch-light.switch-holo>span,
    .switch-toggle.switch-holo {
        background-color: #464747;
        border-radius: 1px;
        box-shadow: inset rgba(0, 0, 0, .1) 0 1px 0;
        color: #fff;
        text-transform: uppercase
    }
    .switch-holo label {
        color: #fff
    }
    .switch-holo>span span {
        opacity: 0;
        transition: all .1s
    }
    .switch-holo>span span:first-of-type {
        opacity: 1
    }
    .switch-holo label,
    .switch-holo>span span {
        font-size: 85%;
        line-height: 2.15625em
    }
    .switch-holo a {
        background-color: #666;
        border-radius: 1px;
        box-shadow: inset rgba(255, 255, 255, .2) 0 1px 0, inset rgba(0, 0, 0, .3) 0 -1px 0
    }
    .switch-holo.switch-light input:checked~span a {
        background-color: #0e88b1
    }
    .switch-holo.switch-light input:checked~span span:first-of-type {
        opacity: 0
    }
    .switch-holo.switch-light input:checked~span span:last-of-type {
        opacity: 1
    }
    .switch-light.switch-material a {
        top: -.1875em;
        width: 1.75em;
        height: 1.75em;
        border-radius: 50%;
        background: #fafafa;
        box-shadow: 0 .125em .125em 0 rgba(0, 0, 0, .14), 0 .1875em .125em -.125em rgba(0, 0, 0, .2), 0 .125em .25em 0 rgba(0, 0, 0, .12);
        transition: right .28s cubic-bezier(.4, 0, .2, 1)
    }
    .switch-material.switch-light {
        overflow: visible
    }
    .switch-material.switch-light::after {
        clear: both;
        content: '';
        display: table
    }
    .switch-material.switch-light>span {
        overflow: visible;
        position: relative;
        top: .1875em;
        width: 3.25em;
        height: 1.5em;
        min-height: auto;
        border-radius: 1em;
        background: rgba(0, 0, 0, .26)
    }
    .switch-material.switch-light span span {
        position: absolute;
        clip: rect(0 0 0 0)
    }
    .switch-material.switch-light input:checked~span a {
        right: 0;
        background: #3f51b5;
        box-shadow: 0 .1875em .25em 0 rgba(0, 0, 0, .14), 0 .1875em .1875em -.125em rgba(0, 0, 0, .2), 0 .0625em .375em 0 rgba(0, 0, 0, .12)
    }
    .switch-material.switch-light input:checked~span {
        background: rgba(63, 81, 181, .5)
    }
    .switch-toggle.switch-material {
        overflow: visible
    }
    .switch-toggle.switch-material::after {
        clear: both;
        content: '';
        display: table
    }
    .switch-toggle.switch-material a {
        top: 48%;
        width: .375em !important;
        height: .375em;
        margin-left: .25em;
        background: #3f51b5;
        border-radius: 100%;
        transform: translateY(-50%);
        transition: transform .4s ease-in
    }
    .switch-toggle.switch-material label {
        color: rgba(0, 0, 0, .54);
        font-size: 1em
    }
    .switch-toggle.switch-material label:before {
        content: '';
        position: absolute;
        top: 48%;
        left: 0;
        display: block;
        width: .875em;
        height: .875em;
        border-radius: 100%;
        border: .125em solid rgba(0, 0, 0, .54);
        transform: translateY(-50%)
    }
    .switch-toggle.switch-material input:checked+label:before {
        border-color: #3f51b5
    }
    .switch-light.switch-material>span:after,
    .switch-light.switch-material>span:before,
    .switch-toggle.switch-material label:after {
        content: '';
        position: absolute;
        top: 0;
        left: 0;
        z-index: 3;
        display: block;
        width: 4em;
        height: 4em;
        border-radius: 100%;
        background: #3f51b5;
        opacity: .4;
        margin-left: -1.25em;
        margin-top: -1.25em;
        transform: scale(0);
        transition: opacity .4s ease-in
    }
    .switch-light.switch-material>span:after {
        left: auto;
        right: 0;
        margin-left: 0;
        margin-right: -1.25em
    }
    .switch-toggle.switch-material label:after {
        width: 3.25em;
        height: 3.25em;
        margin-top: -.75em
    }
    @keyframes materialRipple {
        0% {
            transform: scale(0)
        }
        20% {
            transform: scale(1)
        }
        100% {
            opacity: 0;
            transform: scale(1)
        }
    }
    .switch-material.switch-light input:checked~span:before,
    .switch-material.switch-light input:not(:checked)~span:after,
    .switch-toggle.switch-material input:checked+label:after {
        animation: materialRipple .4s ease-in
    }
    .switch-light.switch-material.switch-light input~span:after,
    .switch-light.switch-material.switch-light input~span:before,
    .switch-material.switch-toggle input+label:after {
        visibility: hidden
    }
    .switch-light.switch-material.switch-light input:focus:checked~span:before,
    .switch-light.switch-material.switch-light input:focus:not(:checked)~span:after,
    .switch-material.switch-toggle input:focus:checked+label:after {
        visibility: visible
    }
}

@media only screen and (-webkit-max-device-pixel-ratio:2) and (max-device-width:80em) {
    .switch-light,
    .switch-toggle {
        -webkit-animation: webkitSiblingBugfix infinite 1s
    }
}

@-webkit-keyframes webkitSiblingBugfix {
    from {
        -webkit-transform: translate3d(0, 0, 0)
    }
    to {
        -webkit-transform: translate3d(0, 0, 0)
    }
}
