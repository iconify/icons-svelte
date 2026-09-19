<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v240b9bic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-arrow-forward-ios" {...props}></Icon>
<style>
:global(.v240b9bic) {
  fill: currentColor;
  d: path("M6.23 20.23L8 22l10-10L8 2L6.23 3.77L14.46 12z");
}

</style>
