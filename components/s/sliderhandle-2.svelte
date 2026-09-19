<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/l/lm0y67cgx.css';
import '../../css/w/wvor-jbep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="n1lsf0bnc"><path class="lm0y67cgx"/><path class="wvor-jbep"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:sliderhandle-2" {...props}></Icon>
