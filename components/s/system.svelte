<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpl_e0shw.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG7auVBcPn"><path class="rpl_e0shw"/></mask></defs><path mask="url(#SVG7auVBcPn)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:system" {...props}></Icon>
