<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="njrb65bpb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-color-accent-24-regular" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.njrb65bpb) {
  d: path("M4.5 16.75a.75.75 0 0 1 .75-.75h12.5a.75.75 0 0 1 .75.75v3a.75.75 0 0 1-.75.75H5.25a.75.75 0 0 1-.75-.75v-3z");
  fill: currentColor;
}

</style>
