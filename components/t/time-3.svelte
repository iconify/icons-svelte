<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvdcm44zn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bvdcm44zn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:time-3" {...props}></Icon>
