<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gopnm44um.css';
import '../../css/j/j0nq1ogbv.css';
import '../../css/e/ec0z0rb7k.css';
import '../../css/g/gjuy1obec.css';
import '../../css/s/syw3b9bhc.css';
import '../../css/g/gvugorbzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="gopnm44um"><rect class="j0nq1ogbv"/><path class="ec0z0rb7k"/><path class="gjuy1obec"/><path class="syw3b9bhc"/><path class="gvugorbzi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:schedule" {...props}></Icon>
