<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/tvl0obccn.css';
import '../../css/x/xiuiabbcc.css';
import '../../css/o/ofo04lg3k.css';
import '../../css/x/xkpy2fb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="tvl0obccn"/><path class="xiuiabbcc"/><path clip-rule="evenodd" class="ofo04lg3k"/><path class="xkpy2fb9u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:train" {...props}></Icon>
