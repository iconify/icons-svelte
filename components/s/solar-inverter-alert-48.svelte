<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/et_wnkuox.css';
import '../../css/w/wqhrjbcye.css';
import '../../css/i/ikpbwe38b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="et_wnkuox"/><path class="wqhrjbcye"/><path class="ikpbwe38b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-inverter-alert-48" {...props}></Icon>
