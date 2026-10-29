<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hdftlebhb.css';
import '../../css/o/o_i4znb3n.css';
import '../../css/p/pfunrccay.css';
import '../../css/k/kfb2hf1uo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hdftlebhb wm-k"/><path class="o_i4znb3n wm-shadow"/><path class="pfunrccay wm-k"/><path class="kfb2hf1uo wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:water-balloon-engrave" {...props}></Icon>
