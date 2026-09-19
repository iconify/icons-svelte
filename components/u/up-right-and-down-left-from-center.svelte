<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw9d_bb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="gw9d_bb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:up-right-and-down-left-from-center" {...props}></Icon>
