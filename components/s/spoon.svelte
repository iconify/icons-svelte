<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rft8ifkfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rft8ifkfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:spoon" {...props}></Icon>
