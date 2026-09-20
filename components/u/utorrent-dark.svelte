<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhqab3bdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qhqab3bdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:utorrent-dark" {...props}></Icon>
