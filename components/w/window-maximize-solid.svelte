<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/po_yurb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="po_yurb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:window-maximize-solid" {...props}></Icon>
