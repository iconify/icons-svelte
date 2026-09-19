<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f-ntwsbcy.css';
import '../../css/c/cyzopgbdr.css';
import '../../css/a/a8924ab8w.css';
import '../../css/b/bxcg2tb1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="f-ntwsbcy"/><path class="cyzopgbdr"/><path class="a8924ab8w"/><path class="bxcg2tb1i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:surprise-duo" {...props}></Icon>
