<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gby4ftqcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gby4ftqcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:vhs" {...props}></Icon>
