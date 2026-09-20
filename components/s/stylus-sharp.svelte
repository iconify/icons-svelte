<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ynr7aybob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:stylus-sharp" {...props}></Icon>
<style>
:global(.ynr7aybob) {
  fill: currentColor;
  d: path("M8.45 20.1L2.7 21.3l1.2-5.75zm1.625-1.225l-4.95-4.95l11.75-11.75l4.95 4.95z");
}

</style>
