<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0-ynyfjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k0-ynyfjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:scan-barcode" {...props}></Icon>
