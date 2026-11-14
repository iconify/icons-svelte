<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b78pnzbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b78pnzbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:vscode" {...props}></Icon>
