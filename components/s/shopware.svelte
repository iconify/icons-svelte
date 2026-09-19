<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/piz0fn1_w.css';
import '../../css/y/yqacr5idm.css';
import '../../css/a/auwbk5w3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<g class="piz0fn1_w"><path class="yqacr5idm"/><path class="auwbk5w3x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:shopware" {...props}></Icon>
