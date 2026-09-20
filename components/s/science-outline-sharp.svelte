<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ar-zhsu-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:science-outline-sharp" {...props}></Icon>
<style>
:global(.ar-zhsu-y) {
  fill: currentColor;
  d: path("M5 21q-1.275 0-1.812-1.137t.262-2.113L9 11V5H7V3h10v2h-2v6l5.55 6.75q.8.975.263 2.113T19 21zm0-2h14l-6-7.3V5h-2v6.7zm7-7");
}

</style>
