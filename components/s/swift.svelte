<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vefif0bcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vefif0bcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:swift" {...props}></Icon>
