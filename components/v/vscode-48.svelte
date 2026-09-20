<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxd6qze7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uxd6qze7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:vscode-48" {...props}></Icon>
