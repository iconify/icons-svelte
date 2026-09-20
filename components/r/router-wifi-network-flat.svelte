<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/r/rvqnfbaaf.css';
import '../../css/t/tt5hhcckr.css';
import '../../css/y/y8oq2gb1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="rvqnfbaaf"/><path class="tt5hhcckr"/><path class="y8oq2gb1u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:router-wifi-network-flat" {...props}></Icon>
