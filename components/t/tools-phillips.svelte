<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oywtd5bjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:tools-phillips" {...props}></Icon>
<style>
:global(.oywtd5bjt) {
  fill: currentColor;
  d: path("M7 21v-2h10v2zm0-3V8l3.75-5h2.5L17 8v10zm2-7l2-2V6L9 8.675zm6 0V8.675L13 6v3z");
}

</style>
