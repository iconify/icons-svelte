<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/r/rgcigdc_c.css';
import '../../css/p/p0r1koben.css';
import '../../css/k/ke2-dkbvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="rgcigdc_c"/><path class="p0r1koben"/><path class="ke2-dkbvo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:text-formating-rotate-angle" {...props}></Icon>
