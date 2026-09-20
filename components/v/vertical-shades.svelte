<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bnkr6kbks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:vertical-shades" {...props}></Icon>
<style>
:global(.bnkr6kbks) {
  fill: currentColor;
  d: path("M3 20v-1h2V4h14v15h2v1zm6.75-1h4.5V5h-4.5z");
}

</style>
