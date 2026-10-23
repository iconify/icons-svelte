<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov_nythto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ov_nythto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:scan-barcode" {...props}></Icon>
