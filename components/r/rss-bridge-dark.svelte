<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgil3hbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wgil3hbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rss-bridge-dark" {...props}></Icon>
