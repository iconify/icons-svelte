<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp9o_9agn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="rp9o_9agn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:travel-transportation-airplane-travel-plane-adventure-airplane" {...props}></Icon>
