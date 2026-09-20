<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/k/k-m_0bc-f.css';
import '../../css/x/xu5eysboh.css';
import '../../css/j/j_qzpysrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="k-m_0bc-f"/><path class="xu5eysboh"/><path class="j_qzpysrk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:tape-cassette-1" {...props}></Icon>
