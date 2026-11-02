<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2qja5mor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e2qja5mor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:whiteboard-fill" {...props}></Icon>
