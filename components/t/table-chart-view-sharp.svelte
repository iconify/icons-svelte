<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sz-x-ebga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:table-chart-view-sharp" {...props}></Icon>
<style>
:global(.sz-x-ebga) {
  fill: currentColor;
  d: path("M7.4 22L6 20.6l6.9-6.925l3.5 3.5L21.575 12L23 13.425L16.4 20l-3.5-3.5zM4 21H2V3h18v7H4z");
}

</style>
