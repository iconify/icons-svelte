<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/z/zlkt_lbys.css';
import '../../css/y/yi-zuwb-b.css';
import '../../css/g/gjdjc1rxg.css';
import '../../css/d/d2j0uq01z.css';
import '../../css/o/orc0r4bvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="zlkt_lbys"/><path class="yi-zuwb-b"/><path class="gjdjc1rxg"/><path class="d2j0uq01z"/><path class="orc0r4bvr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:vinyl-record-player-2" {...props}></Icon>
