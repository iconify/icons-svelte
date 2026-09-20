<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbme2ub2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mbme2ub2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:wheelie-bin-and-apple-core" {...props}></Icon>
