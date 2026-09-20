<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/f/fv6kxxgsn.css';
import '../../css/e/ekbzj6b2x.css';
import '../../css/a/ad1ird2hr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="fv6kxxgsn"/><path class="ekbzj6b2x"/><path class="ad1ird2hr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:worldwide-web-disable" {...props}></Icon>
