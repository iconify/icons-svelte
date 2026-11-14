<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s57h_shdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:thermostat-cool" {...props}></Icon>
<style>
:global(.s57h_shdn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.551 19.782a9.5 9.5 0 1 1 10.898 0M12 2.5v2.75M12 8v8m3.464-6l-6.928 4m6.928 0l-6.928-4");
}

</style>
