<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cd2prfbuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:view-week-sharp" {...props}></Icon>
<style>
:global(.cd2prfbuv) {
  fill: currentColor;
  d: path("M2 20V4h5.325v16zm7.35 0V4h5.325v16zm7.325 0V4H22v16z");
}

</style>
