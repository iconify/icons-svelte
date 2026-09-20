<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kvn3d2vll.css';
import '../../css/a/ak51bicdp.css';
import '../../css/a/asmo-1zgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kvn3d2vll"/><path class="ak51bicdp"/><path class="asmo-1zgb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:squares-filled" {...props}></Icon>
