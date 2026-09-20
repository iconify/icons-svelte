<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9tkx_0qf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l9tkx_0qf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:triangle-right" {...props}></Icon>
