<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rio-24bds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="rio-24bds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:smoking" {...props}></Icon>
