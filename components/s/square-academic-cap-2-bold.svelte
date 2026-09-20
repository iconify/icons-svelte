<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/asgo7gbiy.css';
import '../../css/v/vido6rbat.css';
import '../../css/n/nbadl6rrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="asgo7gbiy"/><path class="vido6rbat"/><path class="nbadl6rrm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-academic-cap-2-bold" {...props}></Icon>
