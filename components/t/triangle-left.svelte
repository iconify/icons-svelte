<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjyy7ib5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xjyy7ib5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:triangle-left" {...props}></Icon>
