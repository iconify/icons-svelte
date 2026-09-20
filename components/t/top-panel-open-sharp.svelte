<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwc8sqbzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:top-panel-open-sharp" {...props}></Icon>
<style>
:global(.jwc8sqbzn) {
  fill: currentColor;
  d: path("m12 16.5l4-4H8zM5 19h14v-9H5zm-2 2V3h18v18z");
}

</style>
