<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/t/tbu58ltdb.css';
import '../../css/b/bzdv1ob_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="tbu58ltdb"/><path class="bzdv1ob_h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:xpm" {...props}></Icon>
