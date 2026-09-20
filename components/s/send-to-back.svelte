<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqed0kbod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tqed0kbod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:send-to-back" {...props}></Icon>
