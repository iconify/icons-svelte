<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/z/z24is80fz.css';
import '../../css/w/wbv9zob4q.css';
import '../../css/z/zotk41bsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="z24is80fz"/><path class="wbv9zob4q"/><path class="zotk41bsy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:shopping-basket-smile-1" {...props}></Icon>
