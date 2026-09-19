<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr6a2-c4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="kr6a2-c4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:stopwatch-20" {...props}></Icon>
