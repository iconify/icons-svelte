<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s98b-2bjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s98b-2bjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:sedan-under-taxi-checkerboard" {...props}></Icon>
