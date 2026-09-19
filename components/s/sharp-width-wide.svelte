<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1wjqqbnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-width-wide" {...props}></Icon>
<style>
:global(.m1wjqqbnz) {
  fill: currentColor;
  d: path("M22 4H2v16h20zM4 6h2v12H4zm16 12h-2V6h2z");
}

</style>
