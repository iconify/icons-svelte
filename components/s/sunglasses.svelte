<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xr4x-ojwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xr4x-ojwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:sunglasses" {...props}></Icon>
