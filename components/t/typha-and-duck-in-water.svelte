<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-55etb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="u-55etb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:typha-and-duck-in-water" {...props}></Icon>
