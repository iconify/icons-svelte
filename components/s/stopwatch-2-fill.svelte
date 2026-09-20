<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co0ci2b1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="co0ci2b1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:stopwatch-2-fill" {...props}></Icon>
