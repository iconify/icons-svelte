<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th7u9ta3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="th7u9ta3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:three-circles-line" {...props}></Icon>
