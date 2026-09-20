<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rs2xwbc7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rs2xwbc7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:washington" {...props}></Icon>
