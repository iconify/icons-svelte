<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/t/tf6rn230q.css';
import '../../css/s/ssgpo9gdy.css';
import '../../css/p/plgn6t3fk.css';
import '../../css/l/lwothbb2u.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG6etfYbsL"><g class="v3_i3wktz"><rect class="tf6rn230q"/><path class="ssgpo9gdy"/><ellipse class="plgn6t3fk"/><path class="lwothbb2u"/></g></mask></defs><path mask="url(#SVG6etfYbsL)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:scoreboard" {...props}></Icon>
