<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/p/pogviobod.css';
import '../../css/z/zy8ghtbyu.css';
import '../../css/g/gnmfys7zl.css';
import '../../css/f/fc5zd0b4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="pogviobod"/><path class="zy8ghtbyu"/><path class="gnmfys7zl"/><path class="fc5zd0b4n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:train-outline" {...props}></Icon>
