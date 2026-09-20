<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nw1tzdbuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nw1tzdbuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:teamviewer-dark" {...props}></Icon>
