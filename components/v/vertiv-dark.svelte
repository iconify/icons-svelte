<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iotd1qbap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iotd1qbap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vertiv-dark" {...props}></Icon>
