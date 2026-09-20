<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="hk6t0zbwo"/><path class="evw72ubqw"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:shopx-background" {...props}></Icon>
<style>
:global(.evw72ubqw) {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.988 11.658a5.995 5.995 0 0 1-7.645-7.645c-.12-.01-.23-.01-.345-.01A7.995 7.995 0 0 0 4.274 14.07A4.027 4.027 0 0 1 9.7 19.657a7.995 7.995 0 0 0 10.293-7.994z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.hk6t0zbwo) {
  fill: var(--svg-color--061a25, #061a25);
  d: path("M24 0H0v24h24z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
