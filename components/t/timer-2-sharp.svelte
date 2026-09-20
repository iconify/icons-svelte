<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cieqqnjqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:timer-2-sharp" {...props}></Icon>
<style>
:global(.cieqqnjqe) {
  fill: currentColor;
  d: path("M8 19v-8.5h6V8H8V5h9v8.5h-6V16h6v3z");
}

</style>
