<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfxdwobkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bfxdwobkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:undo" {...props}></Icon>
