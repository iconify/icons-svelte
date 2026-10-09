<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkk820mfz.css';
import '../../css/w/w2_kf1b2m.css';
import '../../css/j/jv60--btp.css';
import '../../css/l/lc9zt7qnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hkk820mfz"/><path class="w2_kf1b2m"/><path class="jv60--btp"/><path class="lc9zt7qnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:vehicle-to-grid-48" {...props}></Icon>
