<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="s4-cv-boo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:triangle-down-12-regular" {...props}></Icon>
<style>
:global(.s4-cv-boo) {
  fill: currentColor;
  d: path("M6.786 10.541a.903.903 0 0 1-1.572 0L1.122 3.372C.774 2.762 1.211 2 1.91 2h8.182c.698 0 1.135.762.787 1.372zM6 9.881l3.917-6.864H2.083z");
}

</style>
