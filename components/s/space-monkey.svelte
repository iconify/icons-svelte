<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zdgu3ybil"/><path class="sqht-eb6k"/><path class="vqrv3jbeh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:space-monkey" {...props}></Icon>
<style>
:global(.sqht-eb6k) {
  d: path("M12 17c-3.25-.5-3.75-4-3.25-6s2.5-2.25 3.25-1c.75-1.25 2.75-1 3.25 1s0 5.5-3.25 6Zm-6.75-6.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vqrv3jbeh) {
  d: path("M15.25 10.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm-4.5 2h.01m2.49 0h.01");
}

:global(.zdgu3ybil) {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Z");
}

</style>
