<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/ug4ve3gnj.css';
import '../../css/f/f6-d95u-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":200};
const content = `<g class="ft5dv1b6b"><path class="ug4ve3gnj"/><path class="f6-d95u-p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cif:so" {...props}></Icon>
