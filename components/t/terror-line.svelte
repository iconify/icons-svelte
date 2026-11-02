<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dimqnxboo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dimqnxboo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:terror-line" {...props}></Icon>
