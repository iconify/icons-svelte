<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo7hwc55t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bo7hwc55t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:world-line" {...props}></Icon>
