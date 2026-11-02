<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s64d5hbcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s64d5hbcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:text-area-line" {...props}></Icon>
