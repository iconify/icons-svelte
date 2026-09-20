<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjm76zbxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gjm76zbxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tv-screen" {...props}></Icon>
