<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x0m4pvb0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:upload-2-outline-sharp" {...props}></Icon>
<style>
:global(.x0m4pvb0o) {
  fill: currentColor;
  d: path("M5 21v-1h14v1zm4.635-3.77v-6.788h-3.27L12 3l5.616 7.442h-3.27v6.789zm1-1h2.711V9.424h2.208L12 4.635L8.427 9.423h2.208zM12 9.424");
}

</style>
