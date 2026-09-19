<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x7geb1b7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-exposure-neg-1" {...props}></Icon>
<style>
:global(.x7geb1b7w) {
  fill: currentColor;
  d: path("M4 11v2h8v-2zm15 7h-2V7.38L14 8.4V6.7L18.7 5h.3z");
}

</style>
