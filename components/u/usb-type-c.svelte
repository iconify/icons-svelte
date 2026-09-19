<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/n/n2915hbaq.css';
import '../../css/m/my8fvdb9s.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGaFhASdFG"><g class="wwvp95byt"><path class="n2915hbaq"/><path class="my8fvdb9s"/></g></mask></defs><path mask="url(#SVGaFhASdFG)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:usb-type-c" {...props}></Icon>
