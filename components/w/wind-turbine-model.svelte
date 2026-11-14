<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="czw19kazs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:wind-turbine-model" {...props}></Icon>
<style>
:global(.czw19kazs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 9V2.5M12 9l-6.5 3.75M12 9l6.5 3.75M12 9v12.5m-3.5 0h7");
}

</style>
