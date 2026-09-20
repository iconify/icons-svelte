<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/r/rzgm95thu.css';
import '../../css/z/z_ypc62sw.css';
import '../../css/m/m78giqign.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="rzgm95thu"/><path class="z_ypc62sw"/><path class="m78giqign"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:synchronize-arrows-warning" {...props}></Icon>
