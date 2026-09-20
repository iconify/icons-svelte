<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i5vjvgs8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:slash-forward-24-regular" {...props}></Icon>
<style>
:global(.i5vjvgs8l) {
  fill: currentColor;
  d: path("M15.499 2.042a.75.75 0 0 1 .459.957l-6.5 18.5A.75.75 0 0 1 8.043 21l6.5-18.5a.75.75 0 0 1 .956-.459");
}

</style>
