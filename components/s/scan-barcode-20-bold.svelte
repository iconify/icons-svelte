<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwl-lb6rd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hwl-lb6rd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scan-barcode-20-bold" {...props}></Icon>
