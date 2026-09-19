<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5g_57b6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="t5g_57b6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:stopwatch-20" {...props}></Icon>
