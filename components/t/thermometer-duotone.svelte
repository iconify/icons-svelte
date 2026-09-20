<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bckavcbdl.css';
import '../../css/d/d958dab4i.css';
import '../../css/f/fkxyg9xjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bckavcbdl"/><path class="d958dab4i"/><path clip-rule="evenodd" class="fkxyg9xjl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:thermometer-duotone" {...props}></Icon>
