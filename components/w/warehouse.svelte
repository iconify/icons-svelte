<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfu81lbgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="yfu81lbgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:warehouse" {...props}></Icon>
