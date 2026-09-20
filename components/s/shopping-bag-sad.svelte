<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/t/tdzzo8b5j.css';
import '../../css/z/zyvddlb3n.css';
import '../../css/r/rum9obbsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="tdzzo8b5j"/><path class="zyvddlb3n"/><path class="rum9obbsm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:shopping-bag-sad" {...props}></Icon>
