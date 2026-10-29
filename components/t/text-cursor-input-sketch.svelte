<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/holidngbb.css';
import '../../css/a/azqmc2bkv.css';
import '../../css/r/r6we66bvg.css';
import '../../css/t/t5foyebrh.css';
import '../../css/w/wa4w_3bpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="holidngbb wm-k"/><path class="azqmc2bkv wm-k"/><path class="r6we66bvg wm-k"/><path class="t5foyebrh wm-a"/><path class="wa4w_3bpb wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:text-cursor-input-sketch" {...props}></Icon>
