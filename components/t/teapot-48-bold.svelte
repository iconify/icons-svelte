<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xeyh_rdcv.css';
import '../../css/m/mz5l_db3r.css';
import '../../css/c/c5154m1sd.css';
import '../../css/y/yno-x3bbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xeyh_rdcv"/><path class="mz5l_db3r"/><path class="c5154m1sd"/><path class="yno-x3bbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:teapot-48-bold" {...props}></Icon>
