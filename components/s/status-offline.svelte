<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="obw4-dbdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:status-offline" {...props}></Icon>
<style>
:global(.obw4-dbdb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.828 21.464a9.5 9.5 0 1 1 8.636-8.636M15.5 15.5l5 5m0-5l-5 5");
}

</style>
