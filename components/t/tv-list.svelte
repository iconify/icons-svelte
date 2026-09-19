<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltv1hrb8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":384};
const content = `<path class="ltv1hrb8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:tv-list" {...props}></Icon>
