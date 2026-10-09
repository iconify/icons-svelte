<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqdv09daf.css';
import '../../css/i/ieq7_db9f.css';
import '../../css/e/egp_zuxqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hqdv09daf"/><path class="ieq7_db9f"/><path class="egp_zuxqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermometer-down-48" {...props}></Icon>
