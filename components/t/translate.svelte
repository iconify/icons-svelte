<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_l2z6bml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":432};
const content = `<path class="r_l2z6bml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:translate" {...props}></Icon>
