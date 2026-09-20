<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o9tunqyot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:shift-outline-sharp" {...props}></Icon>
<style>
:global(.o9tunqyot) {
  fill: currentColor;
  d: path("M8 21v-8H3l9-11l9 11h-5v8zm2-2h4v-8h2.775L12 5.15L7.225 11H10zm2-8");
}

</style>
