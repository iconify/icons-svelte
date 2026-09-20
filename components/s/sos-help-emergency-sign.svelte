<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mibrfkbvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="mibrfkbvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:sos-help-emergency-sign" {...props}></Icon>
