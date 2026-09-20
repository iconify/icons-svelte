<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/x/x3keqtbrj.css';
import '../../css/t/tvnupccgq.css';
import '../../css/j/ju3tvgbmc.css';
import '../../css/u/u4kqcvbpc.css';
import '../../css/q/qwljq9bty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":59,"height":59};
const content = `<g class="bi12bsetm"><path class="x3keqtbrj"/><path class="tvnupccgq"/><path class="ju3tvgbmc"/><path class="u4kqcvbpc"/><path class="qwljq9bty"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:transloadit" {...props}></Icon>
