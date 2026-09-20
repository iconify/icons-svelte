<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rcq66ibnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:stockpot-outline-sharp" {...props}></Icon>
<style>
:global(.rcq66ibnx) {
  fill: currentColor;
  d: path("M3 20V8h18v12zm2-2h14v-8H5zM3 7V5h6V3h6v2h6v2zm9 7");
}

</style>
