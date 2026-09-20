<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cscv_fw-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cscv_fw-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:system76" {...props}></Icon>
