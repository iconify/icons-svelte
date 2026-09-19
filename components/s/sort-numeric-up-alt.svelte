<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyser73hu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="xyser73hu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:sort-numeric-up-alt" {...props}></Icon>
