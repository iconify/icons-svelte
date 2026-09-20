<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ykifiqb5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:timer-1-sharp" {...props}></Icon>
<style>
:global(.ykifiqb5b) {
  fill: currentColor;
  d: path("M12 19V8H8V5h7v14z");
}

</style>
