<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/v/vz2352biu.css';
import '../../css/b/bn7vl2b9s.css';
import '../../css/g/gna721brc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="vz2352biu"/><path class="bn7vl2b9s wm-a"/><path class="gna721brc wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:teapot-solid" {...props}></Icon>
