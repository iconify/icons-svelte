<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="o4xg3_bfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:split-vertical-fill" {...props}></Icon>
<style>
:global(.o4xg3_bfe) {
  fill: currentColor;
  d: path("M216 152a8 8 0 0 1-8 8h-72v32h24a8 8 0 0 1 5.66 13.66l-32 32a8 8 0 0 1-11.32 0l-32-32A8 8 0 0 1 96 192h24v-32H48a8 8 0 0 1 0-16h160a8 8 0 0 1 8 8M48 112h160a8 8 0 0 0 0-16h-72V64h24a8 8 0 0 0 5.66-13.66l-32-32a8 8 0 0 0-11.32 0l-32 32A8 8 0 0 0 96 64h24v32H48a8 8 0 0 0 0 16");
}

</style>
