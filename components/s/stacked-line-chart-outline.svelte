<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bh4r20bek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:stacked-line-chart-outline" {...props}></Icon>
<style>
:global(.bh4r20bek) {
  fill: currentColor;
  d: path("M3.5 20.73L2.77 20l6.807-6.808l4 4l6.985-8l.707.67l-7.653 8.83l-4.039-4.038zm0-6L2.77 14l6.807-6.808l4 4l6.985-8l.707.67l-7.653 8.83l-4.039-4.038z");
}

</style>
