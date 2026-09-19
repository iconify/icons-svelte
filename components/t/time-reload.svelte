<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/o/o1_3dvb8s.css';
import '../../css/t/t8dy76v2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<g class="n1lsf0bnc"><path class="o1_3dvb8s"/><path class="t8dy76v2z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:time-reload" {...props}></Icon>
