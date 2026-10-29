<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/e/ex8lrup2k.css';
import '../../css/r/rhnsbwb-m.css';
import '../../css/n/nwncmym7l.css';
import '../../css/l/lntbq-b3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="ex8lrup2k wm-deco"/><path class="rhnsbwb-m wm-deco"/><path class="nwncmym7l"/><path class="lntbq-b3k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:ticket-blueprint" {...props}></Icon>
