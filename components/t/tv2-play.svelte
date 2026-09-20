<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0knsgbev.css';
import '../../css/e/e9axqfb4f.css';
import '../../css/p/pdhn0vbsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c0knsgbev"/><path class="e9axqfb4f"/><path class="pdhn0vbsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tv2-play" {...props}></Icon>
