<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/x/x9xer61ny.css';
import '../../css/d/dp0zwgbbl.css';
import '../../css/w/wuyzb9bxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="x9xer61ny"/><path class="dp0zwgbbl"/><path class="wuyzb9bxj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:transfer-pictures-smartphone" {...props}></Icon>
