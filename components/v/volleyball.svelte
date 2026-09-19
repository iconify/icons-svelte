<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5_0g-2pv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j5_0g-2pv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:volleyball" {...props}></Icon>
