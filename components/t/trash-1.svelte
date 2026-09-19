<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sup606y1b.css';
import '../../css/b/blcprgz6v.css';
import '../../css/n/nlp7aobgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="sup606y1b"/><path class="blcprgz6v"/><path class="nlp7aobgj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:trash-1" {...props}></Icon>
