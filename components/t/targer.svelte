<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/a/aqvjohjml.css';
import '../../css/b/bt2rj5bxf.css';
import '../../css/p/p6iw0hdbg.css';
import '../../css/l/ln_sv0i2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="n1lsf0bnc"><ellipse class="aqvjohjml"/><path class="bt2rj5bxf"/><path class="p6iw0hdbg"/><path class="ln_sv0i2d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:targer" {...props}></Icon>
