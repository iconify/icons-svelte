<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/w/w1_stzbsr.css';
import '../../css/x/x8du9qb9x.css';
import '../../css/d/dw5kuabjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="w1_stzbsr"/><path class="x8du9qb9x"/><path class="dw5kuabjz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:work-from-home-user-pet-cat" {...props}></Icon>
