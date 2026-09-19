<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqfomkbty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqfomkbty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:video-filled" {...props}></Icon>
