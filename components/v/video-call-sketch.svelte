<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/b4e3e4bng.css';
import '../../css/n/nrtl1pboi.css';
import '../../css/h/h-m5r7btd.css';
import '../../css/g/gccckqbrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="b4e3e4bng"/><path class="nrtl1pboi wm-a"/><path class="h-m5r7btd wm-k"/><path class="gccckqbrx wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:video-call-sketch" {...props}></Icon>
