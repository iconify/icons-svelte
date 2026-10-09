<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jitys6bhk.css';
import '../../css/d/duz8iobvw.css';
import '../../css/v/vbamuvwfj.css';
import '../../css/s/sa1gfwbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jitys6bhk"/><path class="duz8iobvw"/><path class="vbamuvwfj"/><path class="sa1gfwbrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-irradiance-20" {...props}></Icon>
