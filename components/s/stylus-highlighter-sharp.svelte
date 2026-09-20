<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l781zc_iy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:stylus-highlighter-sharp" {...props}></Icon>
<style>
:global(.l781zc_iy) {
  fill: currentColor;
  d: path("M7.673 15.308V4h1.994l6.64 3.244v8.064zM5 20l.827-2.308h12.346L19 20z");
}

</style>
