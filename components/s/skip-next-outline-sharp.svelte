<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l52pqtbvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:skip-next-outline-sharp" {...props}></Icon>
<style>
:global(.l52pqtbvm) {
  fill: currentColor;
  d: path("M16.27 16.616V7.385h1v9.23zm-9.54 0V7.385L13.655 12zm1-1.866L11.862 12l-4.13-2.75z");
}

</style>
