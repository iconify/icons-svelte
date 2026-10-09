<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrgo4ebxh.css';
import '../../css/s/s0l3_tbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vrgo4ebxh"/><path class="s0l3_tbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tv-20" {...props}></Icon>
