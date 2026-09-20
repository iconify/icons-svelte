<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/m/mot0enb-y.css';
import '../../css/b/blad_456u.css';
import '../../css/c/cf_fpwv8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="mot0enb-y"/><path class="blad_456u"/><path class="cf_fpwv8i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:speaker-2-flat" {...props}></Icon>
