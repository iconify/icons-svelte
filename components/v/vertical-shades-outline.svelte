<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ass1g5b6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:vertical-shades-outline" {...props}></Icon>
<style>
:global(.ass1g5b6l) {
  fill: currentColor;
  d: path("M3 20v-1h2V4h14v15h2v1zm3-1h2.75V5H6zm3.75 0h4.5V5h-4.5zm5.5 0H18V5h-2.75zM6 19V5zm12 0V5z");
}

</style>
