<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpnkqjn8e.css';
import '../../css/i/ifeyr2b5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tpnkqjn8e"/><path class="ifeyr2b5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:server-24" {...props}></Icon>
