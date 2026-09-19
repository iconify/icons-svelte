<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2h_x22up.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a2h_x22up"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:twitter" {...props}></Icon>
