<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/d/dt-je9w2i.css';
import '../../css/a/ad6etcbld.css';
import '../../css/w/wd2oux1ap.css';
import '../../css/i/iaurxkbqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="dt-je9w2i"/><path class="ad6etcbld"/><path class="wd2oux1ap"/><path class="iaurxkbqz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:shopping-basket-arrow-in" {...props}></Icon>
