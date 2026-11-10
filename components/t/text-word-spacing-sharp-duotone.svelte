<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xpfr6bc8m"/><path class="nu1a0mbto"/><path class="acxmifogh"/><path class="gf4n4_bjz"/><path class="ohn71uxex"/><path class="mf2_jqbho"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:text-word-spacing-sharp-duotone" {...props}></Icon>
<style>
:global(.acxmifogh) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 8V10H8V8H13ZM22 8V10H15V8H22ZM13 2V4H2V2H13Z");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.gf4n4_bjz) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 2V4H15V2H22Z");
}

:global(.mf2_jqbho) {
  d: path("M22 8V10H15V8H22ZM22 2V4H15V2H22Z");
}

:global(.nu1a0mbto) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 14V16H11V14H22ZM6 8V10H2V8H6Z");
}

:global(.ohn71uxex) {
  d: path("M22 14V16H11V14H22ZM13 8V10H8V8H13Z");
}

:global(.xpfr6bc8m) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 20V22H2V20H13ZM9 14V16H2V14H9Z");
}

</style>
