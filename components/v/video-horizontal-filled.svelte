<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nh7axibfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nh7axibfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:video-horizontal-filled" {...props}></Icon>
