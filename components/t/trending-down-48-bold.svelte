<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtakimb5j.css';
import '../../css/q/qnyuvicip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qtakimb5j"/><path class="qnyuvicip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:trending-down-48-bold" {...props}></Icon>
