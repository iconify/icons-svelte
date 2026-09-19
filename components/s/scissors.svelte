<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jw6rkebmt.css';
import '../../css/s/ss8lgbcwv.css';
import '../../css/p/psdc-ub0r.css';
import '../../css/a/a4ypdebsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="jw6rkebmt"/><path class="ss8lgbcwv"/><path class="psdc-ub0r"/><circle class="a4ypdebsh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:scissors" {...props}></Icon>
