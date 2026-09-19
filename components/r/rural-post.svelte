<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/p6z0y3b1u.css';
import '../../css/n/nzxkb6bsg.css';
import '../../css/g/gjraduyzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="p6z0y3b1u"/><path class="nzxkb6bsg"/><path class="gjraduyzd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:rural-post" {...props}></Icon>
