<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s31pbgi7y.css';
import '../../css/m/mxan4gp1r.css';
import '../../css/v/vp9gn9sho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s31pbgi7y"/><path class="mxan4gp1r"/><path class="vp9gn9sho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wifi-48" {...props}></Icon>
