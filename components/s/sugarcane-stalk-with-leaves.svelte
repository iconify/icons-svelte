<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-r4blpba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="d-r4blpba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:sugarcane-stalk-with-leaves" {...props}></Icon>
