<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xz2z7f3fq.css';
import '../../css/t/t_f0x_b-c.css';
import '../../css/n/np5y80p8g.css';
import '../../css/p/psw603pny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xz2z7f3fq"/><path class="t_f0x_b-c"/><path class="np5y80p8g"/><path class="psw603pny"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:rv-outline" {...props}></Icon>
