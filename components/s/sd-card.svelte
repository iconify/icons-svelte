<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kc-5ykbhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:sd-card" {...props}></Icon>
<style>
:global(.kc-5ykbhe) {
  fill: currentColor;
  d: path("M6.616 21q-.691 0-1.153-.462T5 19.385V8.423L10.423 3h6.962q.69 0 1.153.463T19 4.615v14.77q0 .69-.462 1.152T17.384 21zm2.961-10.23h1V7.345h-1zm2.808 0h1V7.345h-1zm2.807 0h1V7.345h-1z");
}

</style>
