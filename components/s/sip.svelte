<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f5v0r7ble.css';
import '../../css/l/l-ohcb8tc.css';
import '../../css/w/wbx9gobfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f5v0r7ble"/><path class="l-ohcb8tc"/><path class="wbx9gobfg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:sip" {...props}></Icon>
