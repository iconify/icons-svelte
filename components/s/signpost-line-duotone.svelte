<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/idmd52b7b.css';
import '../../css/g/gqb61cbma.css';
import '../../css/c/c_criydpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="idmd52b7b"/><path class="gqb61cbma"/><path class="c_criydpm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:signpost-line-duotone" {...props}></Icon>
