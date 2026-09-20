<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzi166bfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vzi166bfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tiktok-light" {...props}></Icon>
