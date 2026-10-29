<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/o/ounuhul-g.css';
import '../../css/z/z972s-b0h.css';
import '../../css/g/gq5wgor7s.css';
import '../../css/d/dhjxlpbbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="ounuhul-g wm-deco"/><path class="wm-deco z972s-b0h"/><path class="gq5wgor7s wm-k"/><path class="dhjxlpbbc wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:user-cog-blueprint" {...props}></Icon>
