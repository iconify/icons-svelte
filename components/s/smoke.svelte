<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/l/lao2y7iei.css';
import '../../css/k/k10jtebwe.css';
import '../../css/q/qkcequqdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="lao2y7iei"/><path class="k10jtebwe"/><path class="qkcequqdr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:smoke" {...props}></Icon>
