<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yey0pshjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:tooltip-sharp" {...props}></Icon>
<style>
:global(.yey0pshjj) {
  fill: currentColor;
  d: path("m12 22l-2.675-4H2V2h20v16h-7.325z");
}

</style>
