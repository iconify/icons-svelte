<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/u/ua-z8vb0h.css';
import '../../css/l/lbj5m-bzm.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGs5vV0AcE"><g class="v3_i3wktz"><path class="ua-z8vb0h"/><path class="lbj5m-bzm"/></g></mask></defs><path mask="url(#SVGs5vV0AcE)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:upload-three" {...props}></Icon>
