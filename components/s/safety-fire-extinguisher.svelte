<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/e/ewv2ge6ug.css';
import '../../css/p/p7y_1d_fe.css';
import '../../css/z/zt0gv6bln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ewv2ge6ug"/><path class="p7y_1d_fe"/><path class="zt0gv6bln"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:safety-fire-extinguisher" {...props}></Icon>
