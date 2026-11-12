<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tfsq0xb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wi-fi-none-outline" {...props}></Icon>
<style>
:global(.tfsq0xb1f) {
  fill: currentColor;
  d: path("M12.0176 18.7144C12.4318 18.7144 12.7676 19.0501 12.7676 19.4644C12.7676 19.8786 12.4318 20.2144 12.0176 20.2144C11.6034 20.2144 11.2676 19.8786 11.2676 19.4644C11.2676 19.0501 11.6034 18.7144 12.0176 18.7144Z");
}

</style>
