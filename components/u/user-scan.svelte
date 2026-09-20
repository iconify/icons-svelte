<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b680p_blz.css';
import '../../css/o/oq-b65kyl.css';
import '../../css/h/hipat9bbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b680p_blz"/><path clip-rule="evenodd" class="oq-b65kyl"/><path class="hipat9bbi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:user-scan" {...props}></Icon>
