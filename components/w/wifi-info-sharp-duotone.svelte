<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/a/akajwubis.css';
import '../../css/y/yepmwko9k.css';
import '../../css/r/r8p08nb8h.css';
import '../../css/x/xzzb1ne8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="akajwubis"/><path class="yepmwko9k"/><path class="r8p08nb8h"/><path class="xzzb1ne8n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:wifi-info-sharp-duotone" {...props}></Icon>
