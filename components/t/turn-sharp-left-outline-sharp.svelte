<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lex20mbqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:turn-sharp-left-outline-sharp" {...props}></Icon>
<style>
:global(.lex20mbqb) {
  fill: currentColor;
  d: path("M16.5 20v-5.884h-10v-8.2l-2.1 2.1l-.708-.708L7 4l3.308 3.308l-.708.708l-2.1-2.1v7.2h10V20z");
}

</style>
