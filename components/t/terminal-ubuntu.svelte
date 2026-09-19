<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y96bstb6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y96bstb6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:terminal-ubuntu" {...props}></Icon>
