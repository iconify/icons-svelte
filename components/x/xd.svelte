<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccj7lubgn.css';
import '../../css/k/kdw8ckbee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":240,"height":234};
const content = `<path class="ccj7lubgn"/><path class="kdw8ckbee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:xd" {...props}></Icon>
