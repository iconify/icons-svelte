<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/h/hqtysac5g.css';
import '../../css/z/zyb2qu_wj.css';
import '../../css/n/ncjvozvar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="hqtysac5g"/><path class="zyb2qu_wj"/><path class="ncjvozvar"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:threat-folder-flat" {...props}></Icon>
