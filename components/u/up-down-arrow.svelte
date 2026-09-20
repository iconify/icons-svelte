<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="bj_pawvjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noto-v1:up-down-arrow" {...props}></Icon>
<style>
:global(.bj_pawvjy) {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M76.09 44.31h20.06L64 .46L31.85 44.31H51.9V83.7H31.85L64 127.54L96.15 83.7H76.09z");
}

</style>
