<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqr8yp28h.css';
import '../../css/f/f4mdfjbca.css';
import '../../css/x/xm577jbwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fqr8yp28h"/><path class="f4mdfjbca"/><path class="xm577jbwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:webcam-48-bold" {...props}></Icon>
