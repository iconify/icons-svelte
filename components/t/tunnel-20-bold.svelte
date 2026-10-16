<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvt5-9uoj.css';
import '../../css/w/w-jbejb_h.css';
import '../../css/y/yfoxxnbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mvt5-9uoj"/><path class="w-jbejb_h"/><path class="yfoxxnbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tunnel-20-bold" {...props}></Icon>
