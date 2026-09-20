<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/liv7s6d2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="liv7s6d2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:triangle-down-with-plus" {...props}></Icon>
