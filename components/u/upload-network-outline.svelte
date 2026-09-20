<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar7hmtfxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ar7hmtfxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:upload-network-outline" {...props}></Icon>
