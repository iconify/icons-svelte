<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fongpbc3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:settop-component-outline" {...props}></Icon>
<style>
:global(.fongpbc3w) {
  fill: currentColor;
  d: path("M2 17V7h20v10zm2-2h16V9H4zm1-2h6v-2H5zm9.713-.288Q15 12.426 15 12t-.288-.712T14 11t-.712.288T13 12t.288.713T14 13t.713-.288m3 0Q18 12.426 18 12t-.288-.712T17 11t-.712.288T16 12t.288.713T17 13t.713-.288M4 15V9z");
}

</style>
