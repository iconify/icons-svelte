<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/b/bge4e0m_e.css';
import '../../css/d/d9_tw6tfv.css';
import '../../css/r/rsvuxndka.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGuvsWselU"><g class="ufeehvblu"><path class="bge4e0m_e"/><path class="d9_tw6tfv"/><path class="rsvuxndka"/></g></mask></defs><path mask="url(#SVGuvsWselU)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:webcam" {...props}></Icon>
