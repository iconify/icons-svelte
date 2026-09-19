<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/l/lq98u_b3a.css';
import '../../css/d/dygpaf-cm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<g transform="translate(1 4)" class="n1lsf0bnc"><path class="lq98u_b3a"/><ellipse class="dygpaf-cm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:view" {...props}></Icon>
