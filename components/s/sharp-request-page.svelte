<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="exjy7vblv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-request-page" {...props}></Icon>
<style>
:global(.exjy7vblv) {
  fill: currentColor;
  d: path("M14 2H4.01L4 22h16V8zm1 9h-4v1h4v5h-2v1h-2v-1H9v-2h4v-1H9V9h2V8h2v1h2z");
}

</style>
