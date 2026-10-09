<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n669t5b-i.css';
import '../../css/d/d1jrieb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n669t5b-i"/><path class="d1jrieb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermal-camera-48-bold" {...props}></Icon>
