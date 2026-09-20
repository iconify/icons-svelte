<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scc50pnyt.css';
import '../../css/w/wgfto0gvm.css';
import '../../css/i/i0im9gb4o.css';
import '../../css/o/oyapxxb1h.css';
import '../../css/h/h1tlmbc9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="scc50pnyt"/><path class="wgfto0gvm"/><path class="i0im9gb4o"/><path class="oyapxxb1h"/><path class="h1tlmbc9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:wire" {...props}></Icon>
