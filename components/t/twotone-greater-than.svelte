<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dy76dkb7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-greater-than" {...props}></Icon>
<style>
:global(.dy76dkb7p) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m6.5 17.5l8.25-5.5L6.5 6.5l1-1.5L18 12L7.5 19z");
}

</style>
