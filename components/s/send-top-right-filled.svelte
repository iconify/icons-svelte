<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ono-tjryk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ono-tjryk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:send-top-right-filled" {...props}></Icon>
