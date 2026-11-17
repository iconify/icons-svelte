<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2x2dyavi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l2x2dyavi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:upload-assistant-light" {...props}></Icon>
