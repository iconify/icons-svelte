<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k61w4fflf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="k61w4fflf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:whistle" {...props}></Icon>
