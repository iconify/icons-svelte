<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh5j54mvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xh5j54mvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:size-uniform-filled" {...props}></Icon>
