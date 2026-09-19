<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_3cmje0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":480};
const content = `<path class="j_3cmje0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:wrench" {...props}></Icon>
