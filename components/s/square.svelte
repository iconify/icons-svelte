<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vgz4piszl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:square" {...props}></Icon>
<style>
:global(.vgz4piszl) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 2.75h10q1.76 0 3.005 1.245T21.25 7v10q0 1.76-1.245 3.005T17 21.25H7q-1.76 0-3.005-1.245T2.75 17V7q0-1.76 1.245-3.005T7 2.75");
}

</style>
