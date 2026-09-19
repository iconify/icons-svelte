<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6naq-7ae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-bolt" {...props}></Icon>
<style>
:global(.q6naq-7ae) {
  fill: currentColor;
  d: path("M11 21h-1l1-7H6.74S10.42 7.54 13 3h1l-1 7h4.28z");
}

</style>
