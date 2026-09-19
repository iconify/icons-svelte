<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/s/sc-c-_bdi.css';
import '../../css/o/olnotz5yy.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGPRmqlcpn"><g class="v3_i3wktz"><path class="sc-c-_bdi"/><path class="olnotz5yy"/></g></mask></defs><path mask="url(#SVGPRmqlcpn)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:wallet-two" {...props}></Icon>
