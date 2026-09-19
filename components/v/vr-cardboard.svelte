<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj3vvdbyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="wj3vvdbyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:vr-cardboard" {...props}></Icon>
