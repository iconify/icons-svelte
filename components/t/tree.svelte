<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fy_3j5b9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="fy_3j5b9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:tree" {...props}></Icon>
