<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yaxvt8d_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yaxvt8d_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:vscode-insiders-outline" {...props}></Icon>
