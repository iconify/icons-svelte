<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr52ofb1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vr52ofb1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:vibrate-filled" {...props}></Icon>
