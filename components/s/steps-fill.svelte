<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="xb_s_dbjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:steps-fill" {...props}></Icon>
<style>
:global(.xb_s_dbjr) {
  fill: currentColor;
  d: path("M240 56v144a8 8 0 0 1-8 8H8a8 8 0 0 1 0-16h48v-40a8 8 0 0 1 8-8h48v-40a8 8 0 0 1 8-8h48V56a8 8 0 0 1 8-8h56a8 8 0 0 1 8 8");
}

</style>
