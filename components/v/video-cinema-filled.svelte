<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhv2lljao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhv2lljao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:video-cinema-filled" {...props}></Icon>
