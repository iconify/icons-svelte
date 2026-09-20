<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fb52jdbep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fb52jdbep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:stopwatch-line" {...props}></Icon>
