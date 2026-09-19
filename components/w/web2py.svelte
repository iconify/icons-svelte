<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpk_aciym.css';
import '../../css/a/aentn7bbl.css';
import '../../css/s/spc4sabls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="rpk_aciym"/><path class="aentn7bbl"/><path class="spc4sabls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:web2py" {...props}></Icon>
