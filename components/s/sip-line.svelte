<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brkwi-iqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="brkwi-iqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:sip-line" {...props}></Icon>
