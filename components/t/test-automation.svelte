<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i7_o6db3a"/><path class="vdo1j_06c"/><path class="k57ggj4vq"/><path class="niy0uvcpl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:test-automation" {...props}></Icon>
<style>
:global(.i7_o6db3a) {
  d: path("m10.884 8.159l.142-1.572h1.948l.142 1.572l1.653.954l1.432-.663l.974 1.687l-1.29.909v1.908l1.29.909l-.974 1.687l-1.432-.663l-1.653.954l-.142 1.572h-1.948l-.142-1.572l-1.653-.954l-1.432.663l-.974-1.687l1.29-.909v-1.908l-1.29-.909l.974-1.687l1.432.663Z");
}

:global(.k57ggj4vq) {
  d: path("M19.794 7.5A9 9 0 1 1 7.5 4.206");
}

:global(.niy0uvcpl) {
  d: path("m5 3.5l2.5.75l-.75 2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vdo1j_06c) {
  d: path("M10.25 12a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

</style>
