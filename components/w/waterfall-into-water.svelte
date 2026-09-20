<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw0v0acxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pw0v0acxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:waterfall-into-water" {...props}></Icon>
