<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egwdlccgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="egwdlccgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:window-shutter-alert" {...props}></Icon>
