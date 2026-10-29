<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/z/zmxobqbxk.css';
import '../../css/o/o7-ag87sb.css';
import '../../css/d/dfa4tmbvu.css';
import '../../css/s/smy6rvbml.css';
import '../../css/a/ao7apwbgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="wm-deco zmxobqbxk"/><path class="o7-ag87sb wm-deco"/><path class="dfa4tmbvu wm-k"/><path class="smy6rvbml wm-a"/><path class="ao7apwbgn wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:tornado-blueprint" {...props}></Icon>
