<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lba1z4b7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lba1z4b7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:video-off-filled" {...props}></Icon>
