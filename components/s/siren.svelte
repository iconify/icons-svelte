<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/unh320b8e.css';
import '../../css/b/b5yiy186s.css';
import '../../css/l/l7uasacuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="unh320b8e"/><path clip-rule="evenodd" class="b5yiy186s"/><path class="l7uasacuk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:siren" {...props}></Icon>
