<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw6guzb1a.css';
import '../../css/y/y2u9_ob2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<defs><path id="SVGGOv5rcfr" class="tw6guzb1a"/></defs><g clip-rule="evenodd" class="y2u9_ob2n"><use href="#SVGGOv5rcfr"/><use href="#SVGGOv5rcfr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:wifi-100" {...props}></Icon>
