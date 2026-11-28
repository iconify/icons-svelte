<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/gcod-bc8e.css';
import '../../css/l/lx4p1b97v.css';
import '../../css/p/pmpia37up.css';
import '../../css/y/y6i34ubff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="gcod-bc8e"/><path class="lx4p1b97v"/><path class="pmpia37up"/><path class="y6i34ubff"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:theater-mask" {...props}></Icon>
