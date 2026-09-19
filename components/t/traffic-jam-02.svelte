<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/i/ijbv10b3u.css';
import '../../css/z/zyit0rs6g.css';
import '../../css/z/z7nlpshuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ijbv10b3u"/><path class="zyit0rs6g"/><path class="z7nlpshuv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:traffic-jam-02" {...props}></Icon>
