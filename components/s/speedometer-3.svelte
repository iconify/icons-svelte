<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/r/rz8zezu5f.css';
import '../../css/b/bvrootbcu.css';
import '../../css/h/hfrppyb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="s9cl3zbei"><path class="rz8zezu5f"/><path class="bvrootbcu"/><path class="hfrppyb3s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:speedometer-3" {...props}></Icon>
