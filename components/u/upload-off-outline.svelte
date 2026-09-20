<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfedg_btm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bfedg_btm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:upload-off-outline" {...props}></Icon>
