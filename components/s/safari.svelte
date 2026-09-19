<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/q/qbqs7jbro.css';
import '../../css/w/websu8mzr.css';
import '../../css/g/gxt617bhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="qbqs7jbro"/><path class="websu8mzr"/><path class="gxt617bhz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:safari" {...props}></Icon>
