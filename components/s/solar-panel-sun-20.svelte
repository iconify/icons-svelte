<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvmutbc5a.css';
import '../../css/f/fift-7btu.css';
import '../../css/t/t40xb7btq.css';
import '../../css/s/scfermb5u.css';
import '../../css/v/vkqm4g6bs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vvmutbc5a"/><path class="fift-7btu"/><path class="t40xb7btq"/><path class="scfermb5u"/><path class="vkqm4g6bs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-panel-sun-20" {...props}></Icon>
