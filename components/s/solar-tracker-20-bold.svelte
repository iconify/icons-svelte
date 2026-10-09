<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/al_ly38km.css';
import '../../css/u/uav-pacbt.css';
import '../../css/a/ag99qbbai.css';
import '../../css/l/l7namiv5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="al_ly38km"/><path class="uav-pacbt"/><path class="ag99qbbai"/><path class="l7namiv5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-tracker-20-bold" {...props}></Icon>
