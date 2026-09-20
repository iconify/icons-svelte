<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/a8neukw-z.css';
import '../../css/n/nhwshp5mj.css';
import '../../css/l/luthdg-vg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><circle class="a8neukw-z"/><path clip-rule="evenodd" class="nhwshp5mj"/><path class="luthdg-vg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:user-heart-duotone" {...props}></Icon>
