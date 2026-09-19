<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/g/gq8lmn-fl.css';
import '../../css/w/w4k4oubkq.css';
import '../../css/e/eitjcwufr.css';
import '../../css/o/on3a9747h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="gq8lmn-fl"/><path class="w4k4oubkq"/><path class="eitjcwufr"/><path class="on3a9747h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sim-card-outline" {...props}></Icon>
