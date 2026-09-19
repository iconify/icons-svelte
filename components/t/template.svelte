<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv5f_v8gl.css';
import '../../css/m/mpb976b_h.css';
import '../../css/m/mbjqfdc5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pv5f_v8gl"/><path class="mpb976b_h"/><path class="mbjqfdc5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:template" {...props}></Icon>
