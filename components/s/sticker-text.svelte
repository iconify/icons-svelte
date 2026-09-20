<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htlsyzb7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="htlsyzb7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sticker-text" {...props}></Icon>
