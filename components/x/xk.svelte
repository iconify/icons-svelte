<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/aui1ykh8i.css';
import '../../css/q/qz_pprnfi.css';
import '../../css/b/bgvh92byt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":200};
const content = `<g class="ft5dv1b6b"><path class="aui1ykh8i"/><path class="qz_pprnfi"/><path class="bgvh92byt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cif:xk" {...props}></Icon>
