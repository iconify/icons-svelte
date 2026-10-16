<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_vn9-b7l.css';
import '../../css/k/kj4xs5bkc.css';
import '../../css/g/gxky-sbxf.css';
import '../../css/o/o3qyi4q4j.css';
import '../../css/x/xm5em6khk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g_vn9-b7l"/><path class="kj4xs5bkc"/><path class="gxky-sbxf"/><path class="o3qyi4q4j"/><path class="xm5em6khk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermostat-check-20" {...props}></Icon>
