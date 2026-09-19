<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dux_1z-1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dux_1z-1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:wifi" {...props}></Icon>
