<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="brkrrubld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:speed-1-25-outline-sharp" {...props}></Icon>
<style>
:global(.brkrrubld) {
  fill: currentColor;
  d: path("M7.039 16.5v-1h1v1zm9.461 0v-1h4v-3h-4v-5h5v1h-4v3h4v5zm-6.73 0v-5h4v-3h-4v-1h5v5h-4v3h4v1zm-5.462 0v-8H2.5v-1h2.808v9z");
}

</style>
