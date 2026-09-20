<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGh7UOEbiz)" class="r4i437pya"/><path class="pp6v-oblh"/><path class="e3i5z4baf"/></g><defs><linearGradient id="SVGh7UOEbiz" x1="5.961" x2="10.582" y1="8.667" y2="19.021" gradientUnits="userSpaceOnUse"><stop class="lrxp2fb9w"/><stop offset=".13" class="mgur39bvh"/><stop offset=".258" class="ss2ufhbeu"/><stop offset=".376" class="f9cro4egm"/><stop offset=".492" class="eojwqixaj"/><stop offset=".612" class="zgxo820li"/><stop offset=".731" class="ahe1014pz"/><stop offset=".829" class="bdukn1b5f"/><stop offset="1" class="l77ol0bwj"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:swap-background" {...props}></Icon>
<style>
:global(.ahe1014pz) {
  stop-color: var(--svg-color--00b9fa, #00b9fa);
}

:global(.bdukn1b5f) {
  stop-color: var(--svg-color--00c5fb, #00c5fb);
}

:global(.e3i5z4baf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M16 14.119v-.92l-2.8 2L16 17v-.817a4.4 4.4 0 0 0-.4-8.782c-1.008 0-2.4.354-3.2 1.2c-1 1.154-2.192 4.062-2.192 4.062l3.57-2.315A2.3 2.3 0 1 1 16 14.12");
}

:global(.eojwqixaj) {
  stop-color: var(--svg-color--009df9, #009df9);
}

:global(.f9cro4egm) {
  stop-color: var(--svg-color--008bf9, #008bf9);
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.l77ol0bwj) {
  stop-color: var(--svg-color--00ccfc, #00ccfc);
}

:global(.lrxp2fb9w) {
  stop-color: var(--svg-color--0076ef, #0076ef);
}

:global(.mgur39bvh) {
  stop-color: var(--svg-color--007ff6, #007ff6);
}

:global(.pp6v-oblh) {
  fill: var(--svg-color--fff, #fff);
  d: path("M8 9.881v.92L10.8 8.8L8 7v.818a4.4 4.4 0 0 0 .4 8.782c1.008 0 2.4-.355 3.2-1.2c1-1.154 2.192-4.062 2.192-4.062l-3.57 2.315a2.302 2.302 0 0 1-3.703-.36A2.3 2.3 0 0 1 8 9.882");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.r4i437pya) {
  d: path("M24 0H0v24h24z");
}

:global(.ss2ufhbeu) {
  stop-color: var(--svg-color--0084f6, #0084f6);
}

:global(.zgxo820li) {
  stop-color: var(--svg-color--00aef9, #00aef9);
}

</style>
