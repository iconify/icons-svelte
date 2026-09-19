<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/b/b0cnw74gn.css';
import '../../css/j/j0nrwubnn.css';
import '../../css/c/cah5o1biu.css';
import '../../css/r/renz17btl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<g transform="translate(1)" class="n1lsf0bnc"><ellipse class="b0cnw74gn"/><circle class="j0nrwubnn"/><path class="cah5o1biu"/><path class="renz17btl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:trolley-briefcase" {...props}></Icon>
