<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wm-nhl8rc.css';
import '../../css/x/xlja3acan.css';
import '../../css/n/np43tbbbg.css';
import '../../css/e/e-n1u_b2f.css';
import '../../css/g/gz9__31di.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wm-nhl8rc"/><circle class="xlja3acan"/><path class="np43tbbbg"/><circle class="e-n1u_b2f"/><path class="gz9__31di"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:webcam" {...props}></Icon>
