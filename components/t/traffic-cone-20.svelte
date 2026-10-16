<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chylptbbp.css';
import '../../css/l/lu03jdbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="chylptbbp"/><path class="lu03jdbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:traffic-cone-20" {...props}></Icon>
