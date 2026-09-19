<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up4_10tsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="up4_10tsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:triangle-down" {...props}></Icon>
