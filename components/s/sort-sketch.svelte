<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/f4fq62boi.css';
import '../../css/o/oos9n2b5s.css';
import '../../css/o/oiiu6_b2q.css';
import '../../css/v/va5hn9blj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="f4fq62boi wm-k"/><path class="oos9n2b5s wm-a"/><path class="oiiu6_b2q wm-k"/><path class="va5hn9blj wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:sort-sketch" {...props}></Icon>
