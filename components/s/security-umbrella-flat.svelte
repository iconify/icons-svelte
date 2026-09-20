<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/p/p4hsu1cam.css';
import '../../css/n/nf6h_omja.css';
import '../../css/n/ncufwjbwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="p4hsu1cam"/><path class="nf6h_omja"/><path class="ncufwjbwc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:security-umbrella-flat" {...props}></Icon>
