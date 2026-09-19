<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3isa1xzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a3isa1xzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:vscode-insiders" {...props}></Icon>
