<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmokpm6wb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tmokpm6wb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:vscode-fill" {...props}></Icon>
