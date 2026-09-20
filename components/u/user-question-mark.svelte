<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/x_4i1x07g.css';
import '../../css/z/z0aeb7bio.css';
import '../../css/e/e3livhuwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="x_4i1x07g"/><path class="z0aeb7bio"/><path class="e3livhuwh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:user-question-mark" {...props}></Icon>
