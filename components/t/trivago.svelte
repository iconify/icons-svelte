<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic2p6wb-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ic2p6wb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:trivago" {...props}></Icon>
