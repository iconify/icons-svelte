<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tib1-l6ty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tib1-l6ty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:scan-barcode" {...props}></Icon>
