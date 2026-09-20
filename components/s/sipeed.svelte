<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rld-_ccic.css';
import '../../css/v/vl74ao08p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rld-_ccic"/><path class="vl74ao08p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sipeed" {...props}></Icon>
