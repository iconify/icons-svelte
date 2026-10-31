<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmux3-dwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmux3-dwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:square-code-gloss" {...props}></Icon>
