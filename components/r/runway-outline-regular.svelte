<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oakk4fbrw"/><path class="ifv_d4f9e"/><path class="d1zyr9bfc"/><path class="iyj_k-bwo"/><path class="jnf_2db5t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:runway-outline-regular" {...props}></Icon>
<style>
:global(.d1zyr9bfc) {
  d: path("M12 4v4");
}

:global(.ifv_d4f9e) {
  d: path("M17 2v20");
}

:global(.iyj_k-bwo) {
  d: path("M12 11v4");
}

:global(.jnf_2db5t) {
  d: path("M12 18v3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oakk4fbrw) {
  d: path("M7 2v20");
}

</style>
