<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7yo8v4vs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h7yo8v4vs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sunrise-line" {...props}></Icon>
