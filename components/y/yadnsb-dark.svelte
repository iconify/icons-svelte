<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf68k4yfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mf68k4yfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yadnsb-dark" {...props}></Icon>
