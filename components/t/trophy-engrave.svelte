<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hfap8z5lo.css';
import '../../css/p/pydtcwi0b.css';
import '../../css/p/pfzd08f0w.css';
import '../../css/r/ri984nurg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hfap8z5lo"/><path class="pydtcwi0b wm-shadow"/><path class="pfzd08f0w"/><path class="ri984nurg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:trophy-engrave" {...props}></Icon>
