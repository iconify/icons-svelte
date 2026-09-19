<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/q/qd4_61bdr.css';
import '../../css/n/ny0-f6z0o.css';
import '../../css/g/gmkyp99tb.css';
import '../../css/a/agc8y1l_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="qd4_61bdr"/><path class="ny0-f6z0o"/><path class="gmkyp99tb"/><path class="agc8y1l_a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:subway-outline" {...props}></Icon>
