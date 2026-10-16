<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skm13gbpu.css';
import '../../css/q/qt_17gbik.css';
import '../../css/g/g_wuh4bxx.css';
import '../../css/l/lzmnrrp8b.css';
import '../../css/m/mxz5qbb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="skm13gbpu"/><path class="qt_17gbik"/><path class="g_wuh4bxx"/><path class="lzmnrrp8b"/><path class="mxz5qbb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-farm-x-20" {...props}></Icon>
