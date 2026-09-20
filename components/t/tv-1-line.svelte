<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdx9atftz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pdx9atftz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tv-1-line" {...props}></Icon>
