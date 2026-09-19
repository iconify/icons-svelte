<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="me47m4bso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-stay-current-portrait" {...props}></Icon>
<style>
:global(.me47m4bso) {
  fill: currentColor;
  d: path("M19 1.01L5.01 1v22H19zM17 19H7V5h10z");
}

</style>
