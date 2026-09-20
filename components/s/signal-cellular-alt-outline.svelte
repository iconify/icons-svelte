<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nd_f2la9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:signal-cellular-alt-outline" {...props}></Icon>
<style>
:global(.nd_f2la9e) {
  fill: currentColor;
  d: path("M6 19v-4h1.616v4zm5.808 0v-9h1.615v9zm5.577 0V5H19v14z");
}

</style>
