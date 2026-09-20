<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/e0bg0mbfi.css';
import '../../css/r/rw9ru_ymu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="e0bg0mbfi"/><path clip-rule="evenodd" class="rw9ru_ymu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:watch2-filled" {...props}></Icon>
