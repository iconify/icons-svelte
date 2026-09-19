<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/n/numvsbbtg.css';
import '../../css/t/tbhcwf75b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ufeehvblu"><path class="numvsbbtg"/><path class="tbhcwf75b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:seek-step" {...props}></Icon>
