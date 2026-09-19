<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh96yfr3m.css';
import '../../css/b/ba4pmswhb.css';
import '../../css/d/dzb76ub5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zh96yfr3m"/><path class="ba4pmswhb"/><path class="dzb76ub5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:speakeronesoundwave" {...props}></Icon>
