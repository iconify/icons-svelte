<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfrchkbrg.css';
import '../../css/t/tlsclv64c.css';
import '../../css/p/p_tmywbwe.css';
import '../../css/e/e-_g3_llx.css';
import '../../css/l/lb80qlbob.css';
import '../../css/n/nvr1rrali.css';
import '../../css/p/pu864wbja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<g class="rfrchkbrg"><ellipse class="tlsclv64c"/><path class="p_tmywbwe"/><path class="e-_g3_llx"/></g><g class="lb80qlbob"><path class="nvr1rrali"/><path class="pu864wbja"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:tomato" {...props}></Icon>
