<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/i/if8avqb2l.css';
import '../../css/x/x-hw30lbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="n1lsf0bnc"><path class="if8avqb2l"/><path class="x-hw30lbb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:wtc" {...props}></Icon>
