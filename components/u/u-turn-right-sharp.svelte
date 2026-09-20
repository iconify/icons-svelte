<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rlx4b1bpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:u-turn-right-sharp" {...props}></Icon>
<style>
:global(.rlx4b1bpx) {
  fill: currentColor;
  d: path("M6 21V9q0-2.5 1.75-4.25T12 3t4.25 1.75T18 9v4.2l1.6-1.6L21 13l-4 4l-4-4l1.4-1.4l1.6 1.6V9q0-1.65-1.175-2.825T12 5T9.175 6.175T8 9v12z");
}

</style>
