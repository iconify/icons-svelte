<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/u/ua5jal-6v.css';
import '../../css/y/ynpcb1bzj.css';
import '../../css/n/nsvyxtbqj.css';
import '../../css/t/ti4702bcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ua5jal-6v"/><path class="ynpcb1bzj"/><path class="nsvyxtbqj"/><path class="ti4702bcp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:website-development-browser-hand" {...props}></Icon>
