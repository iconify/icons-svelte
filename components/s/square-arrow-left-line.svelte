<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz5qr-wbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oz5qr-wbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:square-arrow-left-line" {...props}></Icon>
