<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sqouhrb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-turn-slight-left" {...props}></Icon>
<style>
:global(.sqouhrb7s) {
  fill: currentColor;
  d: path("M11.66 6V4H6v5.66h2V7.41l5 5V20h2v-8.41L9.41 6z");
}

</style>
