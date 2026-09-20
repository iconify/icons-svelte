<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnp03ibug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vnp03ibug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:zazen-line" {...props}></Icon>
