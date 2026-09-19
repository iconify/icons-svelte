<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/w/werlsvbgf.css';
import '../../css/r/rlkfsjbzh.css';
import '../../css/t/tibulpbty.css';
import '../../css/v/vp2v9wbli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="werlsvbgf"/><path class="rlkfsjbzh"/><path class="tibulpbty"/><path class="vp2v9wbli"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:watch-fitness-outline" {...props}></Icon>
