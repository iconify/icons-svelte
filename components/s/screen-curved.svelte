<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/c/co-m62bop.css';
import '../../css/q/qmml9bcel.css';
import '../../css/l/le1tw3baq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="co-m62bop"/><path class="qmml9bcel"/><path class="le1tw3baq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:screen-curved" {...props}></Icon>
