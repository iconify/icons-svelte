<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hk697hhuu"/><path class="yazo7scbq"/><path class="jms1xqp8l"/><path class="acx2mjbnt"/><path class="s1pdfd1ij"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:time-arrow-down-outline-regular" {...props}></Icon>
<style>
:global(.acx2mjbnt) {
  d: path("M12 11v6");
}

:global(.hk697hhuu) {
  d: path("M15.38 6.75a8 8 0 1 1 -6.76 0");
}

:global(.jms1xqp8l) {
  d: path("M9 3h6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.s1pdfd1ij) {
  d: path("M9.5 14.5 12 17l2.5 -2.5");
}

:global(.yazo7scbq) {
  d: path("M12 3v3");
}

</style>
