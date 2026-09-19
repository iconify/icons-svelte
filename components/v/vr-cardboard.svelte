<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf8zvibwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="pf8zvibwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:vr-cardboard" {...props}></Icon>
