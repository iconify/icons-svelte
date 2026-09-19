<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/n/n7f99bojn.css';
import '../../css/p/ptxldtbxo.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGfIgoeeRz"><g class="v3_i3wktz"><path class="n7f99bojn"/><path class="ptxldtbxo"/></g></mask></defs><path mask="url(#SVGfIgoeeRz)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:vip" {...props}></Icon>
