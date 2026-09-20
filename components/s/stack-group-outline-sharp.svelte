<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jc7luvbbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:stack-group-outline-sharp" {...props}></Icon>
<style>
:global(.jc7luvbbj) {
  fill: currentColor;
  d: path("M8 22v-6H2V2h14v6h6v14zm2-2h10V10h-6V4H4v10h6zm2-8");
}

</style>
