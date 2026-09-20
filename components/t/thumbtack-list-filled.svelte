<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pw9cfbbav.css';
import '../../css/p/p1dkmfbom.css';
import '../../css/g/gh1dxtbmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="pw9cfbbav"/><path class="p1dkmfbom"/><path clip-rule="evenodd" class="gh1dxtbmo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:thumbtack-list-filled" {...props}></Icon>
