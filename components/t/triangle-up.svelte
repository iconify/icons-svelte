<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3x85-t3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="e3x85-t3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:triangle-up" {...props}></Icon>
