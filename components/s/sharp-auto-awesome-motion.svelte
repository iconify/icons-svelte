<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j2qqsnb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-auto-awesome-motion" {...props}></Icon>
<style>
:global(.j2qqsnb4n) {
  fill: currentColor;
  d: path("M14 2H2v12h2V4h10zm4 4H6v12h2V8h10zm4 4H10v12h12z");
}

</style>
