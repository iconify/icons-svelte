<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-265-bfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u-265-bfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:volume-off" {...props}></Icon>
