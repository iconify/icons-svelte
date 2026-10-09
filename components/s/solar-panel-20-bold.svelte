<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs1iioq3v.css';
import '../../css/u/ujdtqrbjr.css';
import '../../css/t/t5fnm26xn.css';
import '../../css/d/d2qyootpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gs1iioq3v"/><path class="ujdtqrbjr"/><path class="t5fnm26xn"/><path class="d2qyootpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-panel-20-bold" {...props}></Icon>
