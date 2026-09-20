<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gth9q0crr.css';
import '../../css/i/ia3sgrbqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gth9q0crr"/><path class="ia3sgrbqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:storage-hdd-2" {...props}></Icon>
