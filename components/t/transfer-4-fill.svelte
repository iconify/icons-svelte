<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcr1ef8xs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mcr1ef8xs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:transfer-4-fill" {...props}></Icon>
