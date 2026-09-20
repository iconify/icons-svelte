<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/s/shr9ltubw.css';
import '../../css/t/tlhz8hwex.css';
import '../../css/r/rexpb8zmg.css';
import '../../css/e/e7w7dmbjn.css';
import '../../css/b/bfinew11k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="shr9ltubw"/><path class="tlhz8hwex"/><path class="rexpb8zmg"/><path class="e7w7dmbjn"/><path class="bfinew11k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:ui-page-scroll" {...props}></Icon>
