<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up1479bcz.css';
import '../../css/n/nxbjncgfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="up1479bcz"/><path class="nxbjncgfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:zoom-in" {...props}></Icon>
