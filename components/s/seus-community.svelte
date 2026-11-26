<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/k/k4xah3b6c.css';
import '../../css/w/whl43ccdj.css';
import '../../css/k/kihtoab6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":840,"height":840};
const content = `<g class="bi12bsetm"><path class="k4xah3b6c"/><path class="whl43ccdj"/><path class="kihtoab6b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:seus-community" {...props}></Icon>
