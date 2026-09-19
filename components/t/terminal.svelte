<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/k/kspzgnbsg.css';
import '../../css/u/u_nsrq4io.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGXE6zpcEE"><g class="ufeehvblu"><rect class="kspzgnbsg"/><path class="u_nsrq4io"/></g></mask></defs><path mask="url(#SVGXE6zpcEE)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:terminal" {...props}></Icon>
