<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ibh8rr9id"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:smarttime-pro" {...props}></Icon>
<style>
:global(.ibh8rr9id) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 36.27h37M29.707 15.463L9.057 33.63m11.669-10.231l6.41 5.84l-8.771 3.162M33.516 13.86a2.13 2.13 0 0 1-4.261 0a2.13 2.13 0 0 1 4.261 0m-17.878 1.221l6.814-2.737l10.642 10.71l6.658-.114");
}

</style>
