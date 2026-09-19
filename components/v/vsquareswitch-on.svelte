<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/f/fn87g02on.css';
import '../../css/j/j1intr00l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="n1lsf0bnc"><path class="fn87g02on"/><path class="j1intr00l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:vsquareswitch-on" {...props}></Icon>
