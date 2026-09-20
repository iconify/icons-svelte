<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/b/b75e_lodc.css';
import '../../css/b/bde9dkbcy.css';
import '../../css/o/o0e_e_brz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="b75e_lodc"/><path class="bde9dkbcy"/><path class="o0e_e_brz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:video-meeting-camera-browser" {...props}></Icon>
