<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/e/etcb43btd.css';
import '../../css/x/xe_mok4yw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="h01tyzbfu"><path class="etcb43btd"/><path class="xe_mok4yw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:setting-outline" {...props}></Icon>
