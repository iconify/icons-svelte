<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yslz4fbvt.css';
import '../../css/i/ik3zd0b_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yslz4fbvt"/><path class="ik3zd0b_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:volume-x-20" {...props}></Icon>
