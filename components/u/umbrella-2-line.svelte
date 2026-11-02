<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wg1q8-kvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wg1q8-kvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:umbrella-2-line" {...props}></Icon>
