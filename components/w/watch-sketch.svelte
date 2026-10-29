<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/ahg3o2b7k.css';
import '../../css/t/tpy81lbbx.css';
import '../../css/z/zmgde5b3b.css';
import '../../css/b/b8f2ikipk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ahg3o2b7k"/><path class="tpy81lbbx wm-a"/><path class="wm-k zmgde5b3b"/><path class="b8f2ikipk wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:watch-sketch" {...props}></Icon>
