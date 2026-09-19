<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcp9m9fsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mcp9m9fsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:telescope" {...props}></Icon>
