<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrlu6h6mi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrlu6h6mi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:webcam-video" {...props}></Icon>
