<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnb03vb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="wnb03vb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:trend-upward-circle" {...props}></Icon>
