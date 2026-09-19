<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3308_fmz.css';
import '../../css/e/e2itionyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3308_fmz"/><path class="e2itionyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:scan-barcode" {...props}></Icon>
