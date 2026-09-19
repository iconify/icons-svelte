<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zs7_t6bwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="zs7_t6bwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:shield-compact" {...props}></Icon>
