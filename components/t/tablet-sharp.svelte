<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sebyljbld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:tablet-sharp" {...props}></Icon>
<style>
:global(.sebyljbld) {
  fill: currentColor;
  d: path("M1 20V4h22v16zm5-2h12V6H6z");
}

</style>
