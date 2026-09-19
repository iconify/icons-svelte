<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pg1-5rbnm.css';
import '../../css/i/i8-ig2bjx.css';
import '../../css/x/xm9hcq-cp.css';
import '../../css/y/yeyg09bzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pg1-5rbnm"/><path class="i8-ig2bjx"/><path class="xm9hcq-cp"/><path class="yeyg09bzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:xbox" {...props}></Icon>
