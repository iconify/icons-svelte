<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xjj7gnb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:skip-intro" {...props}></Icon>
<style>
:global(.xjj7gnb_w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.19 5.74l7.62 5.27q1.44.99 0 1.98l-7.62 5.27q-1.44.99-1.44-.76v-11q0-1.75 1.44-.76m13.06-.99v14.5");
}

</style>
