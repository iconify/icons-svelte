<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fksazibln.css';
import '../../css/q/qe-q-eb0q.css';
import '../../css/e/e87rnnu0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fksazibln"/><path class="qe-q-eb0q"/><circle class="e87rnnu0f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:wi-fi" {...props}></Icon>
