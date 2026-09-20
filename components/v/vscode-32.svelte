<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_q4bkngh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e_q4bkngh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:vscode-32" {...props}></Icon>
