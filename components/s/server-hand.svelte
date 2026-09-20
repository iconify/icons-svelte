<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/d/dc-opbbnk.css';
import '../../css/f/fqnkg2bwc.css';
import '../../css/f/f99jusbwg.css';
import '../../css/o/o6n94jakv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="dc-opbbnk"/><path class="fqnkg2bwc"/><path class="f99jusbwg"/><path class="o6n94jakv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:server-hand" {...props}></Icon>
