<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odvnyb7mh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":368,"height":384};
const content = `<path class="odvnyb7mh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:view-column" {...props}></Icon>
