<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw3x_bcqz.css';
import '../../css/y/ywzq7itsb.css';
import '../../css/w/wz0-7abar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lw3x_bcqz"/><path class="ywzq7itsb"/><path class="wz0-7abar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:voltage-source-48" {...props}></Icon>
