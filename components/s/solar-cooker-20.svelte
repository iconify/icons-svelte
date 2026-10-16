<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z22c6ybkz.css';
import '../../css/x/xmr7_lblt.css';
import '../../css/m/mi661mi7p.css';
import '../../css/m/mk7wn8hfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z22c6ybkz"/><path class="xmr7_lblt"/><path class="mi661mi7p"/><path class="mk7wn8hfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-cooker-20" {...props}></Icon>
