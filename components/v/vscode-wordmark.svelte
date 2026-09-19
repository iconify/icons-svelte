<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbr94kb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="sbr94kb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:vscode-wordmark" {...props}></Icon>
