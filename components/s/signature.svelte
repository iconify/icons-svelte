<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/idzrjj4iz.css';
import '../../css/t/t_-i39b5w.css';
import '../../css/l/l2n3c_l2o.css';
import '../../css/d/d30ka7bpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="idzrjj4iz"/><path class="t_-i39b5w"/><path clip-rule="evenodd" class="l2n3c_l2o"/><path class="d30ka7bpr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:signature" {...props}></Icon>
