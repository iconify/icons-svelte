<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f85ik0b_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="f85ik0b_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:time-interval" {...props}></Icon>
