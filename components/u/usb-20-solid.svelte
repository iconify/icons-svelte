<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vscatsm3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="vscatsm3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:usb-20-solid" {...props}></Icon>
