<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7_289hqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="q7_289hqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:storage" {...props}></Icon>
