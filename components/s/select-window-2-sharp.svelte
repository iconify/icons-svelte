<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nrjlbih3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:select-window-2-sharp" {...props}></Icon>
<style>
:global(.nrjlbih3m) {
  fill: currentColor;
  d: path("M20 15V7H6V2h16v13zM2 22V9h16v13z");
}

</style>
