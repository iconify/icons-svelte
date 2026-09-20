<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n59-0kbri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:vertical-split" {...props}></Icon>
<style>
:global(.n59-0kbri) {
  fill: currentColor;
  d: path("M3 15v-2h8v2zm0 4v-2h8v2zm0-8V9h8v2zm0-4V5h8v2zm12 12q-.825 0-1.412-.587T13 17V7q0-.825.588-1.412T15 5h4q.825 0 1.413.588T21 7v10q0 .825-.587 1.413T19 19z");
}

</style>
