<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/ujy0l2b2e.css';
import '../../css/h/hui8lvb1c.css';
import '../../css/i/ifzbg_-en.css';
import '../../css/b/bou945bat.css';
import '../../css/h/hqlqb8bfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ujy0l2b2e wm-k"/><path class="hui8lvb1c wm-a"/><path class="ifzbg_-en wm-shadow"/><path class="bou945bat wm-k"/><path class="hqlqb8bfm wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:trees-engrave" {...props}></Icon>
