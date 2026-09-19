<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th1r3u7ye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1280,"height":1536};
const content = `<path class="th1r3u7ye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:stack-exchange" {...props}></Icon>
