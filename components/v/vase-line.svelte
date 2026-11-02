<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrktfpb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrktfpb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:vase-line" {...props}></Icon>
