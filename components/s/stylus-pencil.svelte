<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwu2qho_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:stylus-pencil" {...props}></Icon>
<style>
:global(.qwu2qho_z) {
  fill: currentColor;
  d: path("m5 20l.473-1.317q.162-.452.533-.722t.848-.269h10.292q.477 0 .848.27t.533.72L19 20zm1.923-4.692L11.346 4h1.289l4.423 11.308z");
}

</style>
