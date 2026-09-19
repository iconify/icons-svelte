<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jo3zqub6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:youtify" {...props}></Icon>
<style>
:global(.jo3zqub6y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 24.306h-7.843l-4.355-7.774l-6.398 21.485l-6.979-28.034l-5.582 14.323H4.5");
}

</style>
