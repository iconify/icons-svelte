<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqojcvb-w.css';
import '../../css/g/g64mwldzs.css';
import '../../css/b/bz5lwabqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mqojcvb-w"/><path class="g64mwldzs"/><path class="bz5lwabqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:spring-balance-20-bold" {...props}></Icon>
