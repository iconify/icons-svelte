<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dn8bx52jh.css';
import '../../css/h/hidu0kbkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dn8bx52jh"/><path class="hidu0kbkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:sunrise-filled" {...props}></Icon>
