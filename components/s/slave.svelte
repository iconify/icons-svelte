<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qdjo4sv5r.css';
import '../../css/v/v4mvfkyzo.css';
import '../../css/v/vsuxsc7gj.css';
import '../../css/t/thwemd3eh.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGF9RhgcHB"><g class="ft5dv1b6b"><path class="qdjo4sv5r"/><path class="v4mvfkyzo"/><path class="vsuxsc7gj"/><circle class="thwemd3eh"/></g></mask></defs><path mask="url(#SVGF9RhgcHB)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:slave" {...props}></Icon>
