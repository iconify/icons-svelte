<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wuyjo_bfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wuyjo_bfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:slideshow-filled" {...props}></Icon>
