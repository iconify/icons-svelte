<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdb2gpbvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wdb2gpbvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:smiling-face-with-eyeglasses-in-circle-outline" {...props}></Icon>
