<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/r/rp1xwe1-z.css';
import '../../css/w/wi90qc0tn.css';
import '../../css/g/gjzxlrd4t.css';
import '../../css/f/f9a5_u-iz.css';
import '../../css/j/jce98cbsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="rp1xwe1-z"/><path class="wi90qc0tn"/><path class="gjzxlrd4t"/><path class="f9a5_u-iz"/><path class="jce98cbsi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:trophy" {...props}></Icon>
