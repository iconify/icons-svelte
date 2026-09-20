<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/e/enq2l8p_m.css';
import '../../css/o/o9q3skbhp.css';
import '../../css/p/ppm1aachj.css';
import '../../css/u/uk5pr39zp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g class="bi12bsetm"><path class="enq2l8p_m"/><path class="o9q3skbhp"/><path class="ppm1aachj"/><path class="uk5pr39zp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:server" {...props}></Icon>
