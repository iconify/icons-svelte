<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_uvm7bnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="a_uvm7bnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:twitter-box" {...props}></Icon>
