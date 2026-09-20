<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lhne4ccit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:south-west-outline-sharp" {...props}></Icon>
<style>
:global(.lhne4ccit) {
  fill: currentColor;
  d: path("M5.5 18.5v-9h1v7.292l12.1-12.1l.708.708l-12.1 12.1H14.5v1z");
}

</style>
