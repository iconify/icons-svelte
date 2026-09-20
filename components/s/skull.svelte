<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jin2j0b-d.css';
import '../../css/j/jfg0svbzw.css';
import '../../css/k/kh3yuubdz.css';
import '../../css/b/brzn_0bpr.css';
import '../../css/m/mvkqf0b1i.css';
import '../../css/g/gplcw0brg.css';
import '../../css/s/s8xi0xbdk.css';
import '../../css/v/vu7s6tb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="jin2j0b-d"/><path class="jfg0svbzw"/><path class="kh3yuubdz"/><g class="brzn_0bpr"><path class="mvkqf0b1i"/><path class="gplcw0brg"/><circle class="s8xi0xbdk"/><circle class="vu7s6tb7c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:skull" {...props}></Icon>
