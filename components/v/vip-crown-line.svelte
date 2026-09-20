<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntcvex3pb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ntcvex3pb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:vip-crown-line" {...props}></Icon>
