<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/s/slrtq_bwu.css';
import '../../css/y/yvo8g2ena.css';
import '../../css/i/i_mt8hb3h.css';
import '../../css/y/ytyk_-blx.css';
import '../../css/x/xfv2nibzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="slrtq_bwu"/><path class="yvo8g2ena"/><path class="i_mt8hb3h"/><path class="ytyk_-blx"/><path class="xfv2nibzq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:share-radar" {...props}></Icon>
