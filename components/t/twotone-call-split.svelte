<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdbwu9bnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-call-split" {...props}></Icon>
<style>
:global(.cdbwu9bnt) {
  fill: currentColor;
  d: path("M20 4h-6l2.29 2.29l-2.88 2.88l1.42 1.42l2.88-2.88L20 10zM4 4v6l2.29-2.29l4.71 4.7V20h2v-8.41l-5.29-5.3L10 4z");
}

</style>
