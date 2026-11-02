<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l32j6t-3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l32j6t-3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:time-duration-fill" {...props}></Icon>
