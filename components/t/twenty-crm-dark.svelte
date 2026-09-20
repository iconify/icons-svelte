<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sof4l1tbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sof4l1tbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:twenty-crm-dark" {...props}></Icon>
