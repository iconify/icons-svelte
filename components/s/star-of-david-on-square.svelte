<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv2clib9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jv2clib9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:star-of-david-on-square" {...props}></Icon>
