<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cseet96gg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":480,"height":512};
const content = `<path class="cseet96gg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:vial" {...props}></Icon>
