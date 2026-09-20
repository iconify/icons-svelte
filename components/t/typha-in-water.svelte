<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to5r_0bit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="to5r_0bit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:typha-in-water" {...props}></Icon>
