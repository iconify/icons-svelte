<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixma8s7gr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ixma8s7gr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:window-restore" {...props}></Icon>
