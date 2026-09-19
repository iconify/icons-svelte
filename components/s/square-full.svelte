<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1p-v2bxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z1p-v2bxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:square-full" {...props}></Icon>
