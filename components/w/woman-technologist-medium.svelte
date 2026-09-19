<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iqrRyTh)" class="lp-jspbxv"/><path fill="url(#iqexxae)" class="a_spo2cop"/><path fill="url(#ihQrDwX)" class="ax3t7fbst"/><path fill="url(#iNXhUee)" class="ax3t7fbst"/><path class="jki7tzdcu"/><path fill="url(#ia3Jeib)" class="td7qnxbmr"/><path fill="url(#ixcotec)" class="td7qnxbmr"/><path fill="url(#iRI2yhd)" class="g3ux3cbys"/><path fill="url(#ihnjaeb)" class="ny9_xhbeh"/><g filter="url(#iJCr8ub)"><path fill="url(#iItdqFb)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#iDJm0Sb)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#i0lnGvd)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#iDhcBkd)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#ipogSmd)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#iXs5VMe)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#irOp5ue)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#ipg4wwe)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#i87OA0b)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#iRYSywc)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#iVDUBsc)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#ioAht7b)" clip-rule="evenodd" class="bi4mzcbhr"/></g><g filter="url(#ifacYQb)"><path fill="url(#iBA6oQT)" class="glnfjzbdq"/></g><path fill="url(#iitTHIc)" class="glnfjzbdq"/><g filter="url(#imu19cd)"><path fill="url(#iu568uU)" class="kmbgvqb8x"/><path fill="url(#i0gmwRe)" class="kmbgvqb8x"/></g><g filter="url(#iROP23c)"><path class="tadf2zbsn"/><path fill="url(#ivTECie)" class="j9z76nbfg"/></g><g filter="url(#izoMsfd)"><path class="u4-z14ojq"/><path fill="url(#iVtpa5b)" class="eur0b6bpq"/></g><g filter="url(#iDWSQpg)"><path fill="url(#iK84J4c)" class="qdx0jsipi"/><path fill="url(#iz3MPmc)" class="qdx0jsipi"/><path fill="url(#icZg1ud)" class="qdx0jsipi"/><path fill="url(#iME9ULc)" class="qdx0jsipi"/><path fill="url(#i06kbib)" class="qdx0jsipi"/><path fill="url(#iK2PX7b)" class="qdx0jsipi"/><path fill="url(#iE4ZRId)" class="qdx0jsipi"/><path fill="url(#i949Fwd)" class="qdx0jsipi"/></g><path fill="url(#iYhzhbb)" class="qdx0jsipi"/><g filter="url(#i7AtTQb)"><path class="ug_4b754r"/></g><g filter="url(#iEVGHlc)"><path class="xzg4h5kta"/><path fill="url(#id9LcFb)" class="vrruugv9e"/><path fill="url(#ilktzpe)" class="vrruugv9e"/><path fill="url(#iPUFvce)" class="vrruugv9e"/><path fill="url(#inUdvsK)" class="vrruugv9e"/></g><path fill="url(#ilSZB1d)" class="vrruugv9e"/><path fill="url(#iskK9vb)" class="vrruugv9e"/><path stroke="url(#iFanWTd)" class="b-l6lqbfm"/><g filter="url(#i6lzEvc)"><path class="jqu9_pcww"/></g><g filter="url(#i6mYIRJ)"><path class="khpnv-b-p"/></g><g filter="url(#i8M1KWb)"><path class="dc3pzb5bv"/></g><g filter="url(#isRj97c)"><path clip-rule="evenodd" class="s46oq0c_s"/></g><path class="uf5rerbdy"/><path fill="url(#iE8oPbX)" class="sy_z82uvd"/><path class="jo8lxfo6c"/><g filter="url(#iMfhHuc)"><path class="segtjobkz"/><path fill="url(#iNO0awb)" class="zhb5rly-q"/></g><g filter="url(#ijL3enc)"><path fill="url(#ieaxaTb)" class="n3eifgatt"/></g><path class="i6bji0ert"/><path fill="url(#iortVcX)" class="r51qdgb9u"/><path class="ebv6t9bbq"/><g filter="url(#iFyHYIe)"><path fill="url(#iJg10Sc)" class="p3xkpoqcr"/></g><g filter="url(#iKQ68XE)"><ellipse transform="rotate(-27.914 13.547 9.816)" class="pdyfmt2wz"/><ellipse fill="url(#iBTecCL)" transform="rotate(-27.914 13.547 9.816)" class="w2q6f6-7d"/></g><g filter="url(#iH4SwTc)"><path class="pa5ynsbhr"/></g><g filter="url(#izsAfxe)"><path class="wns61wbig"/></g><g filter="url(#iEgLDEb)"><path class="k27mj0pgu"/><path fill="url(#iJo9Dcd)" class="ncz3x3yii"/><path fill="url(#ie1kOjd)" class="ncz3x3yii"/></g><g filter="url(#imyOohv)"><path class="rzgqoacdf"/><path fill="url(#inGB9pC)" class="ttb9dxbfy"/><path fill="url(#iOHSgxb)" class="ttb9dxbfy"/></g><g filter="url(#iCwwmce)"><path stroke="url(#ixqpveb)" class="zpok88b9y"/></g><g filter="url(#inM7f9k)"><path class="lx37_05kq"/></g><g filter="url(#iXQLEAd)"><path fill="url(#iHXaVce)" class="jsqgobbht"/><path fill="url(#i2BUj5L)" class="jsqgobbht"/><path fill="url(#iqtSqJd)" class="jsqgobbht"/><path fill="url(#iNN1SaK)" class="jsqgobbht"/><path fill="url(#irzSjbb)" class="jsqgobbht"/><path fill="url(#ihI2zKe)" class="jsqgobbht"/></g><path fill="url(#ixwQhto)" class="ppwrykbzp"/><path fill="url(#i8N6NDd)" class="ppwrykbzp"/><path fill="url(#ilcEH9d)" class="ppwrykbzp"/><path fill="url(#iKDpaee)" class="ppwrykbzp"/><path fill="url(#i2FoUFP)" class="ppwrykbzp"/><path fill="url(#iWis4Qd)" class="w6exmsbsa"/><defs><radialGradient id="ihQrDwX" cx="0" cy="0" r="1" gradientTransform="matrix(2.80769 -1.3591 1.47615 3.04949 2.747 30.02)" gradientUnits="userSpaceOnUse"><stop offset=".406" class="mom0z_ble"/><stop offset="1" class="ofcsa759z"/></radialGradient><radialGradient id="iNXhUee" cx="0" cy="0" r="1" gradientTransform="rotate(177.157 2.332 14.994)scale(3.35044 4.79049)" gradientUnits="userSpaceOnUse"><stop offset=".764" class="r0k1w-u4i"/><stop offset=".927" class="lmanndb2z"/></radialGradient><radialGradient id="ia3Jeib" cx="0" cy="0" r="1" gradientTransform="matrix(5.64062 -3.71875 1.03844 1.57511 27.091 30.119)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="purgp5b3s"/><stop offset="1" class="tizq1n0kf"/></radialGradient><radialGradient id="iDJm0Sb" cx="0" cy="0" r="1" gradientTransform="matrix(-.60337 4.55908 -5.69522 -.75373 15.698 13.008)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="w9gpkna4y"/><stop offset="1" class="xvq3mubqy"/></radialGradient><radialGradient id="i0lnGvd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 12.883 13.278)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="u3fmvdnwh"/><stop offset="1" class="ysga7wb0w"/></radialGradient><radialGradient id="iDhcBkd" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.927 8.121)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="jo-m975mj"/><stop offset="1" class="ecm2ecc2d"/></radialGradient><radialGradient id="ipogSmd" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.364 7.606)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ksj-40n4x"/><stop offset="1" class="qkj18_koj"/></radialGradient><radialGradient id="iXs5VMe" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 4.212 11.555)scale(2.95399 4.10059)" gradientUnits="userSpaceOnUse"><stop class="bk_mrebvc"/><stop offset="1" class="o57gz703y"/></radialGradient><radialGradient id="irOp5ue" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.979 6.786)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="g2m4aac5s"/><stop offset="1" class="tulkzacvs"/></radialGradient><radialGradient id="ipg4wwe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.84482 23.51 9.657)" gradientUnits="userSpaceOnUse"><stop class="ii82yjbfl"/><stop offset="1" class="tobrp8lrd"/></radialGradient><radialGradient id="i87OA0b" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.648 7.948)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="gto3tpbjl"/><stop offset="1" class="k8ni71bqd"/></radialGradient><radialGradient id="iRYSywc" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 12.95 -3.804)scale(2.80034 2.21491)" gradientUnits="userSpaceOnUse"><stop class="j6tbtfb5n"/><stop offset="1" class="u7ezkxzae"/></radialGradient><radialGradient id="iVDUBsc" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 9.858 9.621)" gradientUnits="userSpaceOnUse"><stop class="r4e237cot"/><stop offset="1" class="ktpt3tb_i"/></radialGradient><radialGradient id="ioAht7b" cx="0" cy="0" r="1" gradientTransform="rotate(-102.748 14.14 -3.95)scale(3.79787 1.37073)" gradientUnits="userSpaceOnUse"><stop class="fyy3crxae"/><stop offset="1" class="x7431zb1g"/></radialGradient><radialGradient id="iitTHIc" cx="0" cy="0" r="1" gradientTransform="matrix(-.6537 -1.20346 1.36368 -.74073 10.921 12.118)" gradientUnits="userSpaceOnUse"><stop class="wlzou1bho"/><stop offset="1" class="muarw1mje"/></radialGradient><radialGradient id="iu568uU" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.04 10.948)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="xqzyuky4n"/><stop offset="1" class="yiz6fvgdb"/></radialGradient><radialGradient id="i0gmwRe" cx="0" cy="0" r="1" gradientTransform="matrix(1.20681 0 0 .5196 20.945 8.802)" gradientUnits="userSpaceOnUse"><stop class="v4cuahbfk"/><stop offset="1" class="ame5l9u0o"/></radialGradient><radialGradient id="ivTECie" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.392 10.62)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="j_jb06m8v"/><stop offset="1" class="t9v208shd"/></radialGradient><radialGradient id="iVtpa5b" cx="0" cy="0" r="1" gradientTransform="rotate(180 5.7 5.254)scale(1.05596)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="w5re42dqy"/><stop offset="1" class="w4wkyodwa"/></radialGradient><radialGradient id="iK84J4c" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 8.336 7.055)scale(7.16175 9.58588)" gradientUnits="userSpaceOnUse"><stop class="ox3481l0h"/><stop offset="1" class="l65mx1yct"/></radialGradient><radialGradient id="iz3MPmc" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 7.847 7.302)scale(2.38203 1.65881)" gradientUnits="userSpaceOnUse"><stop class="vw42v6b3v"/><stop offset="1" class="v5m4qhb2r"/></radialGradient><radialGradient id="icZg1ud" cx="0" cy="0" r="1" gradientTransform="matrix(1.28915 -3.92836 4.98436 1.6357 13.838 16.478)" gradientUnits="userSpaceOnUse"><stop class="hl813wbpa"/><stop offset="1" class="a21bmlbcx"/></radialGradient><radialGradient id="iME9ULc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.0625 -10.078 0 16 9.222)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="epv7lyz4c"/><stop offset=".907" class="if2p0wt7d"/></radialGradient><radialGradient id="i06kbib" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.336 6.716)scale(7.03739 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="qh0bdqbav"/><stop offset="1" class="dt7ct4boy"/></radialGradient><radialGradient id="iK2PX7b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.301 9.552)" gradientUnits="userSpaceOnUse"><stop class="azt-9rbtm"/><stop offset="1" class="ci16jsbol"/></radialGradient><radialGradient id="iE4ZRId" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 13.924 9.324)" gradientUnits="userSpaceOnUse"><stop class="zemyxxbjg"/><stop offset="1" class="k1zv-ubmt"/></radialGradient><radialGradient id="i949Fwd" cx="0" cy="0" r="1" gradientTransform="matrix(-.87016 3.22674 -2.58193 -.69627 17.383 7.236)" gradientUnits="userSpaceOnUse"><stop class="aotu-xwil"/><stop offset="1" class="izc7dk1pl"/></radialGradient><radialGradient id="iYhzhbb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 21.096 11.04)" gradientUnits="userSpaceOnUse"><stop class="fyxppic9g"/><stop offset="1" class="kq5b787yl"/></radialGradient><radialGradient id="id9LcFb" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 16.784 11.767)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="ab1vgh_ru"/><stop offset="1" class="f80hfjhpj"/></radialGradient><radialGradient id="inUdvsK" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 16.545 11.979)" gradientUnits="userSpaceOnUse"><stop class="hjp773b9j"/><stop offset="1" class="wh0vrhbzi"/></radialGradient><radialGradient id="iskK9vb" cx="0" cy="0" r="1" gradientTransform="rotate(145.529 6.423 8.232)scale(1.66326 1.99898)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="xs9vt_bzp"/><stop offset="1" class="p13423bzd"/><stop offset="1" class="jjvamgr7p"/></radialGradient><radialGradient id="iE8oPbX" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.182 9.911)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iNO0awb" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.954 9.995)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iortVcX" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.818 9.911)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iBTecCL" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.752 -1.595)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iJo9Dcd" cx="0" cy="0" r="1" gradientTransform="rotate(-65.391 11.24 -4.16)scale(3.03069 1.55043)" gradientUnits="userSpaceOnUse"><stop class="gaydocc3b"/><stop offset="1" class="o5ryhdc_j"/></radialGradient><radialGradient id="ie1kOjd" cx="0" cy="0" r="1" gradientTransform="matrix(1.14952 -1.97524 1.06043 .61714 12.05 6.81)" gradientUnits="userSpaceOnUse"><stop class="bkfqk3fbn"/><stop offset="1" class="hrqlkdbpd"/></radialGradient><radialGradient id="inGB9pC" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.143 6.922)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ukea7pdhy"/><stop offset="1" class="wuqjd3b5z"/></radialGradient><radialGradient id="iOHSgxb" cx="0" cy="0" r="1" gradientTransform="matrix(-.21033 1.3672 -2.94145 -.45252 16.21 2.953)" gradientUnits="userSpaceOnUse"><stop class="y3gk9pbvh"/><stop offset="1" class="j2p90_-bc"/><stop offset="1" class="ru9fl6bjc"/></radialGradient><radialGradient id="i2BUj5L" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.59705 13.2772 0 17.243 31.067)" gradientUnits="userSpaceOnUse"><stop offset=".027" class="o1-qqkidl"/><stop offset="1" class="q0dxfdmim"/></radialGradient><radialGradient id="ihI2zKe" cx="0" cy="0" r="1" gradientTransform="matrix(-.78125 .4375 -.4057 -.72446 26.696 16.66)" gradientUnits="userSpaceOnUse"><stop class="nonrr22es"/><stop offset=".724" class="jehi2ihjx"/></radialGradient><radialGradient id="iWis4Qd" cx="0" cy="0" r="1" gradientTransform="matrix(-.0957 .08008 -.11939 -.14269 17.371 21.824)" gradientUnits="userSpaceOnUse"><stop class="a-otvg7dq"/><stop offset="1" class="t_w5hobcp"/></radialGradient><linearGradient id="iqrRyTh" x1="8.815" x2="23.191" y1="15.318" y2="15.318" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iqexxae" x1="8.815" x2="23.191" y1="15.288" y2="15.288" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="ixcotec" x1="26.966" x2="27.302" y1="28.838" y2="28.838" gradientUnits="userSpaceOnUse"><stop class="l5rpyobus"/><stop offset="1" class="q1cl32x8o"/></linearGradient><linearGradient id="iRI2yhd" x1="10.918" x2="1.428" y1="24.003" y2="24.044" gradientUnits="userSpaceOnUse"><stop class="vuad6pb7r"/><stop offset="1" class="zaeth0b6d"/></linearGradient><linearGradient id="ihnjaeb" x1="22.998" x2="28.652" y1="24.02" y2="24.02" gradientUnits="userSpaceOnUse"><stop class="vuad6pb7r"/><stop offset="1" class="zaeth0b6d"/></linearGradient><linearGradient id="iItdqFb" x1="20.693" x2="14.559" y1="3.556" y2="14.317" gradientUnits="userSpaceOnUse"><stop class="ap760fb9g"/><stop offset="1" class="w1etxcbdz"/></linearGradient><linearGradient id="iBA6oQT" x1="9.705" x2="11.563" y1="10.596" y2="10.596" gradientUnits="userSpaceOnUse"><stop class="cg1k0hirj"/><stop offset="1" class="u6m78ac0i"/></linearGradient><linearGradient id="ilktzpe" x1="15.061" x2="16" y1="11.84" y2="11.84" gradientUnits="userSpaceOnUse"><stop class="hm31m3bmo"/><stop offset="1" class="vh12xwf7a"/></linearGradient><linearGradient id="iPUFvce" x1="16" x2="16" y1="12.547" y2="11.92" gradientUnits="userSpaceOnUse"><stop class="us3ue9b4r"/><stop offset="1" class="hxr-reb3g"/></linearGradient><linearGradient id="ilSZB1d" x1="16.078" x2="16.078" y1="12.613" y2="12.473" gradientUnits="userSpaceOnUse"><stop class="b576ppbxh"/><stop offset="1" class="a_xwx-nqh"/></linearGradient><linearGradient id="iFanWTd" x1="14.936" x2="15.397" y1="14.048" y2="13.336" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="ieaxaTb" x1="18.96" x2="18.646" y1="9.965" y2="10.159" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iJg10Sc" x1="14.562" x2="14.248" y1="9.965" y2="10.159" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ixqpveb" x1="12.891" x2="13.381" y1="3.556" y2="4.821" gradientUnits="userSpaceOnUse"><stop class="olrv_cchi"/><stop offset="1" class="lwhsndh-i"/></linearGradient><linearGradient id="iHXaVce" x1="7.493" x2="11.284" y1="19.754" y2="30.805" gradientUnits="userSpaceOnUse"><stop class="ux-m5bn7d"/><stop offset="1" class="l294t3zvi"/></linearGradient><linearGradient id="iqtSqJd" x1="16" x2="16" y1="16.02" y2="17.379" gradientUnits="userSpaceOnUse"><stop class="dmu1fh1sq"/><stop offset=".268" class="gzfhb8b1n"/><stop offset=".863" class="szjcm-w7x"/></linearGradient><linearGradient id="iNN1SaK" x1="5" x2="6.055" y1="24.254" y2="24.254" gradientUnits="userSpaceOnUse"><stop class="a61ap5b7j"/><stop offset="1" class="p9llu9bpa"/></linearGradient><linearGradient id="irzSjbb" x1="27" x2="25.524" y1="25.192" y2="25.192" gradientUnits="userSpaceOnUse"><stop offset=".174" class="yr342ibfl"/><stop offset="1" class="d9m_15bme"/></linearGradient><linearGradient id="ixwQhto" x1="17.977" x2="13.911" y1="23.099" y2="23.099" gradientUnits="userSpaceOnUse"><stop offset=".096" class="qufyc6r7b"/><stop offset=".13" class="xqmtwwbyq"/><stop offset=".165" class="k71v6_7um"/><stop offset="1" class="uem0lbchq"/></linearGradient><linearGradient id="i8N6NDd" x1="15.999" x2="15.999" y1="21.641" y2="23.196" gradientUnits="userSpaceOnUse"><stop class="w9bfwpbnq"/><stop offset="1" class="zt_ualb3u"/></linearGradient><linearGradient id="ilcEH9d" x1="15.999" x2="15.999" y1="21.641" y2="24.557" gradientUnits="userSpaceOnUse"><stop class="l17xqebtl"/><stop offset=".037" class="r1d3vkbxd"/><stop offset=".058" class="bowxt9bwr"/><stop offset=".097" class="g48yfbn9k"/></linearGradient><linearGradient id="iKDpaee" x1="14.444" x2="15.02" y1="23.122" y2="23.122" gradientUnits="userSpaceOnUse"><stop offset=".086" class="v1n2dlbml"/><stop offset=".663" class="ohv650iba"/></linearGradient><linearGradient id="i2FoUFP" x1="15.999" x2="15.999" y1="24.842" y2="24.168" gradientUnits="userSpaceOnUse"><stop offset=".507" class="qqk6g6zlh"/><stop offset=".736" class="auud8yb7i"/></linearGradient><filter id="iJCr8ub" width="15.268" height="15.768" x="8.491" y="1.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.133333 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1065"/></filter><filter id="ifacYQb" width="3.368" height="3.218" x="9.705" y="8.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1065"/></filter><filter id="imu19cd" width="3.218" height="3.468" x="19.218" y="8.649" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.34902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1065"/></filter><filter id="iROP23c" width="3.148" height="3.148" x="19.253" y="8.934" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1065" stdDeviation=".25"/></filter><filter id="izoMsfd" width="2.848" height="2.848" x="9.91" y="9.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1065" stdDeviation=".175"/></filter><filter id="iDWSQpg" width="10.191" height="11.127" x="10.905" y="5.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1065"/></filter><filter id="i7AtTQb" width="2.877" height="3.682" x="14.399" y="9.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1065" stdDeviation=".25"/></filter><filter id="iEVGHlc" width="2.377" height="3.182" x="14.811" y="9.615" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1065" stdDeviation=".125"/></filter><filter id="i6lzEvc" width="3.001" height="1.285" x="16.942" y="9.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.0705882 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1065"/></filter><filter id="i6mYIRJ" width="3.001" height="1.285" x="12.057" y="9.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1065"/></filter><filter id="i8M1KWb" width="2.453" height="1.091" x="12.192" y="7.68" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1065"/></filter><filter id="isRj97c" width="2.453" height="1.091" x="17.609" y="7.68" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1065"/></filter><filter id="iMfhHuc" width=".787" height=".696" x="17.448" y="9.472" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1065" stdDeviation=".05"/></filter><filter id="ijL3enc" width=".891" height=".913" x="18.288" y="9.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1065" stdDeviation=".1"/></filter><filter id="iFyHYIe" width=".986" height="1.04" x="13.845" y="9.483" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1065" stdDeviation=".1"/></filter><filter id="iKQ68XE" width=".913" height=".705" x="13.09" y="9.463" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1065" stdDeviation=".05"/></filter><filter id="iH4SwTc" width="2.661" height="1.378" x="17.44" y="7.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1065" stdDeviation=".2"/></filter><filter id="izsAfxe" width="2.661" height="1.378" x="11.988" y="7.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1065" stdDeviation=".2"/></filter><filter id="iEgLDEb" width="4.312" height="4.613" x="9.646" y="3.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.286275 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1065"/><feGaussianBlur result="effect2_foregroundBlur_3_1065" stdDeviation=".2"/></filter><filter id="imyOohv" width="8.767" height="5.782" x="12.83" y="2.432" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.317647 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1065"/><feGaussianBlur result="effect2_foregroundBlur_3_1065" stdDeviation=".125"/></filter><filter id="iCwwmce" width="1.145" height="2.31" x="12.809" y="3.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1065" stdDeviation=".1"/></filter><filter id="inM7f9k" width="6.427" height="3.372" x="15.418" y="4.475" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1065" stdDeviation=".375"/></filter><filter id="iXQLEAd" width="22" height="14.1" x="5" y="16.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.670588 0 0 0 0 0.682353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1065"/></filter></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji:woman-technologist-medium" {...props}></Icon>
<style>
:global(.a_spo2cop) {
  d: path("M16.025 15.289h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

:global(.a_xwx-nqh) {
  stop-color: var(--svg-color--8f5269, #8F5269);
  stop-opacity: 0;
}

:global(.a-otvg7dq) {
  stop-color: var(--svg-color--806b97, #806B97);
}

:global(.a21bmlbcx) {
  stop-color: var(--svg-color--945a73, #945A73);
  stop-opacity: 0;
}

:global(.a61ap5b7j) {
  stop-color: var(--svg-color--9f93b2, #9F93B2);
}

:global(.ab1vgh_ru) {
  stop-color: var(--svg-color--cda38b, #CDA38B);
}

:global(.ame5l9u0o) {
  stop-color: var(--svg-color--906d53, #906D53);
  stop-opacity: 0;
}

:global(.aotu-xwil) {
  stop-color: var(--svg-color--ab8179, #AB8179);
}

:global(.ap760fb9g) {
  stop-color: var(--svg-color--6d524e, #6D524E);
}

:global(.auud8yb7i) {
  stop-color: var(--svg-color--4a3261, #4A3261);
  stop-opacity: 0;
}

:global(.ax3t7fbst) {
  d: path("M8.329 30.02q.004-.082.004-.163a3.138 3.138 0 1 0-6.271.162z");
}

:global(.azt-9rbtm) {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
}

:global(.b-l6lqbfm) {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.602 13.031a.204.204 0 0 0-.248.043a.196.196 0 0 0-.02.248a1.982 1.982 0 0 0 3.333 0a.2.2 0 0 0-.022-.25a.205.205 0 0 0-.246-.041A3 3 0 0 1 16 13.37a3 3 0 0 1-1.398-.339Z");
}

:global(.b576ppbxh) {
  stop-color: var(--svg-color--8f5269, #8F5269);
}

:global(.bi4mzcbhr) {
  fill-rule: evenodd;
  d: path("M23.185 11.918c.213-.435.324-.92.324-1.427c0-.467-.096-.905-.268-1.305h.005a3 3 0 0 0-.281-.513l-.002-.003a3.24 3.24 0 0 1-.527-1.771v-.01a3.3 3.3 0 0 0-3.299-3.3a.54.54 0 0 1-.455-.232A3.3 3.3 0 0 0 16 1.98a3.3 3.3 0 0 0-2.682 1.377a.56.56 0 0 1-.455.233h-.085a3.3 3.3 0 0 0-3.214 3.3v.01a3.24 3.24 0 0 1-.527 1.77l-.002.004a3.3 3.3 0 0 0-.22 3.245c.07.142.07.314 0 .456A3.213 3.213 0 0 0 11.709 17h8.582a3.213 3.213 0 0 0 3.218-3.219c0-.506-.121-.981-.324-1.406a.51.51 0 0 1 0-.456m-12.26-2.672h-.012l1.198 2.355c.124 2.803 1.217 0 3.889 0s3.836 3.12 3.96.317l1.136-3.197c-.054-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.19-1.673a.264.264 0 0 0-.461.05l-.082.195a2.3 2.3 0 0 1-1.292 1.275c-.236.122-.79.49-.81 1.439l.01.306z");
}

:global(.bk_mrebvc) {
  stop-color: var(--svg-color--554543, #554543);
}

:global(.bkfqk3fbn) {
  stop-color: var(--svg-color--4b2839, #4B2839);
}

:global(.bowxt9bwr) {
  stop-color: var(--svg-color--6f5783, #6F5783);
}

:global(.cg1k0hirj) {
  stop-color: var(--svg-color--8d645f, #8D645F);
}

:global(.ci16jsbol) {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
  stop-opacity: 0;
}

:global(.ckw4b5bec) {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

:global(.d9m_15bme) {
  stop-color: var(--svg-color--a191b5, #A191B5);
  stop-opacity: 0;
}

:global(.dc3pzb5bv) {
  fill: var(--svg-color--432a28, #432A28);
  d: path("m12.602 8.73l-.004.003a.268.268 0 0 1-.276-.46h.002l.003-.003l.01-.005a2 2 0 0 1 .148-.077a3 3 0 0 1 .41-.162c.34-.108.815-.2 1.328-.109a.268.268 0 1 1-.093.528a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.434.182z");
}

:global(.dmu1fh1sq) {
  stop-color: var(--svg-color--beb0b0, #BEB0B0);
}

:global(.dt7ct4boy) {
  stop-color: var(--svg-color--9a7267, #9A7267);
}

:global(.e0-rnofaa) {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

:global(.ebv6t9bbq) {
  fill: var(--svg-color--000, #000);
  d: path("M14.327 10.327a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.235");
}

:global(.ecm2ecc2d) {
  stop-color: var(--svg-color--27141e, #27141E);
  stop-opacity: 0;
}

:global(.epv7lyz4c) {
  stop-color: var(--svg-color--9a6371, #9A6371);
  stop-opacity: 0;
}

:global(.eur0b6bpq) {
  d: path("M11.334 11.583a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

:global(.f80hfjhpj) {
  stop-color: var(--svg-color--cda38b, #CDA38B);
  stop-opacity: 0;
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.fyxppic9g) {
  stop-color: var(--svg-color--c0967a, #C0967A);
}

:global(.fyy3crxae) {
  stop-color: var(--svg-color--3e2125, #3E2125);
}

:global(.g2m4aac5s) {
  stop-color: var(--svg-color--6e5350, #6E5350);
}

:global(.g3ux3cbys) {
  d: path("M8.98 18.02a10.99 10.99 0 0 0-3.97 8.5l.02 3.5l4-.02z");
}

:global(.g48yfbn9k) {
  stop-color: var(--svg-color--5f447b, #5F447B);
  stop-opacity: 0;
}

:global(.gaydocc3b) {
  stop-color: var(--svg-color--5c4643, #5C4643);
}

:global(.glnfjzbdq) {
  d: path("M11.314 12.118a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.219");
}

:global(.gto3tpbjl) {
  stop-color: var(--svg-color--564544, #564544);
}

:global(.gzfhb8b1n) {
  stop-color: var(--svg-color--beb7c7, #BEB7C7);
}

:global(.h_j9u0wvt) {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

:global(.hjp773b9j) {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
}

:global(.hl813wbpa) {
  stop-color: var(--svg-color--945a73, #945A73);
}

:global(.hm31m3bmo) {
  stop-color: var(--svg-color--875f54, #875F54);
}

:global(.hrqlkdbpd) {
  stop-color: var(--svg-color--4b2839, #4B2839);
  stop-opacity: 0;
}

:global(.hxr-reb3g) {
  stop-color: var(--svg-color--995c76, #995C76);
  stop-opacity: 0;
}

:global(.i6bji0ert) {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.61 9.163c-.654 0-1.206.45-1.356 1.058a.275.275 0 0 0 .268.341h2.231a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.37-1.127");
}

:global(.if2p0wt7d) {
  stop-color: var(--svg-color--945278, #945278);
}

:global(.ii82yjbfl) {
  stop-color: var(--svg-color--604947, #604947);
}

:global(.izc7dk1pl) {
  stop-color: var(--svg-color--ab8179, #AB8179);
  stop-opacity: 0;
}

:global(.j_jb06m8v) {
  stop-color: var(--svg-color--a26d62, #A26D62);
  stop-opacity: 0;
}

:global(.j2p90_-bc) {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

:global(.j6tbtfb5n) {
  stop-color: var(--svg-color--5f4846, #5F4846);
}

:global(.j9z76nbfg) {
  d: path("M20.827 11.583a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

:global(.jehi2ihjx) {
  stop-color: var(--svg-color--e5dff1, #E5DFF1);
  stop-opacity: 0;
}

:global(.jjvamgr7p) {
  stop-color: var(--svg-color--815553, #815553);
}

:global(.jki7tzdcu) {
  fill: var(--svg-color--bd977b, #BD977B);
  d: path("M29.938 30.02q.005-.082.005-.163a3.138 3.138 0 1 0-6.272.162z");
}

:global(.jo-m975mj) {
  stop-color: var(--svg-color--27141e, #27141E);
}

:global(.jo8lxfo6c) {
  fill: var(--svg-color--000, #000);
  d: path("M17.673 10.327c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

:global(.jqu9_pcww) {
  fill: var(--svg-color--2f2c32, #2F2C32);
  d: path("M17.142 9.94c.266-.467.67-.836 1.538-.836c.38 0 .747.105 1.072.369c.27.217.233.495.025.599l-.556.317c-.652-.21-1.373-.239-2.079-.45");
}

:global(.jsqgobbht) {
  d: path("M26.03 16.02H5.97a.97.97 0 0 0-.97.97v13.03h22V16.99a.97.97 0 0 0-.97-.97");
}

:global(.k1zv-ubmt) {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
  stop-opacity: 0;
}

:global(.k27mj0pgu) {
  fill: var(--svg-color--49302e, #49302E);
  d: path("M10.93 4.52c.567-.599 1.637-.6 2.132-.51l.396 1.29c-.253-.039-.296-.001-.486.183c-.137 1.093-1.376 1.757-2.886 2.197c-.148-1.492.109-2.38.845-3.16");
}

:global(.k71v6_7um) {
  stop-color: var(--svg-color--51366c, #51366C);
}

:global(.k8ni71bqd) {
  stop-color: var(--svg-color--564544, #564544);
  stop-opacity: 0;
}

:global(.khpnv-b-p) {
  fill: var(--svg-color--27232a, #27232A);
  d: path("M14.858 9.94c-.265-.467-.669-.836-1.537-.836c-.38 0-.747.105-1.073.369c-.269.217-.233.495-.025.599l.556.317c.652-.21 1.373-.239 2.08-.45");
}

:global(.kmbgvqb8x) {
  d: path("M20.827 12.118a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.219");
}

:global(.kq5b787yl) {
  stop-color: var(--svg-color--c0967a, #C0967A);
  stop-opacity: 0;
}

:global(.ksj-40n4x) {
  stop-color: var(--svg-color--230c14, #230C14);
}

:global(.kt__1405u) {
  stop-color: var(--svg-color--ccc, #CCC);
}

:global(.ktpt3tb_i) {
  stop-color: var(--svg-color--56413d, #56413D);
  stop-opacity: 0;
}

:global(.l17xqebtl) {
  stop-color: var(--svg-color--594170, #594170);
}

:global(.l294t3zvi) {
  stop-color: var(--svg-color--847498, #847498);
}

:global(.l5rpyobus) {
  stop-color: var(--svg-color--b38f78, #B38F78);
}

:global(.l65mx1yct) {
  stop-color: var(--svg-color--946568, #946568);
}

:global(.l7c47o-wr) {
  stop-color: var(--svg-color--664944, #664944);
}

:global(.lhxedz0io) {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

:global(.lmanndb2z) {
  stop-color: var(--svg-color--ba907d, #BA907D);
}

:global(.lp-jspbxv) {
  d: path("M16.355 15.289c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

:global(.lwhsndh-i) {
  stop-color: var(--svg-color--452531, #452531);
}

:global(.lx37_05kq) {
  fill: var(--svg-color--664a4a, #664A4A);
  d: path("m18.406 6.328l-1.425.262a.688.688 0 1 1-.125-1.365h2.34c1.385 0 1.843 1.395 1.9 1.872a3.15 3.15 0 0 0-2.69-.77");
}

:global(.mbk9t98yd) {
  stop-color: var(--svg-color--694b43, #694B43);
}

:global(.mom0z_ble) {
  stop-color: var(--svg-color--b28a78, #B28A78);
}

:global(.muarw1mje) {
  stop-color: var(--svg-color--814e62, #814E62);
  stop-opacity: 0;
}

:global(.n3eifgatt) {
  d: path("M18.98 10.21a.84.84 0 0 0-.232-.463l-.26.285l.117.228z");
}

:global(.ncz3x3yii) {
  d: path("M10.93 4.52c.567-.599 1.637-.6 2.132-.51l.396 1.29c-.253-.039-.296-.001-.486.183c-.137 1.093-1.376 1.757-2.886 2.197c-.148-1.492.109-2.38.845-3.16");
}

:global(.nonrr22es) {
  stop-color: var(--svg-color--e5dff1, #E5DFF1);
}

:global(.ny9_xhbeh) {
  d: path("M23 18.03v11.98h4v-3.5c0-3.41-1.56-6.46-4-8.48");
}

:global(.o1-qqkidl) {
  stop-color: var(--svg-color--78698c, #78698C);
}

:global(.o57gz703y) {
  stop-color: var(--svg-color--554543, #554543);
  stop-opacity: 0;
}

:global(.o5ryhdc_j) {
  stop-color: var(--svg-color--5c4643, #5C4643);
  stop-opacity: 0;
}

:global(.od4qh9blv) {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

:global(.ofcsa759z) {
  stop-color: var(--svg-color--8a6959, #8A6959);
}

:global(.ohv650iba) {
  stop-color: var(--svg-color--52376c, #52376C);
  stop-opacity: 0;
}

:global(.olrv_cchi) {
  stop-color: var(--svg-color--361f1f, #361F1F);
}

:global(.ox3481l0h) {
  stop-color: var(--svg-color--c79980, #C79980);
}

:global(.p13423bzd) {
  stop-color: var(--svg-color--693b40, #693B40);
}

:global(.p3xkpoqcr) {
  d: path("M14.631 10.222c0-.288-.234-.48-.298-.539l-.288.28l.178.36z");
}

:global(.p9llu9bpa) {
  stop-color: var(--svg-color--9f93b2, #9F93B2);
  stop-opacity: 0;
}

:global(.pa5ynsbhr) {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.94 8.136c.322-.079 1.124-.04 1.66.344");
}

:global(.pdyfmt2wz) {
  cx: 13.547px;
  cy: 9.816px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

:global(.pkjdwtbdo) {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

:global(.ppwrykbzp) {
  d: path("M14.444 21.89a.25.25 0 0 1 .25-.25h2.61a.25.25 0 0 1 .25.25v2.417a.25.25 0 0 1-.25.25h-2.61a.25.25 0 0 1-.25-.25z");
}

:global(.purgp5b3s) {
  stop-color: var(--svg-color--cca28f, #CCA28F);
}

:global(.q0dxfdmim) {
  stop-color: var(--svg-color--7a6b8e, #7A6B8E);
  stop-opacity: 0;
}

:global(.q1cl32x8o) {
  stop-color: var(--svg-color--b38f78, #B38F78);
  stop-opacity: 0;
}

:global(.qdx0jsipi) {
  d: path("M10.913 9.246h.012l-.01-.266l-.01-.306c.02-.949.574-1.316.81-1.438l.051-.02l.051-.021a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.05a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.087 1.136 1.332l-.12 3.073c-.122 2.803-2.311 4.684-4.982 4.684s-4.86-1.882-4.984-4.684z");
}

:global(.qh0bdqbav) {
  stop-color: var(--svg-color--9a7267, #9A7267);
  stop-opacity: 0;
}

:global(.qkj18_koj) {
  stop-color: var(--svg-color--230c14, #230C14);
  stop-opacity: 0;
}

:global(.qqk6g6zlh) {
  stop-color: var(--svg-color--3d2555, #3D2555);
}

:global(.qufyc6r7b) {
  stop-color: var(--svg-color--56416b, #56416B);
}

:global(.qvv2y8bvl) {
  stop-color: var(--svg-color--804d49, #804D49);
}

:global(.r0k1w-u4i) {
  stop-color: var(--svg-color--ba907d, #BA907D);
  stop-opacity: 0;
}

:global(.r1d3vkbxd) {
  stop-color: var(--svg-color--6d5686, #6D5686);
}

:global(.r4e237cot) {
  stop-color: var(--svg-color--56413d, #56413D);
}

:global(.r51qdgb9u) {
  d: path("M13.816 9.434a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

:global(.ru9fl6bjc) {
  stop-color: var(--svg-color--634945, #634945);
  stop-opacity: 0;
}

:global(.rzgqoacdf) {
  fill: var(--svg-color--553836, #553836);
  d: path("M15.397 2.718c-1.133-.25-2.15.88-2.267 1.299c1.051 3.545 3.713 3.35 6.34 3.059c1.572-.175 1.743.542 1.877.888c0-3.933-3.344-4.67-5.922-5.24z");
}

:global(.s46oq0c_s) {
  fill: var(--svg-color--432a28, #432A28);
  fill-rule: evenodd;
  d: path("m19.732 8.273l-.138.23za.268.268 0 0 1-.275.46l-.005-.002a1 1 0 0 0-.113-.059a3 3 0 0 0-.342-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 1 1-.093-.528c.513-.09.988.001 1.328.11a3.3 3.3 0 0 1 .559.238l.009.005z");
}

:global(.segtjobkz) {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.119 9.623c.063.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.389-.051");
}

:global(.ssfga94sp) {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

:global(.sy_z82uvd) {
  d: path("M18.184 9.434a.893.893 0 0 1 .86 1.128H17.32a.896.896 0 0 1 .864-1.128");
}

:global(.szjcm-w7x) {
  stop-color: var(--svg-color--beb7c7, #BEB7C7);
  stop-opacity: 0;
}

:global(.t_w5hobcp) {
  stop-color: var(--svg-color--8d78a4, #8D78A4);
  stop-opacity: 0;
}

:global(.t-wcrfbaw) {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

:global(.t9v208shd) {
  stop-color: var(--svg-color--a26d62, #A26D62);
}

:global(.tadf2zbsn) {
  fill: var(--svg-color--b38574, #B38574);
  d: path("M20.827 11.583a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

:global(.td7qnxbmr) {
  d: path("M29.938 30.02q.005-.082.005-.163a3.138 3.138 0 1 0-6.272.162z");
}

:global(.tizq1n0kf) {
  stop-color: var(--svg-color--cca28f, #CCA28F);
  stop-opacity: 0;
}

:global(.tobrp8lrd) {
  stop-color: var(--svg-color--604947, #604947);
  stop-opacity: 0;
}

:global(.ttb9dxbfy) {
  d: path("M15.397 2.718c-1.133-.25-2.15.88-2.267 1.299c1.051 3.545 3.713 3.35 6.34 3.059c1.572-.175 1.743.542 1.877.888c0-3.933-3.344-4.67-5.922-5.24z");
}

:global(.tulkzacvs) {
  stop-color: var(--svg-color--6e5350, #6E5350);
  stop-opacity: 0;
}

:global(.u3fmvdnwh) {
  stop-color: var(--svg-color--25131c, #25131C);
}

:global(.u4-z14ojq) {
  fill: var(--svg-color--7e555a, #7E555A);
  d: path("M11.334 11.583a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

:global(.u6m78ac0i) {
  stop-color: var(--svg-color--604138, #604138);
}

:global(.u7ezkxzae) {
  stop-color: var(--svg-color--5f4846, #5F4846);
  stop-opacity: 0;
}

:global(.uem0lbchq) {
  stop-color: var(--svg-color--4f3568, #4F3568);
}

:global(.uf5rerbdy) {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.391 9.163c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.268.341h-2.23a.23.23 0 0 1-.228-.272c.126-.64.69-1.127 1.371-1.127");
}

:global(.ug_4b754r) {
  fill: var(--svg-color--88555f, #88555F);
  d: path("m15.608 10.286l-.684 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.377-.494-.377-.613 0");
}

:global(.ukea7pdhy) {
  stop-color: var(--svg-color--442534, #442534);
  stop-opacity: 0;
}

:global(.us3ue9b4r) {
  stop-color: var(--svg-color--995c76, #995C76);
}

:global(.ux-m5bn7d) {
  stop-color: var(--svg-color--ab9cbe, #AB9CBE);
}

:global(.v1n2dlbml) {
  stop-color: var(--svg-color--3b2b50, #3B2B50);
}

:global(.v4cuahbfk) {
  stop-color: var(--svg-color--906d53, #906D53);
}

:global(.v5m4qhb2r) {
  stop-color: var(--svg-color--c4967a, #C4967A);
  stop-opacity: 0;
}

:global(.vh12xwf7a) {
  stop-color: var(--svg-color--875f54, #875F54);
  stop-opacity: 0;
}

:global(.vrruugv9e) {
  d: path("m15.618 10.147l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.376-.646-.376-.765 0");
}

:global(.vuad6pb7r) {
  stop-color: var(--svg-color--1c1c1c, #1C1C1C);
}

:global(.vw42v6b3v) {
  stop-color: var(--svg-color--c4967a, #C4967A);
}

:global(.w1etxcbdz) {
  stop-color: var(--svg-color--2c1c24, #2C1C24);
}

:global(.w2q6f6-7d) {
  cx: 13.547px;
  cy: 9.816px;
  rx: 0.39px;
  ry: 0.197px;
}

:global(.w4wkyodwa) {
  stop-color: var(--svg-color--6c4640, #6C4640);
}

:global(.w5re42dqy) {
  stop-color: var(--svg-color--6c4640, #6C4640);
  stop-opacity: 0;
}

:global(.w6exmsbsa) {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M14.444 21.89a.25.25 0 0 1 .25-.25h2.61a.25.25 0 0 1 .25.25v2.417a.25.25 0 0 1-.25.25h-2.61a.25.25 0 0 1-.25-.25z");
}

:global(.w9bfwpbnq) {
  stop-color: var(--svg-color--60407f, #60407F);
}

:global(.w9gpkna4y) {
  stop-color: var(--svg-color--261326, #261326);
}

:global(.wh0vrhbzi) {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
  stop-opacity: 0;
}

:global(.wlzou1bho) {
  stop-color: var(--svg-color--814e62, #814E62);
}

:global(.wns61wbig) {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.149 8.136c-.323-.079-1.125-.04-1.661.344");
}

:global(.wuqjd3b5z) {
  stop-color: var(--svg-color--442534, #442534);
}

:global(.x7431zb1g) {
  stop-color: var(--svg-color--3e2125, #3E2125);
  stop-opacity: 0;
}

:global(.xqmtwwbyq) {
  stop-color: var(--svg-color--614c77, #614C77);
}

:global(.xqzyuky4n) {
  stop-color: var(--svg-color--b28279, #B28279);
}

:global(.xs9vt_bzp) {
  stop-color: var(--svg-color--815553, #815553);
  stop-opacity: 0;
}

:global(.xvq3mubqy) {
  stop-color: var(--svg-color--261326, #261326);
  stop-opacity: 0;
}

:global(.xzg4h5kta) {
  fill: var(--svg-color--b38578, #B38578);
  d: path("m15.618 10.147l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.376-.646-.376-.765 0");
}

:global(.y3gk9pbvh) {
  stop-color: var(--svg-color--634945, #634945);
}

:global(.yiz6fvgdb) {
  stop-color: var(--svg-color--cca58b, #CCA58B);
}

:global(.yr342ibfl) {
  stop-color: var(--svg-color--bab9c0, #BAB9C0);
}

:global(.ysga7wb0w) {
  stop-color: var(--svg-color--25131c, #25131C);
  stop-opacity: 0;
}

:global(.zaeth0b6d) {
  stop-color: var(--svg-color--636363, #636363);
}

:global(.zemyxxbjg) {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
}

:global(.zhb5rly-q) {
  d: path("M18.119 9.623c.063.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.389-.051");
}

:global(.zpok88b9y) {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.109 3.967c.023.243.234 1.156.544 1.71");
}

:global(.zt_ualb3u) {
  stop-color: var(--svg-color--543870, #543870);
  stop-opacity: 0;
}

</style>
