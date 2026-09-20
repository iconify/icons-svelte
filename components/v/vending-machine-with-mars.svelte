<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/derf13ncu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="derf13ncu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:vending-machine-with-mars" {...props}></Icon>
