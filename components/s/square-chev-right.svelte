<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwv1b8brk.css';
import '../../css/r/r9kyeodza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwv1b8brk"/><path class="r9kyeodza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:square-chev-right" {...props}></Icon>
