<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/molcvsbva.css';
import '../../css/w/wl_z7s7lf.css';
import '../../css/x/xrey7damx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="molcvsbva wm-k"/><path class="wl_z7s7lf wm-a"/><path class="wm-a xrey7damx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:scan-face" {...props}></Icon>
