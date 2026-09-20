<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvyojlb_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qvyojlb_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:sound-mute-1-filled" {...props}></Icon>
