<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/r/rbw0rrbrh.css';
import '../../css/d/dt1o5lyez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="rbw0rrbrh"/><path class="dt1o5lyez"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:stamp-bold" {...props}></Icon>
