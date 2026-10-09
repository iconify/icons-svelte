<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9597wbne.css';
import '../../css/p/pul26ybon.css';
import '../../css/w/wumlmueqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g9597wbne"/><path class="pul26ybon"/><path class="wumlmueqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-pump-20-bold" {...props}></Icon>
