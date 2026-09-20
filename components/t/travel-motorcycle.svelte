<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm6dfob2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xm6dfob2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:travel-motorcycle" {...props}></Icon>
