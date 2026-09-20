<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/q/qfkblubnr.css';
import '../../css/z/zeztm9b4g.css';
import '../../css/x/xi4gu7bkr.css';
import '../../css/g/gph2l2k-x.css';
import '../../css/u/u3i10hqhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><rect transform="rotate(90 18 9)" class="qfkblubnr"/><rect transform="rotate(90 18 17)" class="zeztm9b4g"/><rect transform="rotate(-90 3 7)" class="xi4gu7bkr"/><path class="gph2l2k-x"/><path class="u3i10hqhh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:subttasks-light" {...props}></Icon>
