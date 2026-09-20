<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8oo7gb6g.css';
import '../../css/m/m03j44bzn.css';
import '../../css/g/glvsvvb8w.css';
import '../../css/w/we-rlobyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="m03j44bzn"/><path class="glvsvvb8w"/><path class="we-rlobyj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:sticky-notes-6" {...props}></Icon>
