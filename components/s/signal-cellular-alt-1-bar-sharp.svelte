<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n35-htkzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:signal-cellular-alt-1-bar-sharp" {...props}></Icon>
<style>
:global(.n35-htkzb) {
  fill: currentColor;
  d: path("M6 19v-4h1.616v4z");
}

</style>
