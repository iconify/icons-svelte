<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi9mw4qcx.css';
import '../../css/y/yz--wtxhz.css';
import '../../css/h/hubf0zbho.css';
import '../../css/b/bau81vnse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bi9mw4qcx"/><path class="yz--wtxhz"/><path class="hubf0zbho"/><path class="bau81vnse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scales-20-bold" {...props}></Icon>
