<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk_is3nbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zk_is3nbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:video-camera-gloss" {...props}></Icon>
