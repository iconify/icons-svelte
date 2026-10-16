<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3bu2g2no.css';
import '../../css/i/iyhbzwb_j.css';
import '../../css/y/yfoxxnbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m3bu2g2no"/><path class="iyhbzwb_j"/><path class="yfoxxnbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:vertical-solar-20-bold" {...props}></Icon>
