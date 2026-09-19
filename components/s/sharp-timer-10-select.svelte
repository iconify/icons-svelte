<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0rk03e9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-timer-10-select" {...props}></Icon>
<style>
:global(.a0rk03e9x) {
  fill: currentColor;
  d: path("M13 8v8h-3V8zm3-3H7v14h9zM1 8h2v11h3V5H1zm22 3h-6v5h4v1h-4v2h6v-5h-4v-1h4z");
}

</style>
