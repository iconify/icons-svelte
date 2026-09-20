<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sw8askbty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sw8askbty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:transit-vehicle" {...props}></Icon>
