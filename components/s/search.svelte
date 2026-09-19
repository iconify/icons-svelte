<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy-s0bbvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="iy-s0bbvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:search" {...props}></Icon>
