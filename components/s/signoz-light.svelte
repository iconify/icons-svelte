<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz8n4bbcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vz8n4bbcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:signoz-light" {...props}></Icon>
