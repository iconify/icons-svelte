<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h5vn5qz0x.css';
import '../../css/v/v_x350b_j.css';
import '../../css/n/ndwopbc4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="h5vn5qz0x"/><path class="v_x350b_j"/><path clip-rule="evenodd" class="ndwopbc4m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:surveilance-officer-outline" {...props}></Icon>
