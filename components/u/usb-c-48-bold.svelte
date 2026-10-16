<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hca0avbef.css';
import '../../css/g/gmcm_xa4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hca0avbef"/><path class="gmcm_xa4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:usb-c-48-bold" {...props}></Icon>
