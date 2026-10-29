<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/i87ljq8sy.css';
import '../../css/s/srigqbf1b.css';
import '../../css/w/w0rbxob2c.css';
import '../../css/z/zrt6lub-k.css';
import '../../css/v/v6en1acrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="i87ljq8sy"/><path class="srigqbf1b wm-k"/><path class="w0rbxob2c wm-k"/><path class="wm-s zrt6lub-k"/><path class="v6en1acrc wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:user-x-sketch" {...props}></Icon>
