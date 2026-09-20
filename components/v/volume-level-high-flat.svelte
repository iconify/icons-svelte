<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/n/na-paxbuk.css';
import '../../css/m/ms-45pbir.css';
import '../../css/m/mfvyn3b0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="na-paxbuk"/><path class="ms-45pbir"/><path class="mfvyn3b0e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:volume-level-high-flat" {...props}></Icon>
