<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o_ssmh9ez"/><path class="ngx0bsb5w"/><path class="oxy-4pqdz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:send-outline-regular" {...props}></Icon>
<style>
:global(.ngx0bsb5w) {
  d: path("M8.5 15.5 13 11");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o_ssmh9ez) {
  d: path("M3 12a9 9 0 1 0 18 0 9 9 0 1 0 -18 0");
}

:global(.oxy-4pqdz) {
  d: path("M10.5 9H15v4.5");
}

</style>
