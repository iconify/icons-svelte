<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydyvfu86y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ydyvfu86y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:stop-filled" {...props}></Icon>
