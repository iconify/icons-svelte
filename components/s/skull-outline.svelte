<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/e/eemwaab5j.css';
import '../../css/l/l1tjz6bep.css';
import '../../css/l/l3aiq-bqz.css';
import '../../css/b/bi5px2mad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="eemwaab5j"/><path class="l1tjz6bep"/><path class="l3aiq-bqz"/><path class="bi5px2mad"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:skull-outline" {...props}></Icon>
