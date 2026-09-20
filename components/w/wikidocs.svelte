<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n26s6ub1x.css';
import '../../css/i/iadi1vbcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n26s6ub1x"/><path class="iadi1vbcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wikidocs" {...props}></Icon>
