<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/y/ysfxjsqqh.css';
import '../../css/n/nqfk3p38l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="ysfxjsqqh"/><path class="nqfk3p38l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:soup-filled" {...props}></Icon>
