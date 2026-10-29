<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xhp6tur6s.css';
import '../../css/i/ia6ikvh9r.css';
import '../../css/n/n0mw1qblu.css';
import '../../css/o/odnmdzi_x.css';
import '../../css/d/dorpla9vi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k xhp6tur6s"/><path class="ia6ikvh9r wm-a"/><path class="n0mw1qblu wm-shadow"/><path class="odnmdzi_x wm-k"/><path class="dorpla9vi wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:route-engrave" {...props}></Icon>
