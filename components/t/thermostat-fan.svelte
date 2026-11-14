<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="goiz_9b_e"/><path class="v3yk_79_c"/><path class="l-90lk5gq"/><path class="avnq1sbnx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:thermostat-fan" {...props}></Icon>
<style>
:global(.avnq1sbnx) {
  d: path("m11.975 13.458l-1.25-2.166l4.547-2.625l1.25 2.166Z");
}

:global(.goiz_9b_e) {
  d: path("M6.551 19.782a9.5 9.5 0 1 1 10.898 0M12 2.5v2.75");
}

:global(.l-90lk5gq) {
  d: path("m13.275 11.292l-1.25 2.166l-4.547-2.625l1.25-2.166Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v3yk_79_c) {
  d: path("M10.75 11.25h2.5v5.25h-2.5Z");
}

</style>
