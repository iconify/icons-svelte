<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/d/d4jw9nboq.css';
import '../../css/h/hh22srh1i.css';
import '../../css/p/p94o0ic_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="d4jw9nboq"/><path class="hh22srh1i"/><path class="p94o0ic_w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:speaker" {...props}></Icon>
