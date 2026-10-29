<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/c/c16lvpbmd.css';
import '../../css/d/d9xbqbgcs.css';
import '../../css/r/rbzq4bjzv.css';
import '../../css/p/p29my7dtm.css';
import '../../css/t/t2d-3xa1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="c16lvpbmd wm-deco"/><path class="d9xbqbgcs wm-deco"/><path class="rbzq4bjzv wm-deco"/><path class="p29my7dtm"/><path class="t2d-3xa1h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shield-blueprint" {...props}></Icon>
