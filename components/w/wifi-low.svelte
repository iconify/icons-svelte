<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4cec1b5g.css';
import '../../css/d/dijuj1icq.css';
import '../../css/n/n7436gv2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="i4cec1b5g"><path class="dijuj1icq"/><path class="n7436gv2b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:wifi-low" {...props}></Icon>
