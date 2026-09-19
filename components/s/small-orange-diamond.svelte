<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="rjvq8qjat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:small-orange-diamond" {...props}></Icon>
<style>
:global(.rjvq8qjat) {
  fill: var(--svg-color--f27a52, #f27a52);
  d: path("m16.019 32l15.98-15.981l15.98 15.98L32 47.98z");
}

</style>
