<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3jerqblc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="o3jerqblc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:window-compact" {...props}></Icon>
