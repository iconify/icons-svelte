<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/m/mun8-6qsp.css';
import '../../css/v/v5r32fbat.css';
import '../../css/h/hxx-u4vvz.css';
import '../../css/z/zpwhebc3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="mun8-6qsp"/><path class="v5r32fbat"/><path class="hxx-u4vvz"/><path class="zpwhebc3e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:users-outline" {...props}></Icon>
