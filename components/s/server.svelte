<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj2xsotgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mj2xsotgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:server" {...props}></Icon>
