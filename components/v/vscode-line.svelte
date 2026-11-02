<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fen-6uanf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fen-6uanf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:vscode-line" {...props}></Icon>
