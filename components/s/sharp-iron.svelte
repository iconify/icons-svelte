<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7evb1cib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-iron" {...props}></Icon>
<style>
:global(.s7evb1cib) {
  fill: currentColor;
  d: path("M18 6v8h-1V7H7v3h2V9h6v2H6c-2.21 0-4 1.79-4 4v3h15v-2h3V8h2V6z");
}

</style>
