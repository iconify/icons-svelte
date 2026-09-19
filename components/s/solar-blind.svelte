<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/u/uw6kyrbng.css';
import '../../css/s/snbrnrc_w.css';
import '../../css/o/olyp84b8n.css';
import '../../css/c/c007ltvaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="n1lsf0bnc"><g transform="translate(3)"><path class="uw6kyrbng"/><ellipse class="snbrnrc_w"/><path class="olyp84b8n"/></g><path class="c007ltvaa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:solar-blind" {...props}></Icon>
