<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xa41frb-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:vite" {...props}></Icon>
<style>
:global(.xa41frb-w) {
  fill: var(--svg-color--007aff, #007aff);
  d: path("m3 7.725l5.625-1.35l-.563 14.063zm6.75-1.524L21 3.563L8.231 20.274L9.75 6.206z");
}

</style>
