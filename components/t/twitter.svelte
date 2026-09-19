<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt3dg-b7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1600,"height":1280};
const content = `<path class="xt3dg-b7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:twitter" {...props}></Icon>
