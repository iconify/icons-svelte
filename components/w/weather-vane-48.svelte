<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hot0jtf_c.css';
import '../../css/p/p8swzyblw.css';
import '../../css/i/izs6c-bvl.css';
import '../../css/t/tqe-v7b0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hot0jtf_c"/><path class="p8swzyblw"/><path class="izs6c-bvl"/><path class="tqe-v7b0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:weather-vane-48" {...props}></Icon>
