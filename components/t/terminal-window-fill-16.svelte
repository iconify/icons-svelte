<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agtx_2bxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="agtx_2bxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:terminal-window-fill-16" {...props}></Icon>
