<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv4ot8bdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yv4ot8bdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wallet-fill" {...props}></Icon>
