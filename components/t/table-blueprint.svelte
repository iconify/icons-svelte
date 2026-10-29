<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/j/jrpbbdoby.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/h/hjheo7blk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="jrpbbdoby wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="hjheo7blk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:table-blueprint" {...props}></Icon>
