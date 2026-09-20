<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nlfixfo7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:top-panel-close-sharp" {...props}></Icon>
<style>
:global(.nlfixfo7b) {
  fill: currentColor;
  d: path("M8 16.5h8l-4-4zM5 19h14v-9H5zm-2 2V3h18v18z");
}

</style>
