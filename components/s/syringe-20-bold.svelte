<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzk42qbyr.css';
import '../../css/b/bsr_e2r7t.css';
import '../../css/b/bguuzc2kk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tzk42qbyr"/><path class="bsr_e2r7t"/><path class="bguuzc2kk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:syringe-20-bold" {...props}></Icon>
