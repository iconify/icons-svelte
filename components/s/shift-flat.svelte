<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f14q2uffn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="f14q2uffn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:shift-flat" {...props}></Icon>
