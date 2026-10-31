<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wm2m2btlp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm2m2btlp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:sailboat-round" {...props}></Icon>
