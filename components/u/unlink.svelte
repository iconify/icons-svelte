<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/ray_qnbjg.css';
import '../../css/v/vlvdrabkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="ft5dv1b6b"><path class="ray_qnbjg"/><path class="vlvdrabkl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:unlink" {...props}></Icon>
