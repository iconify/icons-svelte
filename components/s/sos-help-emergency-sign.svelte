<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lenmjtbvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="lenmjtbvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:sos-help-emergency-sign" {...props}></Icon>
