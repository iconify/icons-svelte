<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/uox1_xncs.css';
import '../../css/f/fao-xubsm.css';
import '../../css/m/mbbow6b3r.css';
import '../../css/d/dpj3u_-0n.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG596qwe5J"><g class="ft5dv1b6b"><path class="uox1_xncs"/><path clip-rule="evenodd" class="fao-xubsm"/><path class="mbbow6b3r"/><path class="dpj3u_-0n"/></g></mask></defs><path mask="url(#SVG596qwe5J)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:save" {...props}></Icon>
