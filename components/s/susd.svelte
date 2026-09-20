<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2bcx3mob.css';
import '../../css/e/efw24oblo.css';
import '../../css/r/r29q0j4dc.css';
import '../../css/u/uukhb0tao.css';
import '../../css/g/gna-ztm3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q2bcx3mob"/><path class="efw24oblo"/><path class="r29q0j4dc"/><path class="uukhb0tao"/><path class="gna-ztm3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:susd" {...props}></Icon>
