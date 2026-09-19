<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxok0n99r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="cxok0n99r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:search-in-page" {...props}></Icon>
