<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/t46nd_b7v.css';
import '../../css/b/b4zzipb8w.css';
import '../../css/s/sfvyxjmsv.css';
import '../../css/b/bfd9jmbir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="t46nd_b7v wm-k"/><path class="b4zzipb8w wm-a"/><path class="sfvyxjmsv wm-k"/><path class="bfd9jmbir wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:swap-sketch" {...props}></Icon>
