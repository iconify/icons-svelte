<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s53vmbcgz.css';
import '../../css/m/m1yihhu0h.css';
import '../../css/r/repkyhzkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s53vmbcgz"><path class="m1yihhu0h"/><path class="repkyhzkx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:youtube" {...props}></Icon>
