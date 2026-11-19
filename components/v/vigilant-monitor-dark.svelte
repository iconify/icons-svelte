<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3ixzgbuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y3ixzgbuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vigilant-monitor-dark" {...props}></Icon>
