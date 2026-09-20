<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcad-6s8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kcad-6s8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:usb-outline" {...props}></Icon>
