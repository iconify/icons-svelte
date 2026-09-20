<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_pxrxg6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="g_pxrxg6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:three-circular-pills" {...props}></Icon>
