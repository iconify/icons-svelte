<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="ih1i-5b2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:triangle-28-filled" {...props}></Icon>
<style>
:global(.ih1i-5b2o) {
  fill: currentColor;
  d: path("M15.967 4.158c-.857-1.542-3.075-1.542-3.933 0L3.069 20.285C2.142 21.952 3.347 24 5.254 24h17.493c1.906 0 3.111-2.048 2.185-3.715z");
}

</style>
