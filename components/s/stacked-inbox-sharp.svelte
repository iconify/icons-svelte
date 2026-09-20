<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r1vx5pbig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:stacked-inbox-sharp" {...props}></Icon>
<style>
:global(.r1vx5pbig) {
  fill: currentColor;
  d: path("M5.5 17.116v-12h16v12zm8-3.424q.825 0 1.413-.587t.587-1.413h5V6.116h-14v5.576h5q0 .825.588 1.413t1.412.587m3.73 6.424H2.5V7.5h1v11.616h13.73z");
}

</style>
