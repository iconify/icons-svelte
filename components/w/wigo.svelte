<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ab64tmb8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:wigo" {...props}></Icon>
<style>
:global(.ab64tmb8n) {
  fill: var(--svg-color--070bf0, #070bf0);
  d: path("M21 12h-1.928V6.073a15.01 15.01 0 0 1-15.21 4.089L3 9.904l.514-1.729l.868.257c4.822 1.44 10.093.148 13.539-3.503H12V3h9zM3 12h1.929v5.927a15.01 15.01 0 0 1 15.21-4.088l.861.257l-.514 1.729l-.868-.257a13.35 13.35 0 0 0-13.539 3.504H12V21H3z");
}

</style>
