<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn4c03_ef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="sn4c03_ef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:ux" {...props}></Icon>
