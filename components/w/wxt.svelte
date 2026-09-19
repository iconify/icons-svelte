<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpm4eacfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wpm4eacfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:wxt" {...props}></Icon>
