<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/w/wjgebtbst.css';
import '../../css/m/myatxhbsg.css';
import '../../css/o/ohv-qybzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(1 3)" class="bi12bsetm"><path class="wjgebtbst"/><path class="myatxhbsg"/><rect class="ohv-qybzb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:tags" {...props}></Icon>
