<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/g/gjdc2nvab.css';
import '../../css/w/wb4hhokrb.css';
import '../../css/e/esa11jb9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="gjdc2nvab"/><path class="wb4hhokrb"/><path class="esa11jb9o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:route" {...props}></Icon>
