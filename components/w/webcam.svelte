<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqm_ipb1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xqm_ipb1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:webcam" {...props}></Icon>
