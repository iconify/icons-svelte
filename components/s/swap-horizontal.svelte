<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz3r-qb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rz3r-qb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:swap-horizontal" {...props}></Icon>
