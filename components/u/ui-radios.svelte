<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxbt59n7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vxbt59n7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:ui-radios" {...props}></Icon>
