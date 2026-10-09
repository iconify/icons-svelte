<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz_mm6jom.css';
import '../../css/c/c30yugl2g.css';
import '../../css/l/llq1prb2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cz_mm6jom"/><path class="c30yugl2g"/><path class="llq1prb2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scaffolding-20" {...props}></Icon>
