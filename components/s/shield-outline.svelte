<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy-sd1yvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iy-sd1yvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:shield-outline" {...props}></Icon>
