<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ks3qzdbnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:stylus-pencil-sharp" {...props}></Icon>
<style>
:global(.ks3qzdbnx) {
  fill: currentColor;
  d: path("m6 16l5-13h2l5 13zm-2 5l1-3h14l1 3z");
}

</style>
