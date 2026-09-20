<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/ca0ca5k1s.css';
import '../../css/d/d9v1t7v0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVG2EtlbetS)"><path class="ca0ca5k1s"/></g><defs><clipPath id="SVG2EtlbetS"><path class="d9v1t7v0a"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:whatsapp-filled" {...props}></Icon>
