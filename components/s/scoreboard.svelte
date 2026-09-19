<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/u/uuiv2_bbd.css';
import '../../css/m/mg9i1cw4h.css';
import '../../css/n/nq-wggb4s.css';
import '../../css/a/am52znbyr.css';
import '../../css/v/vybj90bva.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGnTgIxeTB"><g class="ufeehvblu"><rect class="uuiv2_bbd"/><path class="mg9i1cw4h"/><path class="nq-wggb4s"/><ellipse class="am52znbyr"/><path class="vybj90bva"/></g></mask></defs><path mask="url(#SVGnTgIxeTB)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:scoreboard" {...props}></Icon>
