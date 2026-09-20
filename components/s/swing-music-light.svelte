<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz97kebhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tz97kebhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:swing-music-light" {...props}></Icon>
