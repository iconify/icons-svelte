<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hnvnn0bgl"/><path class="lhdgxh0_q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:shield-dollar" {...props}></Icon>
<style>
:global(.hnvnn0bgl) {
  d: path("m12 2.75l7.5 2.75v6c0 4.7-3.1 8-7.5 9.75c-4.4-1.75-7.5-5.05-7.5-9.75v-6Z");
}

:global(.lhdgxh0_q) {
  d: path("M14.5 9c-.4-.9-1.3-1.25-2.5-1.25c-1.4 0-2.5.75-2.5 2c0 2.65 5 1.15 5 4c0 1.15-1.1 2-2.5 2c-1.25 0-2.1-.45-2.5-1.25M12 6.25v1.5m0 8v1.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
