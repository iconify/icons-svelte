<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lwnyuac7m.css';
import '../../css/o/o3-0pkjoj.css';
import '../../css/t/tgtp_hsjq.css';
import '../../css/o/owf7idx3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lwnyuac7m wm-k"/><path class="o3-0pkjoj wm-a"/><path class="tgtp_hsjq wm-k"/><path class="owf7idx3m wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shuffle-sketch" {...props}></Icon>
