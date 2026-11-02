<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxvt099fo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxvt099fo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:upload-3-fill" {...props}></Icon>
