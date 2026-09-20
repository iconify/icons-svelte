<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mqwcj0b4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:trending-down-outline" {...props}></Icon>
<style>
:global(.mqwcj0b4q) {
  fill: currentColor;
  d: path("M16 17.096v-1h3.33l-6.026-5.938l-4 4L3 7.804l.708-.708l5.596 5.596l4-4L20 15.39v-3.293h1v5z");
}

</style>
