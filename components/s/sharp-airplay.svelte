<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="codrdcbyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-airplay" {...props}></Icon>
<style>
:global(.codrdcbyt) {
  fill: currentColor;
  d: path("M6 22h12l-6-6zM23 3H1v16h6v-2H3V5h18v12h-4v2h6z");
}

</style>
