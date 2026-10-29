<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/a/alfbd7bhz.css';
import '../../css/a/aplig2bpt.css';
import '../../css/j/jkj98vkgf.css';
import '../../css/m/m3y59dfla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="alfbd7bhz wm-deco"/><path class="aplig2bpt wm-deco"/><path class="jkj98vkgf wm-deco"/><path class="m3y59dfla"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:triangle-blueprint" {...props}></Icon>
