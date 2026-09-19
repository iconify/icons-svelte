<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulra56alq.css';
import '../../css/b/bys5gtajl.css';
import '../../css/m/ms4qewg_b.css';
import '../../css/v/vdav4blva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="ulra56alq"><path class="bys5gtajl"/><path class="ms4qewg_b"/><path class="vdav4blva"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:web-assembly" {...props}></Icon>
