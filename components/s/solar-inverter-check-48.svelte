<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/et_wnkuox.css';
import '../../css/w/wqhrjbcye.css';
import '../../css/q/qdytrdbev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="et_wnkuox"/><path class="wqhrjbcye"/><path class="qdytrdbev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-inverter-check-48" {...props}></Icon>
