<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtqa41btu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rtqa41btu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:t-shirt-line" {...props}></Icon>
