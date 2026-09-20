<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb9y4lqfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wb9y4lqfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:solar-panel-line" {...props}></Icon>
