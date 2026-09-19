<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-6icjxui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="t-6icjxui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:terminal-window-fill-12" {...props}></Icon>
