<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyl23qbli.css';
import '../../css/u/uy_2stbfh.css';
import '../../css/k/k2l5gbcnd.css';
import '../../css/o/o1615ib4d.css';
import '../../css/b/b0xi1bjln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uyl23qbli"/><path class="uy_2stbfh"/><path class="k2l5gbcnd"/><path class="o1615ib4d"/><path class="b0xi1bjln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-emojis:waving-hand-2" {...props}></Icon>
