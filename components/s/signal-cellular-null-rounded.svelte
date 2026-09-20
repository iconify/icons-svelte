<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_mbjmrqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:signal-cellular-null-rounded" {...props}></Icon>
<style>
:global(.t_mbjmrqq) {
  fill: currentColor;
  d: path("M4.598 21q-.444 0-.62-.401t.145-.722L19.877 4.123q.321-.321.722-.145t.401.62v15.479q0 .394-.264.658q-.265.265-.659.265zm.823-1H20V5.427z");
}

</style>
