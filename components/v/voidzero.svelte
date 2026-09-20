<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t9ru37blf.css';
import '../../css/v/v0v7gbcfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":400,"height":400};
const content = `<g class="ft5dv1b6b"><circle class="t9ru37blf"/><path class="v0v7gbcfe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:voidzero" {...props}></Icon>
