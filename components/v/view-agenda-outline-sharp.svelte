<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkyk0ubzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:view-agenda-outline-sharp" {...props}></Icon>
<style>
:global(.fkyk0ubzl) {
  fill: currentColor;
  d: path("M3 21v-8h18v8zm2-2h14v-4H5zm-2-8V3h18v8zm2-2h14V5H5zm0 6v4zM5 5v4z");
}

</style>
