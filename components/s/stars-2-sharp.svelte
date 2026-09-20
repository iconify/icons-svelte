<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kj5qwvv-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:stars-2-sharp" {...props}></Icon>
<style>
:global(.kj5qwvv-m) {
  fill: currentColor;
  d: path("m6.44 20l1.471-6.275L3 9.481l6.47-.548L12 3l2.55 5.933l6.47.548l-4.912 4.244L17.578 20L12 16.66zM17.424 7.058l.448-1.88l-1.505-1.263l1.984-.161l.766-1.773l.765 1.773l1.985.161L20.36 5.18l.448 1.879l-1.692-1.002z");
}

</style>
