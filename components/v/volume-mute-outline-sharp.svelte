<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kpm-8qbob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:volume-mute-outline-sharp" {...props}></Icon>
<style>
:global(.kpm-8qbob) {
  fill: currentColor;
  d: path("M7 15V9h4l5-5v16l-5-5zm2-2h2.85L14 15.15v-6.3L11.85 11H9zm2.5-1");
}

</style>
