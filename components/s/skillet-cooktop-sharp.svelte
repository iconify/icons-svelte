<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ea5pzfbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:skillet-cooktop-sharp" {...props}></Icon>
<style>
:global(.ea5pzfbjg) {
  fill: currentColor;
  d: path("M3 15V8h13V6.275l6.675-2.225l.625 1.9L18 7.725V15zm6 6v-3H2v-2h9v5zm4 0v-5h9v2h-7v3z");
}

</style>
