<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdjqu4-xy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bdjqu4-xy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:snowcapped-mountain-saddle" {...props}></Icon>
