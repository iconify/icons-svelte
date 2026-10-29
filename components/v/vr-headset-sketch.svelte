<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/q-hyczb2j.css';
import '../../css/q/qballtb5n.css';
import '../../css/v/vjzfk8ovh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="q-hyczb2j"/><path class="qballtb5n wm-k"/><path class="vjzfk8ovh wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:vr-headset-sketch" {...props}></Icon>
