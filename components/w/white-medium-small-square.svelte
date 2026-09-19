<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ityh9rmws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-v1:white-medium-small-square" {...props}></Icon>
<style>
:global(.ityh9rmws) {
  fill: var(--svg-color--d0d2d3, #d0d2d3);
  d: path("M49.717 44.915a3.55 3.55 0 0 1-3.549 3.552H20.332a3.55 3.55 0 0 1-3.548-3.552V19.083a3.55 3.55 0 0 1 3.548-3.551h25.836a3.55 3.55 0 0 1 3.549 3.551z");
}

</style>
