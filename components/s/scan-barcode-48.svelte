<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn_sm0bct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gn_sm0bct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scan-barcode-48" {...props}></Icon>
