<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3k5amnsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-turn-slight-right" {...props}></Icon>
<style>
:global(.v3k5amnsa) {
  fill: currentColor;
  d: path("M12.34 6V4H18v5.66h-2V7.41l-5 5V20H9v-8.41L14.59 6z");
}

</style>
