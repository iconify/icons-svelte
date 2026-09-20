<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtowsomii.css';
import '../../css/v/v7y0zackt.css';
import '../../css/e/edk22ibmj.css';
import '../../css/a/aer981g6j.css';
import '../../css/z/zdy_qebhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="v7y0zackt"/><path class="edk22ibmj"/><path class="aer981g6j"/><path class="zdy_qebhw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:translate" {...props}></Icon>
