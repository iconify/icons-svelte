<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v2wzwhbsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:text-select-move-down-sharp" {...props}></Icon>
<style>
:global(.v2wzwhbsv) {
  fill: currentColor;
  d: path("M4 5V4h16v1zm8 11.308L8.692 13l.708-.708l2.1 2.075V7.5h1v6.867l2.1-2.075l.708.708zM4 20v-1h16v1z");
}

</style>
