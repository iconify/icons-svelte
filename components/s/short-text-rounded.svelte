<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mneoaccvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:short-text-rounded" {...props}></Icon>
<style>
:global(.mneoaccvk) {
  fill: currentColor;
  d: path("M5 15q-.425 0-.712-.288T4 14t.288-.712T5 13h8q.425 0 .713.288T14 14t-.288.713T13 15zm0-4q-.425 0-.712-.288T4 10t.288-.712T5 9h14q.425 0 .713.288T20 10t-.288.713T19 11z");
}

</style>
