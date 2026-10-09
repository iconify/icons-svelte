<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_hrlmb2h.css';
import '../../css/t/tbt13x_gy.css';
import '../../css/i/iipfeyb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m_hrlmb2h"/><path class="tbt13x_gy"/><path class="iipfeyb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:service-vessel-48-bold" {...props}></Icon>
