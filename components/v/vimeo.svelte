<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu__29aqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zu__29aqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vimeo" {...props}></Icon>
