<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbcik9bfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="vbcik9bfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:x-ray" {...props}></Icon>
