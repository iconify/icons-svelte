<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxq6f4b9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="vxq6f4b9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:waterfall-11" {...props}></Icon>
