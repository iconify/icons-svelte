<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v9r87ewzp"/><rect class="lihla0gzi"/><path class="jmd74bfhc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:spice-box" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jmd74bfhc) {
  d: path("M8.75 11.75v9.5m6.5-9.5v9.5");
}

:global(.lihla0gzi) {
  width: 18.5px;
  height: 9.5px;
  x: 2.75px;
  y: 11.75px;
  rx: 1.5px;
}

:global(.v9r87ewzp) {
  d: path("M4.5 3.5h15q.75 0 .58.73l-.91 3.79q-.17.73-.92.73H5.75q-.75 0-.92-.73l-.91-3.79q-.17-.73.58-.73");
}

</style>
