<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brtc7-a1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="brtc7-a1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:voron" {...props}></Icon>
