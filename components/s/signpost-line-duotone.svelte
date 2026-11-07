<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/pf73k4bai.css';
import '../../css/g/gqb61cbma.css';
import '../../css/p/p4r57mjha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pf73k4bai"/><path class="gqb61cbma"/><path class="p4r57mjha"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:signpost-line-duotone" {...props}></Icon>
