<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd6ancbgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xd6ancbgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tubehaus-light" {...props}></Icon>
