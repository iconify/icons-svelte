<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-8at39gu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m-8at39gu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:two-people-standing-in-rectangle-outline-under-arrow-up-beside-arrow-down" {...props}></Icon>
