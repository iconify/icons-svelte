<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf401xb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yf401xb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:terminal-cli-stroke-16" {...props}></Icon>
