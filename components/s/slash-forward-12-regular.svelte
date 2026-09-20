<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="gbsiygn_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:slash-forward-12-regular" {...props}></Icon>
<style>
:global(.gbsiygn_p) {
  fill: currentColor;
  d: path("M7.658 1.026a.5.5 0 0 1 .316.632l-3 9a.5.5 0 1 1-.948-.316l3-9a.5.5 0 0 1 .632-.316");
}

</style>
