<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ffjojta0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:texture-outline" {...props}></Icon>
<style>
:global(.ffjojta0e) {
  fill: currentColor;
  d: path("M4.4 21q-.475-.1-.888-.513T3 19.6L19.6 3q.525.125.9.513t.525.887zM3 14.7v-2.8L11.9 3h2.8zM3 7V5q0-.825.588-1.413T5 3h2zm14 14l4-4v2q0 .825-.587 1.413T19 21zm-7.7 0L21 9.3v2.8L12.1 21z");
}

</style>
