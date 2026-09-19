<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/u/uf8-wnb5o.css';
import '../../css/r/r9ac3lbwm.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jg897qbgt.css';
import '../../css/r/r3o12cznv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<g class="h01tyzbfu"><circle class="uf8-wnb5o"/><path class="r9ac3lbwm"/></g><g class="cuyn6tgcc"><circle class="jg897qbgt"/><circle class="r3o12cznv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:smiley-stroke-12" {...props}></Icon>
