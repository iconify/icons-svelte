<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxi2z2bbm.css';
import '../../css/n/nlc3y1j7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":18,"height":20,"left":3,"top":2};
const content = `<path class="fxi2z2bbm"/><circle class="nlc3y1j7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ultanimus-dark" {...props}></Icon>
