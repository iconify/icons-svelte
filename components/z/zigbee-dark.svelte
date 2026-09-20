<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1u6t7xfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j1u6t7xfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zigbee-dark" {...props}></Icon>
