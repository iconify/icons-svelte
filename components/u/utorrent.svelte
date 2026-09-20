<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8gd5xbhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n8gd5xbhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:utorrent" {...props}></Icon>
