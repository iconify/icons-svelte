<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihvmary2y.css';
import '../../css/y/y1oz-jo5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihvmary2y"/><path class="y1oz-jo5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:send-cancel-filled" {...props}></Icon>
