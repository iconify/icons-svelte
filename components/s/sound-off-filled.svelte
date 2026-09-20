<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_is46bkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d_is46bkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:sound-off-filled" {...props}></Icon>
