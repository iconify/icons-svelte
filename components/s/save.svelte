<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub3z3pbln.css';
import '../../css/f/fe-h--bgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ub3z3pbln"/><circle class="fe-h--bgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:save" {...props}></Icon>
