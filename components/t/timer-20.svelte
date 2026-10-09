<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi_j_db9s.css';
import '../../css/d/dhxs8ubvn.css';
import '../../css/z/zstpfjybv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oi_j_db9s"/><path class="dhxs8ubvn"/><path class="zstpfjybv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:timer-20" {...props}></Icon>
