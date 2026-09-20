<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wduc6h5_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wduc6h5_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:text-summary-rtl" {...props}></Icon>
