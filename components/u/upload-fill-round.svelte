<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdif4bjbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xdif4bjbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:upload-fill-round" {...props}></Icon>
