<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="berj5wbmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:view-agenda-outline-sharp" {...props}></Icon>
<style>
:global(.berj5wbmr) {
  fill: currentColor;
  d: path("M4 19.385v-6h16v6zm1-1h14v-4H5zm-1-7.77v-6h16v6zm1-1h14v-4H5zm0 4.77v4zm0-8.77v4z");
}

</style>
