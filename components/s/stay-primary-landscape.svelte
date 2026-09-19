<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vssqaob3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:stay-primary-landscape" {...props}></Icon>
<style>
:global(.vssqaob3w) {
  fill: currentColor;
  d: path("M1.01 7L1 17c0 1.1.9 2 2 2h18c1.1 0 2-.9 2-2V7c0-1.1-.9-2-2-2H3c-1.1 0-1.99.9-1.99 2M19 7v10H5V7z");
}

</style>
