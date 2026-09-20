<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4r5n9byo.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/x/xa8zo-wvi.css';
import '../../css/n/n05ob-bph.css';
import '../../css/n/nuw89-yss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="k4r5n9byo"/><g class="jn8qy4bru"><path class="xa8zo-wvi"/><path class="n05ob-bph"/><path class="nuw89-yss"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:wheelbarrow" {...props}></Icon>
