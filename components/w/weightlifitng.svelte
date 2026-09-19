<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqq4spbzl.css';
import '../../css/e/ej3ft6qzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="pqq4spbzl"/><path class="ej3ft6qzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:weightlifitng" {...props}></Icon>
