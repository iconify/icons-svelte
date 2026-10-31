<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm1d_swqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fm1d_swqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:spoon-beside-table-knife-in-eaved-gabled-shelter" {...props}></Icon>
