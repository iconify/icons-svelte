<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7cy_2mli.css';
import '../../css/j/j30vuwbhr.css';
import '../../css/p/p1h-zgy2y.css';
import '../../css/v/vu-ogmxzq.css';
import '../../css/s/sl0bimztx.css';
import '../../css/k/kc_qveb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m7cy_2mli"/><path class="j30vuwbhr"/><path class="p1h-zgy2y"/><path class="vu-ogmxzq"/><path class="sl0bimztx"/><path class="kc_qveb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:us-mobile" {...props}></Icon>
