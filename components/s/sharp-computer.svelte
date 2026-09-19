<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lc37yebvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-computer" {...props}></Icon>
<style>
:global(.lc37yebvl) {
  fill: currentColor;
  d: path("m20 18l2-2V4H2v12l2 2H0v2h24v-2zM4 6h16v10H4z");
}

</style>
