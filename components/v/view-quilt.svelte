<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s087jmb1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":368,"height":384};
const content = `<path class="s087jmb1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:view-quilt" {...props}></Icon>
