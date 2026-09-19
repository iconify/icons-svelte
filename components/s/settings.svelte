<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyi21vbaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vyi21vbaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:settings" {...props}></Icon>
