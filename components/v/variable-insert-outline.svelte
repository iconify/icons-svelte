<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i7nt0_9fe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:variable-insert-outline" {...props}></Icon>
<style>
:global(.i7nt0_9fe) {
  fill: currentColor;
  d: path("M4 16V8h16v3.192h-1V9H5v6h9.577v1zm1-1V9zm16.677 4l-3.715-3.71v3.21h-1v-4.923h4.923v1h-3.216l3.697 3.735z");
}

</style>
