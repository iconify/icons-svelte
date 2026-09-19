<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5t6vubnr.css';
import '../../css/o/ow_l13b0g.css';
import '../../css/a/ambai7ovl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="z5t6vubnr"/><path class="ow_l13b0g"/><path class="ambai7ovl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:wallet" {...props}></Icon>
