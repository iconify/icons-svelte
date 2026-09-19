<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikrlaw81o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="ikrlaw81o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:view-list-alt" {...props}></Icon>
