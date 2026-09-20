<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/m/mexdldrmp.css';
import '../../css/r/r0xlvib1h.css';
import '../../css/v/v9-8lib4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="mexdldrmp"/><path class="r0xlvib1h"/><path class="v9-8lib4s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:whitesource-logo-3" {...props}></Icon>
