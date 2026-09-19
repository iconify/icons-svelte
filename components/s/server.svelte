<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/ztur-t_2p.css';
import '../../css/n/nqiw-hxzo.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGedoEBbPO"><g class="ft5dv1b6b"><path class="ztur-t_2p"/><path class="nqiw-hxzo"/></g></mask></defs><path mask="url(#SVGedoEBbPO)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:server" {...props}></Icon>
