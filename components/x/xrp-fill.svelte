<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcilopbey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hcilopbey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:xrp-fill" {...props}></Icon>
