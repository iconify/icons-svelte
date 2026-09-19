<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lrw3p1b1a.css';
import '../../css/e/e5db84qsw.css';
import '../../css/g/g-brd0vfh.css';
import '../../css/p/p8qto7xhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="lrw3p1b1a"/><rect class="e5db84qsw"/><rect class="g-brd0vfh"/><rect class="p8qto7xhh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:virus" {...props}></Icon>
