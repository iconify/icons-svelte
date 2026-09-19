<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3tgw0b9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-north-west" {...props}></Icon>
<style>
:global(.v3tgw0b9a) {
  fill: currentColor;
  d: path("M5 15h2V8.41L18.59 20L20 18.59L8.41 7H15V5H5z");
}

</style>
