<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cx238s3yb.css';
import '../../css/f/fi7cdacqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cx238s3yb"/><path class="fi7cdacqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:shipment-online-monitor-1-bold" {...props}></Icon>
