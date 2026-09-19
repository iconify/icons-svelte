<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvaqsm1-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="xvaqsm1-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:xmark" {...props}></Icon>
