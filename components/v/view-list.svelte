<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh22k8bct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":368,"height":384};
const content = `<path class="gh22k8bct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:view-list" {...props}></Icon>
