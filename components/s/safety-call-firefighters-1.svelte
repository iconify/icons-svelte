<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/r/ro7o76b0x.css';
import '../../css/b/bhb5ffbim.css';
import '../../css/e/eo77zm_ub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ro7o76b0x"/><path class="bhb5ffbim"/><path class="eo77zm_ub"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:safety-call-firefighters-1" {...props}></Icon>
