<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjuv2pbpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hjuv2pbpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:translate-line" {...props}></Icon>
