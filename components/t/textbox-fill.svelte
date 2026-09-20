<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh49b7bgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xh49b7bgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:textbox-fill" {...props}></Icon>
