<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfmmmw5bm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vfmmmw5bm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:sack-dollar" {...props}></Icon>
