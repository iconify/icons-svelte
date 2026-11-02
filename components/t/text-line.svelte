<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yc7er2vcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yc7er2vcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:text-line" {...props}></Icon>
