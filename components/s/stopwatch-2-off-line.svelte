<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7nm95z8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j7nm95z8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:stopwatch-2-off-line" {...props}></Icon>
